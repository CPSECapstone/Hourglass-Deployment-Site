---
title: Development
nav_order: 5
---

# Development Guide
  Reach comprises of three main components:
  1. React frontend
  2. ASP.NET C# backend
  3. PostgreSQL database

  We primarily use AWS as our cloud service provider. 

---
## Backend Setup
We have scripts in the repo that will handle the majority of the build and deploy pipeline, as well as all the configuration for setting up the Apache server. The following steps are for initalizing the AWS services that we use. Make sure to update the script files if you will be using a different domain. 

### EC2 Setup
Note that the following steps are for creating a single instance. You may also create an autoscaling group and autoscaling configuration using similar configurations.

- Create an EC2 Instance. Any linux instance will do, but we use `Amazon Linux 2 AMI (HVM) x86`.
- Select the instance type and continue. We used a `t2.micro`.
- For IAM role, select an EC2 role for code deploy. If you don't already have one, follow the steps in Code Deploy IAM below.
- Under Advanced Details, paste the following commands in the user data field. These will allow the EC2 to install important packages, including the dotnet framework. It will also setup the correct directory structure.
```console
#!/bin/bash
sudo yum update -y
sudo yum install -y httpd mod_ssl
sudo yum install -y ruby
sudo yum install -y wget
cd /home/ec2-user
wget https://aws-codedeploy-us-east-2.s3.us-east-2.amazonaws.com/latest/install
chmod +x ./install
sudo ./install auto
rm -rf install
curl -sSL -o dotnet.tar.gz https://download.visualstudio.microsoft.com/download/pr/57e63f03-ebdf-4c22-96ff-2b85dc70cf7f/988576869e82a80f4a97ca5a733a5295/dotnet-sdk-3.1.102-linux-x64.tar.gz
sudo mkdir -p /opt/dotnet && sudo tar zxf dotnet.tar.gz -C /opt/dotnet
sudo ln -s /opt/dotnet/dotnet /usr/local/bin
rm -rf dotnet.tar.gz
mkdir Hourglass
mkdir ServerLogs
```
- Configure the security group to only allow inbound/outboud traffic over HTTP/HTTPS, to the database, and to any other service you will be networking with. Also add SSH access to be able to connect to the instance and configure SSL.
- Review and launch the EC2 instance.

### Cloud CI/CD
- Create a CodePipeline
- For the source stage, select Github and connect to your github repo.
- For the build stage, select AWS CodeBuild and select the cloud build project you created. If you haven't created the project, follow the steps in Cloud Build below.
- For the deploy stage, select AWS CodeDeploy and select the application name and deployment group you created. If you haven't created these, follow the steps in Cloud Deploy below. 
- When you are done, press *create pipeline*
- Make sure to edit the script file /scripts/server_config.sh with the updated pipeline name (in case you will have more than one pipeline)
- If you will have a public repo, you can't have the `appsettings` files in the repo. If this is the case, you will need to create an S3 bucket for the configuration. Follow the steps in Cloud Config below. Otherwise, remove the Config artifact related commands from the buildspec.yml file.

#### Cloud Build
- In the CodeBuild console, select *Create a CodeBuild project*
- Set the name for the build.
- Set the Operating System as Amazon Linux 2`
- For everything else, it will be handled from within CodePipeline. You may leave the source and artifacts empty.

#### Cloud Deploy
- In the CodeDeploy console, select *Create applcation*
- Enter a name for the application and select `EC2/On-premises` for the compute platform
- Select *Create deployment group*
- Enter a name for the deployment group
- Select an AWS Codedeploy service role. If you don't have one, create it in the IAM console.
- Configure your deployment preferences. For our purposes, we did not anticapate a large user load so we did not setup any autoscaling. If you do not anticipate a large user load, you can deploy to only one EC2 instance. Under Key put *Name* and Value select the EC2 instance you created earlier
- When you are done, select *Create the deployment group*.

#### Cloud Config
- Create a private S3 bucket (make sure no public access is available)
- Upload a zip of the appsettings you need named `appsettings.zip`
- Edit the source stage of the pipeline you created above
- Click *add action*
- Name the action *Config*
- For action provider, select *Amazon S3*
- For bucket, put the name of the bucket you created, and under S3 object key put `appsettings.zip`
- Select *Done*
- The build scripts in the repo already are setup to handle the cloud config, so no additional setup is required

### .NET Settings
- appsettings.json
```json
{
  "Jwt": {
    "Key": "...",
    "Issuer": "https://api.joinreach.org",
    "Audience": "https://api.joinreach.org",
    "ExpireTime": 30
  },
  "Logging": {
    "LogLevel": {
      "Default": "Warning"
    }
  },
  "AWS": {
    "Buckets": {
      "GraphSnapshot": "hourglass-graph-snapshots",
      "StoryImageBlock": "hourglass-image-block-images (or whatever name you used)"
    },
    "Region": "us-east-2",
    "AccessKey": "enter-access-key-here",
    "AccessSecret": "enter-access-secret-here"
  },
  "Smtp": {
    "Host": "email-smtp.us-west-2.amazonaws.com",
    "Username": "enter-username-here",
    "Password": "enter-password-here"
  },
  "AllowedHosts": "*"
}
```
- appsettings.production.json
```json
{
  "Logging": {
    "LogLevel": {
      "Default": "Debug",
      "System": "Information",
      "Microsoft": "Information"
    }
  },
  "ConnectionStrings": {
    "HourglassDatabase": "Server=enter-postgressql-server-here;port=5432;Database=postgres;User Id=enter-user-id-here;Password=enter-password-here;"
  }
}
```

### EC2 IAM
- The following two policies combine to make the permissions for EC2CodeDeploy
- AmazonEC2RoleForAWSCodeDeploy
```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Action": [
                "s3:GetObject",
                "s3:GetObjectVersion",
                "s3:ListBucket"
            ],
            "Effect": "Allow",
            "Resource": "*"
        }
    ]
}
```
- CodeDeployEC2Permissions
```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "s3:Get*",
                "s3:List*"
            ],
            "Resource": [
                "arn:aws:s3:::your-codepipleine-arn/*",
                "arn:aws:s3:::aws-codedeploy-us-east-2/*"
            ]
        }
    ]
}
```

### TLS/SSL Setup
- Since the frontend is HTTPS, we will also want the backend to be secure to avoid mixed content issues.
- To do this, you must first obtain an SSL certificate. You may do this through https://letsencrypt.org/ if you want a free provider, or use your web hosting provider. 
- After obtaining the certifacte, SSH into the EC2 instance and install it on the machine.
- Make sure to edit the server config files scripts/server_production.conf with the location of the SSL certificate file.


### Simple Email Service
The backend uses AWS Simple Email Service (SES) to send mail. 
- To create credentials, visit SES and go to Email Sending->SMTP Settings->Create My SMTP Credentials and follow the steps given on the creation page. Insert those credentials and the Server Name on the SMTP Settings website into the appsettings.json as follows.
```json
"Smtp": {
    "Host": "email-smtp.us-west-2.amazonaws.com",
    "Username": "enter-username-here",
    "Password": "enter-password-here"
  },
```
- To be able to send email *to* any address, visit Email Sending->Sending Statistics and follow the AWS guide to leaving the SES Sandbox.
- To be able to send *from* an address, visit Identity Management->Email Addresses, click Verify a New Email Address and follow the steps for your desired sending address.
  - Alternatively, visit Identity Management->Domains and Verify a New Domain to allow any address on that to send mail.

---
## Frontend Setup
Our frontend is hosted on AWS Amplify, where we have a development environment, running off of the code in our Master branch and is used for internal testing. We also have a production environment, running off the code in our Production branch, used for external release.
### Setup
- Navigate to AWS amplify console 
- Choose GitHub as the code source
- Select the hourglass-fe repo
- Select master as the branch to be tracked
- Enter an app name (this will be the name the application is saved under in AWS)
- Under build and test settings paste the following:
```
version: 0.1
frontend:
  phases:
    preBuild:
      commands:
        - npm install
    build:
      commands:
        - echo Building...
        - npm run build
    postBuild:
      commands:
        - echo Running unit tests...
        - CI=true npm run test
        - echo Tests complete!
            
  artifacts:
    baseDirectory: build
    files:
      - '**/*'
  cache:
    paths:
      - node_modules/**/*
```
- Review settings on top page 
- Under environment variables enter the proper value for your REACT_APP_TOKEN, REACT_APP_API_URL, REACT_APP_TOKEN
- Click save and deploy
  - This will be your staging deployment
- Click connect branch
- Select production 
- Save and deploy
  - This will be your production branch
- Under App Settings, click on domain management
- Set the domain to the proper name so you don’t have to use the autogenerated AWS url

---
## Database Setup

---
## Other Setup

### S3 Image Support
- Create a bucket in AWS
- When creating the bucket, make sure the bucket is private but has public object access. 
```
Block public access to buckets and objects granted through new access control lists (ACLs)
  Off
Block public access to buckets and objects granted through any access control lists (ACLs)
  Off
Block public access to buckets and objects granted through new public bucket or access point policies
  On
Block public and cross-account access to buckets and objects through any public bucket or access point policies
  On
```
- Create a backend AWS user and grant the following policy when creating the bucket
```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Principal": {
                "AWS": "arn:aws:iam::the-user-arn-you-created"
            },
            "Action": "s3:*",
            "Resource": [
                "arn:aws:s3:::hourglass-graph-snapshots",
                "arn:aws:s3:::hourglass-graph-snapshots/*"
            ]
        }
    ]
}
```
- Add the bucket name you created to appsettings.json under Buckets. For example, if you are adding Profile image support, add "ProfilePicture": "hourglass-profile-pictures" where “hourglass-profile-pictures” is the name of the bucket you created

### Elasticsearch Index and Syncing Lambda Setup
- Set up a domain for your Elasticsearch Service on AWS. Grant the following access policy:
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": {
        "AWS": "*"
      },
      "Action": "es:*",
      "Resource": "your-aws-resource-here/*"
    }
  ]
}
```

There is also a script that syncs the Elasticsearch Indices with the database.
- Set up an execution role with the following policy:
```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": "logs:CreateLogGroup",
            "Resource": "your-resource:*"
        },
        {
            "Effect": "Allow",
            "Action": [
                "logs:CreateLogStream",
                "logs:PutLogEvents"
            ],
            "Resource": [
                "your-resource:your-role-name:*"
            ]
        }
    ]
}
```
- Deploy the Lambda code via the AWS Console.
- Lastly, set up an AWS CloudWatch Events Trigger to schedule the rate at which the search index updates (for example, every day).
