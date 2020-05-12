---
title: Reach
nav_order: 1
---

### About Reach
  Reach is a web based application that allows users to visualize economic data in both graphical and geographical form. The goal of Reach is to empower residents, business owners and politicians from the Central Coast of California to make data-driven decisions by giving them the proper tools to accurately measure the health of their community. 

#### Key Features
  1. Track data trends over time in the Graph Builder
  2. Compare nearby cities and counties in the Map Viewer
  3. Combine maps, graphs and text to form Stories which are exportable to Facebook, Linkedin and Twitter 
  4. Create an account to save Stories for later viewing
  5. Discover Stories that other users have put together through the Explore page
  
### Demo

[![Demo Video](https://res.cloudinary.com/marcomontalbano/image/upload/v1586927119/video_to_markdown/images/youtube--1CZzfJO3TyM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://drive.google.com/file/d/1JzaLhkd2OK4xsbIb5OmDDkNC47wo_G1-/view?usp=sharing "REACH Demo")

### Install
  The application is avaliable by two seperate links. 
  
  The development build will be utilized by developers and internal testers in order to determine stable features to be deployed into alpha. This is an unstable and experimental build, and is available here: [Development](https://master.d1t7lxoixksik3.amplifyapp.com/)
  
  The alpha build which will be avaliable to external testers and the general public is available here: [Alpha](https://production.d1t7lxoixksik3.amplifyapp.com/)

### User Guide

#### 1.0 Introduction
This User Guide will provide information on how to navigate the website.  This section will go into detail on creating an account, logging in, and the three main features of our site: the Explore Page, the VizBuilder page, and the StoryBuilder page.  For more information and guidance on how to use the site, please see the 'Demo' section of the site.

#### 2.0 User Accounts
The Reach site can be used without creating an account; however to save any maps, graphs, or stories a user account must be created to persist that data.

WARNING: Please do not use passwords that you would use on other sites.  We are still working on encryption and the overall security of our site.

##### 2.1 Creating an Account
1. To create an account, click the ‘Login’ button in the upper right hand corner and then navigate to 'Create Account' in the upper right hand corner.  
2. There are three options to create an account: through Facebook, Google, or by creating a Reach account by entering your name, email, and password.  
3. Once your account is created, you will be automatically logged in, which is indicated by the user icon appearing in the upper right hand corner.

##### 2.2 Logging in
1. If you already have an account and would like to log in, click the 'Login' button in the upper right hand corner, which will navigate you to our Login page.
2. Log in using whichever method you chose when creating your account.
3. Once you log in, this will be indicated by the user icon in the upper right hand corner.

##### 2.3 Logging out
1. To log out, click the user icon in the upper right hand corner, which will open up a dropdown menu.
2. Click 'Logout' at the bottom of the dropdown menu.
3. Once you are logged out, this will be indicated by the ‘Login’ button reappearing in the upper right hand corner.

#### 3.0 Explore Page
The Explore page is a way for users to view stories built by others using the StoryBuilder (see section 5.0).  These stories can be shared to social media or saved to your personal device.  The search bar at the top of the page will be used to search for relevant stories.  This page is still under construction and is not yet fully functional.

![](images/ExplorePage.png)

1. Click on 'Explore' on the navigation bar.
2. To view any stories on this page, click on the story card, which will navigate you to a new page with the full story. (not yet fully functional)
3. To share this story, click the 'Share' button, which will provide options to share to Facebook, Twitter, or LinkedIn.


#### 4.0 VizBuilder Page
The VizBuilder Page is a tool that allows users to dig deeper into Central Coast public data. From this page, the user can select to see the data as interactive graphs or as interactive maps or both. Users can specifiy custom filters and then view the resulting data as a series of visualizations based on their selections.

![](images/VizBuilderPage.png)

##### 4.1 Graphs
Once a user accesses the web application, a screen will appear with predefined graphs. A user can work with this graph or click on the upward arrow at the botton of the page to select new graphs from the five different initiatives available. 
The user will be able to see different types of graphs including: 

. a Line graph.

Line graphs are used to track changes over short and long periods of time. When smaller changes exist, line graphs are better to use than bar graphs. Line graphs can also be used to compare changes over the same period of time for more than one group.

. a Pie Chart.

Pie charts are best to use when you are trying to compare parts of a whole. They do not show changes over time.

. a Bar Graph.

Bar graphs are used to compare things between different groups or to track changes over time. However, when trying to measure change over time, bar graphs are best when the changes are larger.

. an Area Graph.

Area graphs are very similar to line graphs. They can be used to track changes over time for one or more groups. Area graphs are good to use when you are tracking the changes in two or more related groups that make up one whole category (for example public and private groups).

.  an X-Y Plot.

X-Y plots are used to determine relationships between the two different things. The x-axis is used to measure one event (or variable) and the y-axis is used to measure the other. If both variables increase at the same time, they have a positive relationship. If one variable decreases while the other increases, they have a negative relationship. Sometimes the variables don't follow any pattern and have no relationship.

A user will be able to delete, save, duplicate, or share a graph on Facebook, Twitter or LinkedIn by clicking on the specific buttons from the menu above the graph.

A user will also be able to print or download a graph as 'PDF', 'PNG', or 'JPEG' files. To do so, the user can click on the 3 lines icon in top right corner of the graph. 

A user can zoom in a graph for better readability; with a mouse pointer, the zooming is performed by dragging out a rectangle in the chart. The user can press the shift key and drag the mouse in order to move inside the zoomed in chart.

##### 4.2 Maps Overview
###### 4.2.0 Adding Layer to Map 
1. Click 'Layers' 
2. Select up to two data topics that you would like to view geographically. Depending on the type of data selected, the map will display pins or a choropleth map. 
3. For a choropleth map, hover the cursor over the map to find the values of a particular area.
4. For a pin, click on a pin to find the values at that point. 

###### 4.2.1 Adjusting Map Bounds (not yet implemented)
Click on 'Region', 'Communities', or 'Zip Code' to adjust the boundaries and data displayed on the map. 

#### 5.0 StoryBuilder Page
The StoryBuilder page is a tool to build a compelling and meaningful story using maps, graphs, images, and text.  This allows you to create a story with the visualizations created using the VizBuilder (section 4.0). These stories can then be saved and shared.

![](images/StoryBuilderPage.png)

##### 5.1 StoryBuilder Overview
1. Click on 'StoryBuilder' in the navigation bar.
2. Fill in the title and description of the story you are trying to tell.
3. From here, you can add maps, graphs, images, or text to your story, using the toolbar on the left. (Only text blocks are implemented so far. Graph blocks are currently under development, and maps and images are coming soon.)
4. All of these components can be reordered by using the drag handles on the left side of each component.
5. To preview what the document will look like, click the 'Preview' button on the toolbar.
6. To save the document when it is finished, click the ‘Save’ button on the toolbar. (not yet fully implemented)

##### 5.2 Adding text to Story
1. Click 'Text' on left-hand side toolbar.
2. Click inside the box to type.
3. To use any of the stylings at the top of the text box, highlight the portion of the text and click on the styling wanted.

### Licensing

#### Terms of Service
[Click here to view the Terms of Service](./TermsOfService.pdf)

#### Privacy Policy
[Click here to view the Privacy Policy](./PrivacyPolicy.pdf)

#### Open Source Licensing

[@babel/code-frame@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-code-frame
) (**MIT**)

[@babel/compat-data@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-compat-data
) (**MIT**)

[@babel/core@7.8.4](https://github.com/babel/babel/tree/master/packages/babel-core
) (**MIT**)

[@babel/generator@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-generator
) (**MIT**)

[@babel/helper-annotate-as-pure@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-annotate-as-pure
) (**MIT**)

[@babel/helper-builder-binary-assignment-operator-visitor@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-builder-binary-assignment-operator-visitor
) (**MIT**)

[@babel/helper-builder-react-jsx@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-builder-react-jsx
) (**MIT**)

[@babel/helper-call-delegate@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-helper-call-delegate
) (**MIT**)

[@babel/helper-compilation-targets@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-helper-compilation-targets
) (**MIT**)

[@babel/helper-create-class-features-plugin@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-helper-create-class-features-plugin
) (**MIT**)

[@babel/helper-create-regexp-features-plugin@7.8.6](https://github.com/babel/babel
) (**MIT**)

[@babel/helper-define-map@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-define-map
) (**MIT**)

[@babel/helper-explode-assignable-expression@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-explode-assignable-expression
) (**MIT**)

[@babel/helper-function-name@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-function-name
) (**MIT**)

[@babel/helper-get-function-arity@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-get-function-arity
) (**MIT**)

[@babel/helper-hoist-variables@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-hoist-variables
) (**MIT**)

[@babel/helper-member-expression-to-functions@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-member-expression-to-functions
) (**MIT**)

[@babel/helper-module-imports@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-module-imports
) (**MIT**)

[@babel/helper-module-transforms@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-helper-module-transforms
) (**MIT**)

[@babel/helper-optimise-call-expression@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-optimise-call-expression
) (**MIT**)

[@babel/helper-plugin-utils@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-plugin-utils
) (**MIT**)

[@babel/helper-regex@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-regex
) (**MIT**)

[@babel/helper-remap-async-to-generator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-remap-async-to-generator
) (**MIT**)

[@babel/helper-replace-supers@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-helper-replace-supers
) (**MIT**)

[@babel/helper-simple-access@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-simple-access
) (**MIT**)

[@babel/helper-split-export-declaration@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-split-export-declaration
) (**MIT**)

[@babel/helper-wrap-function@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-helper-wrap-function
) (**MIT**)

[@babel/helpers@7.8.4](https://github.com/babel/babel/tree/master/packages/babel-helpers
) (**MIT**)

[@babel/highlight@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-highlight
) (**MIT**)

[@babel/parser@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-parser
) (**MIT**)

[@babel/plugin-proposal-async-generator-functions@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-async-generator-functions
) (**MIT**)

[@babel/plugin-proposal-class-properties@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-class-properties
) (**MIT**)

[@babel/plugin-proposal-decorators@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-decorators
) (**MIT**)

[@babel/plugin-proposal-dynamic-import@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-dynamic-import
) (**MIT**)

[@babel/plugin-proposal-json-strings@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-json-strings
) (**MIT**)

[@babel/plugin-proposal-nullish-coalescing-operator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-nullish-coalescing-operator
) (**MIT**)

[@babel/plugin-proposal-numeric-separator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-numeric-separator
) (**MIT**)

[@babel/plugin-proposal-object-rest-spread@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-object-rest-spread
) (**MIT**)

[@babel/plugin-proposal-optional-catch-binding@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-optional-catch-binding
) (**MIT**)

[@babel/plugin-proposal-optional-chaining@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-optional-chaining
) (**MIT**)

[@babel/plugin-proposal-unicode-property-regex@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-proposal-unicode-property-regex
) (**MIT**)

[@babel/plugin-syntax-async-generators@7.8.4](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-async-generators
) (**MIT**)

[@babel/plugin-syntax-decorators@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-decorators
) (**MIT**)

[@babel/plugin-syntax-dynamic-import@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-dynamic-import
) (**MIT**)

[@babel/plugin-syntax-flow@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-flow
) (**MIT**)

[@babel/plugin-syntax-json-strings@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-json-strings
) (**MIT**)

[@babel/plugin-syntax-jsx@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-jsx
) (**MIT**)

[@babel/plugin-syntax-nullish-coalescing-operator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-nullish-coalescing-operator
) (**MIT**)

[@babel/plugin-syntax-numeric-separator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-numeric-separator
) (**MIT**)

[@babel/plugin-syntax-object-rest-spread@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-object-rest-spread
) (**MIT**)

[@babel/plugin-syntax-optional-catch-binding@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-optional-catch-binding
) (**MIT**)

[@babel/plugin-syntax-optional-chaining@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-optional-chaining
) (**MIT**)

[@babel/plugin-syntax-top-level-await@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-top-level-await
) (**MIT**)

[@babel/plugin-syntax-typescript@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-typescript
) (**MIT**)

[@babel/plugin-transform-arrow-functions@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-arrow-functions
) (**MIT**)

[@babel/plugin-transform-async-to-generator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-async-to-generator
) (**MIT**)

[@babel/plugin-transform-block-scoped-functions@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-block-scoped-functions
) (**MIT**)

[@babel/plugin-transform-block-scoping@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-block-scoping
) (**MIT**)

[@babel/plugin-transform-classes@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-classes
) (**MIT**)

[@babel/plugin-transform-computed-properties@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-computed-properties
) (**MIT**)

[@babel/plugin-transform-destructuring@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-destructuring
) (**MIT**)

[@babel/plugin-transform-dotall-regex@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-dotall-regex
) (**MIT**)

[@babel/plugin-transform-duplicate-keys@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-duplicate-keys
) (**MIT**)

[@babel/plugin-transform-exponentiation-operator@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-exponentiation-operator
) (**MIT**)

[@babel/plugin-transform-flow-strip-types@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-flow-strip-types
) (**MIT**)

[@babel/plugin-transform-for-of@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-for-of
) (**MIT**)

[@babel/plugin-transform-function-name@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-function-name
) (**MIT**)

[@babel/plugin-transform-literals@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-literals
) (**MIT**)

[@babel/plugin-transform-member-expression-literals@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-member-expression-literals
) (**MIT**)

[@babel/plugin-transform-modules-amd@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-modules-amd
) (**MIT**)

[@babel/plugin-transform-modules-commonjs@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-modules-commonjs
) (**MIT**)

[@babel/plugin-transform-modules-systemjs@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-modules-systemjs
) (**MIT**)

[@babel/plugin-transform-modules-umd@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-modules-umd
) (**MIT**)

[@babel/plugin-transform-named-capturing-groups-regex@7.8.3](https://github.com/babel/babel
) (**MIT**)

[@babel/plugin-transform-new-target@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-new-target
) (**MIT**)

[@babel/plugin-transform-object-super@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-object-super
) (**MIT**)

[@babel/plugin-transform-parameters@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-parameters
) (**MIT**)

[@babel/plugin-transform-property-literals@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-property-literals
) (**MIT**)

[@babel/plugin-transform-react-constant-elements@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-react-constant-elements
) (**MIT**)

[@babel/plugin-transform-react-display-name@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-react-display-name
) (**MIT**)

[@babel/plugin-transform-react-jsx-self@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-react-jsx-self
) (**MIT**)

[@babel/plugin-transform-react-jsx-source@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-react-jsx-source
) (**MIT**)

[@babel/plugin-transform-react-jsx@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-react-jsx
) (**MIT**)

[@babel/plugin-transform-regenerator@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-regenerator
) (**MIT**)

[@babel/plugin-transform-reserved-words@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-reserved-words
) (**MIT**)

[@babel/plugin-transform-runtime@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-runtime
) (**MIT**)

[@babel/plugin-transform-shorthand-properties@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-shorthand-properties
) (**MIT**)

[@babel/plugin-transform-spread@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-spread
) (**MIT**)

[@babel/plugin-transform-sticky-regex@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-sticky-regex
) (**MIT**)

[@babel/plugin-transform-template-literals@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-template-literals
) (**MIT**)

[@babel/plugin-transform-typeof-symbol@7.8.4](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-typeof-symbol
) (**MIT**)

[@babel/plugin-transform-typescript@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-typescript
) (**MIT**)

[@babel/plugin-transform-unicode-regex@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-unicode-regex
) (**MIT**)

[@babel/preset-env@7.8.4](https://github.com/babel/babel/tree/master/packages/babel-preset-env
) (**MIT**)

[@babel/preset-env@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-preset-env
) (**MIT**)

[@babel/preset-react@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-preset-react
) (**MIT**)

[@babel/preset-typescript@7.8.3](https://github.com/babel/babel/tree/master/packages/babel-preset-typescript
) (**MIT**)

[@babel/runtime-corejs3@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-runtime-corejs3
) (**MIT**)

[@babel/runtime@7.8.4](https://github.com/babel/babel
) (**MIT**)

[@babel/runtime@7.8.7](https://github.com/babel/babel
) (**MIT**)

[@babel/template@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-template
) (**MIT**)

[@babel/traverse@7.8.6](https://github.com/babel/babel/tree/master/packages/babel-traverse
) (**MIT**)

[@babel/types@7.8.7](https://github.com/babel/babel/tree/master/packages/babel-types
) (**MIT**)

[@cnakazawa/watch@1.0.4](https://github.com/mikeal/watch
) (**Apache-2.0**)

[@csstools/convert-colors@1.4.0](https://github.com/jonathantneal/convert-colors
) (**CC0-1.0**)

[@csstools/normalize.css@10.1.0](https://github.com/csstools/normalize.css
) (**CC0-1.0**)

[@date-io/core@1.3.13](https://github.com/dmtrKovalenko/date-io
) (**MIT**)

[@date-io/date-fns@1.3.13](https://github.com/dmtrKovalenko/date-io
) (**MIT**)

[@emotion/hash@0.7.4](https://github.com/emotion-js/emotion/tree/master/packages/hash
) (**MIT**)

[@hapi/address@2.1.4](https://github.com/hapijs/address
) (**BSD-3-Clause**)

[@hapi/bourne@1.3.2](https://github.com/hapijs/bourne
) (**BSD-3-Clause**)

[@hapi/hoek@8.5.1](https://github.com/hapijs/hoek
) (**BSD-3-Clause**)

[@hapi/joi@15.1.1](https://github.com/hapijs/joi
) (**BSD-3-Clause**)

[@hapi/topo@3.1.6](https://github.com/hapijs/topo
) (**BSD-3-Clause**)

[@jest/console@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/core@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/environment@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/fake-timers@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/reporters@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/source-map@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/test-result@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/test-sequencer@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/transform@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/types@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[@jest/types@25.1.0](https://github.com/facebook/jest
) (**MIT**)

[@mapbox/geojson-area@0.2.2](https://github.com/mapbox/geojson-area
) (**BSD-2-Clause**)

[@mapbox/geojson-rewind@0.4.0](https://github.com/mapbox/geojson-rewind
) (**ISC**)

[@mapbox/geojson-types@1.0.2](
) (**ISC**)

[@mapbox/jsonlint-lines-primitives@2.0.2](https://github.com/mapbox/jsonlint
) (**Custom: https://github.com/tmcw/jsonlint**)

[@mapbox/mapbox-gl-supported@1.5.0](https://github.com/mapbox/mapbox-gl-supported
) (**BSD-3-Clause**)

[@mapbox/point-geometry@0.1.0](https://github.com/mapbox/point-geometry
) (**ISC**)

[@mapbox/tiny-sdf@1.1.1](https://github.com/mapbox/tiny-sdf
) (**BSD-2-Clause**)

[@mapbox/unitbezier@0.0.0](https://github.com/mapbox/unitbezier
) (**BSD-2-Clause**)

[@mapbox/vector-tile@1.3.1](https://github.com/mapbox/vector-tile-js
) (**BSD-3-Clause**)

[@mapbox/whoots-js@3.1.0](https://github.com/mapbox/whoots-js
) (**ISC**)

[@material-ui/core@4.9.5](https://github.com/mui-org/material-ui
) (**MIT**)

[@material-ui/icons@4.9.1](https://github.com/mui-org/material-ui
) (**MIT**)

[@material-ui/lab@4.0.0-alpha.45](https://github.com/mui-org/material-ui
) (**MIT**)

[@material-ui/pickers@3.2.10](https://github.com/mui-org/material-ui-pickers
) (**MIT**)

[@material-ui/styles@4.9.0](https://github.com/mui-org/material-ui
) (**MIT**)

[@material-ui/system@4.9.3](https://github.com/mui-org/material-ui
) (**MIT**)

[@material-ui/types@5.0.0](https://github.com/mui-org/material-ui
) (**MIT**)

[@material-ui/utils@4.7.1](https://github.com/mui-org/material-ui
) (**MIT**)

[@math.gl/web-mercator@3.1.3](https://github.com/uber-web/math.gl
) (**MIT**)

[@mrmlnc/readdir-enhanced@2.2.1](https://github.com/bigstickcarpet/readdir-enhanced
) (**MIT**)

[@nodelib/fs.stat@1.1.3](https://github.com/nodelib/nodelib/tree/master/packages/fs/fs.stat
) (**MIT**)

[@sheerun/mutationobserver-shim@0.3.3](github.com/megawac/MutationObserver.js
) (**MIT**)

[@svgr/babel-plugin-add-jsx-attribute@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-add-jsx-attribute
) (**MIT**)

[@svgr/babel-plugin-remove-jsx-attribute@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-remove-jsx-attribute
) (**MIT**)

[@svgr/babel-plugin-remove-jsx-empty-expression@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-remove-jsx-empty-expression
) (**MIT**)

[@svgr/babel-plugin-replace-jsx-attribute-value@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-replace-jsx-attribute-value
) (**MIT**)

[@svgr/babel-plugin-svg-dynamic-title@4.3.3](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-svg-dynamic-title
) (**MIT**)

[@svgr/babel-plugin-svg-em-dimensions@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-svg-em-dimensions
) (**MIT**)

[@svgr/babel-plugin-transform-react-native-svg@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-transform-react-native-svg
) (**MIT**)

[@svgr/babel-plugin-transform-svg-component@4.2.0](https://github.com/smooth-code/svgr/tree/master/packages/babel-plugin-transform-svg-component
) (**MIT**)

[@svgr/babel-preset@4.3.3](https://github.com/smooth-code/svgr/tree/master/packages/babel-preset
) (**MIT**)

[@svgr/core@4.3.3](https://github.com/smooth-code/svgr/tree/master/packages/core
) (**MIT**)

[@svgr/hast-util-to-babel-ast@4.3.2](https://github.com/smooth-code/svgr/tree/master/packages/hast-util-to-babel-ast
) (**MIT**)

[@svgr/plugin-jsx@4.3.3](https://github.com/smooth-code/svgr/tree/master/packages/plugin-jsx
) (**MIT**)

[@svgr/plugin-svgo@4.3.1](https://github.com/smooth-code/svgr/tree/master/packages/plugin-svgo
) (**MIT**)

[@svgr/webpack@4.3.3](https://github.com/smooth-code/svgr/tree/master/packages/webpack
) (**MIT**)

[@testing-library/dom@6.15.0](https://github.com/testing-library/dom-testing-library
) (**MIT**)

[@testing-library/jest-dom@4.2.4](https://github.com/testing-library/jest-dom
) (**MIT**)

[@testing-library/react@9.5.0](https://github.com/testing-library/react-testing-library
) (**MIT**)

[@testing-library/user-event@7.2.1](https://github.com/testing-library/user-event
) (**MIT**)

[@types/babel__core@7.1.6](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/babel__generator@7.6.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/babel__template@7.0.2](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/babel__traverse@7.0.9](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/cheerio@0.22.16](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/chroma-js@2.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/color-name@1.1.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/date-fns@2.6.0](https://github.com/date-fns/date-fns
) (**MIT**)

[@types/domhandler@2.4.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/domutils@1.7.2](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/draft-js@0.10.38](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/draftjs-to-html@0.8.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/enzyme-adapter-react-16@1.0.6](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/enzyme@3.10.5](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/eslint-visitor-keys@1.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/events@3.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/gapi.auth2@0.0.51](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/gapi@0.0.39](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/geojson@7946.0.7](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/gl-matrix@2.4.5](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/glob@7.1.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/history@4.7.5](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/hoist-non-react-statics@3.3.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/htmlparser2@3.10.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/istanbul-lib-coverage@2.0.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/istanbul-lib-report@3.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/istanbul-reports@1.1.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/jest@24.9.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/json-schema@7.0.4](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/lodash@4.14.149](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/mapbox-gl@1.8.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/minimatch@3.0.3](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/node@12.12.29](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/parse-json@4.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/prop-types@15.7.3](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/q@1.5.2](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-dom@16.9.5](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-facebook-login@4.1.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-html-parser@2.0.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-map-gl@5.2.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-redux@7.1.7](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-router-dom@5.1.3](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-router@5.1.4](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-splitter-layout@3.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react-transition-group@4.2.4](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/react@16.9.23](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/stack-utils@1.0.1](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/styled-jsx@2.2.8](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/testing-library__dom@6.14.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/testing-library__react@9.1.3](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/uuid@7.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/viewport-mercator-project@6.1.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/yargs-parser@15.0.0](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/yargs@13.0.8](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@types/yargs@15.0.4](https://github.com/DefinitelyTyped/DefinitelyTyped
) (**MIT**)

[@typescript-eslint/eslint-plugin@2.23.0](https://github.com/typescript-eslint/typescript-eslint
) (**MIT**)

[@typescript-eslint/experimental-utils@2.23.0](https://github.com/typescript-eslint/typescript-eslint
) (**MIT**)

[@typescript-eslint/parser@2.23.0](https://github.com/typescript-eslint/typescript-eslint
) (**BSD-2-Clause**)

[@typescript-eslint/typescript-estree@2.23.0](https://github.com/typescript-eslint/typescript-eslint
) (**BSD-2-Clause**)

[@webassemblyjs/ast@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/floating-point-hex-parser@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/helper-api-error@1.8.5](
) (**MIT**)

[@webassemblyjs/helper-buffer@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/helper-code-frame@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/helper-fsm@1.8.5](
) (**ISC**)

[@webassemblyjs/helper-module-context@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/helper-wasm-bytecode@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/helper-wasm-section@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/ieee754@1.8.5](
) (**MIT**)

[@webassemblyjs/leb128@1.8.5](
) (**MIT**)

[@webassemblyjs/utf8@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/wasm-edit@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/wasm-gen@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/wasm-opt@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/wasm-parser@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/wast-parser@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@webassemblyjs/wast-printer@1.8.5](https://github.com/xtuc/webassemblyjs
) (**MIT**)

[@xtuc/ieee754@1.2.0](https://github.com/feross/ieee754
) (**BSD-3-Clause**)

[@xtuc/long@4.2.2](https://github.com/dcodeIO/long.js
) (**Apache-2.0**)

[abab@2.0.3](https://github.com/jsdom/abab
) (**BSD-3-Clause**)

[abbrev@1.1.1](https://github.com/isaacs/abbrev-js
) (**ISC**)

[accepts@1.3.7](https://github.com/jshttp/accepts
) (**MIT**)

[acorn-globals@4.3.4](https://github.com/ForbesLindesay/acorn-globals
) (**MIT**)

[acorn-jsx@5.2.0](https://github.com/acornjs/acorn-jsx
) (**MIT**)

[acorn-walk@6.2.0](https://github.com/acornjs/acorn
) (**MIT**)

[acorn@5.7.4](https://github.com/acornjs/acorn
) (**MIT**)

[acorn@6.4.1](https://github.com/acornjs/acorn
) (**MIT**)

[acorn@7.1.1](https://github.com/acornjs/acorn
) (**MIT**)

[address@1.1.2](https://github.com/node-modules/address
) (**MIT**)

[adjust-sourcemap-loader@2.0.0](https://github.com/bholloway/adjust-sourcemap-loader
) (**MIT**)

[aggregate-error@3.0.1](https://github.com/sindresorhus/aggregate-error
) (**MIT**)

[airbnb-prop-types@2.15.0](https://github.com/airbnb/prop-types
) (**MIT**)

[ajv-errors@1.0.1](https://github.com/epoberezkin/ajv-errors
) (**MIT**)

[ajv-keywords@3.4.1](https://github.com/epoberezkin/ajv-keywords
) (**MIT**)

[ajv@6.12.0](https://github.com/epoberezkin/ajv
) (**MIT**)

[alphanum-sort@1.0.2](https://github.com/TrySound/alphanum-sort
) (**MIT**)

[amdefine@1.0.1](https://github.com/jrburke/amdefine
) (**BSD-3-Clause OR MIT**)

[ansi-colors@3.2.4](https://github.com/doowb/ansi-colors
) (**MIT**)

[ansi-escapes@3.2.0](https://github.com/sindresorhus/ansi-escapes
) (**MIT**)

[ansi-escapes@4.3.1](https://github.com/sindresorhus/ansi-escapes
) (**MIT**)

[ansi-html@0.0.7](https://github.com/Tjatse/ansi-html
) (**Apache-2.0**)

[ansi-regex@2.1.1](https://github.com/chalk/ansi-regex
) (**MIT**)

[ansi-regex@3.0.0](https://github.com/chalk/ansi-regex
) (**MIT**)

[ansi-regex@4.1.0](https://github.com/chalk/ansi-regex
) (**MIT**)

[ansi-regex@5.0.0](https://github.com/chalk/ansi-regex
) (**MIT**)

[ansi-styles@2.2.1](https://github.com/chalk/ansi-styles
) (**MIT**)

[ansi-styles@3.2.1](https://github.com/chalk/ansi-styles
) (**MIT**)

[ansi-styles@4.2.1](https://github.com/chalk/ansi-styles
) (**MIT**)

[ansicolors@0.2.1](https://github.com/thlorenz/ansicolors
) (**MIT**)

[anymatch@2.0.0](https://github.com/micromatch/anymatch
) (**ISC**)

[anymatch@3.1.1](https://github.com/micromatch/anymatch
) (**ISC**)

[aproba@1.2.0](https://github.com/iarna/aproba
) (**ISC**)

[are-we-there-yet@1.1.5](https://github.com/iarna/are-we-there-yet
) (**ISC**)

[argparse@1.0.10](https://github.com/nodeca/argparse
) (**MIT**)

[aria-query@3.0.0](https://github.com/A11yance/aria-query
) (**Apache-2.0**)

[aria-query@4.0.2](https://github.com/A11yance/aria-query
) (**Apache-2.0**)

[arity-n@1.0.4](https://github.com/stoeffel/arityN
) (**MIT**)

[arr-diff@4.0.0](https://github.com/jonschlinkert/arr-diff
) (**MIT**)

[arr-flatten@1.1.0](https://github.com/jonschlinkert/arr-flatten
) (**MIT**)

[arr-union@3.1.0](https://github.com/jonschlinkert/arr-union
) (**MIT**)

[array-equal@1.0.0](https://github.com/component/array-equal
) (**MIT**)

[array-filter@1.0.0](https://github.com/juliangruber/array-filter
) (**MIT**)

[array-find-index@1.0.2](https://github.com/sindresorhus/array-find-index
) (**MIT**)

[array-flatten@1.1.1](https://github.com/blakeembrey/array-flatten
) (**MIT**)

[array-flatten@2.1.2](https://github.com/blakeembrey/array-flatten
) (**MIT**)

[array-includes@3.1.1](https://github.com/es-shims/array-includes
) (**MIT**)

[array-move@2.2.1](https://github.com/sindresorhus/array-move
) (**MIT**)

[array-union@1.0.2](https://github.com/sindresorhus/array-union
) (**MIT**)

[array-uniq@1.0.3](https://github.com/sindresorhus/array-uniq
) (**MIT**)

[array-unique@0.3.2](https://github.com/jonschlinkert/array-unique
) (**MIT**)

[array.prototype.find@2.1.1](https://github.com/paulmillr/Array.prototype.find
) (**MIT**)

[array.prototype.flat@1.2.3](https://github.com/es-shims/Array.prototype.flat
) (**MIT**)

[arrify@1.0.1](https://github.com/sindresorhus/arrify
) (**MIT**)

[asap@2.0.6](https://github.com/kriskowal/asap
) (**MIT**)

[asn1.js@4.10.1](https://github.com/indutny/asn1.js
) (**MIT**)

[asn1@0.2.4](https://github.com/joyent/node-asn1
) (**MIT**)

[assert-plus@1.0.0](https://github.com/mcavage/node-assert-plus
) (**MIT**)

[assert@1.4.1](https://github.com/defunctzombie/commonjs-assert
) (**MIT**)

[assign-symbols@1.0.0](https://github.com/jonschlinkert/assign-symbols
) (**MIT**)

[ast-types-flow@0.0.7](https://github.com/kyldvs/ast-types-flow
) (**ISC**)

[astral-regex@1.0.0](https://github.com/kevva/astral-regex
) (**MIT**)

[async-each@1.0.3](https://github.com/paulmillr/async-each
) (**MIT**)

[async-foreach@0.1.3](https://github.com/cowboy/javascript-sync-async-foreach
) (**MIT***)

[async-limiter@1.0.1](https://github.com/strml/async-limiter
) (**MIT**)

[async@2.6.3](https://github.com/caolan/async
) (**MIT**)

[asynckit@0.4.0](https://github.com/alexindigo/asynckit
) (**MIT**)

[atob@2.1.2](git://git.coolaj86.com/coolaj86/atob.js
) (**(MIT OR Apache-2.0)**)

[autoprefixer@9.7.4](https://github.com/postcss/autoprefixer
) (**MIT**)

[aws-sign2@0.7.0](https://github.com/mikeal/aws-sign
) (**Apache-2.0**)

[aws4@1.9.1](https://github.com/mhart/aws4
) (**MIT**)

[axobject-query@2.1.2](https://github.com/A11yance/axobject-query
) (**Apache-2.0**)

[babel-code-frame@6.26.0](https://github.com/babel/babel/tree/master/packages/babel-code-frame
) (**MIT**)

[babel-eslint@10.0.3](https://github.com/babel/babel-eslint
) (**MIT**)

[babel-extract-comments@1.0.0](https://github.com/jonschlinkert/babel-extract-comments
) (**MIT**)

[babel-jest@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[babel-loader@8.0.6](https://github.com/babel/babel-loader
) (**MIT**)

[babel-plugin-dynamic-import-node@2.3.0](https://github.com/airbnb/babel-plugin-dynamic-import-node
) (**MIT**)

[babel-plugin-istanbul@5.2.0](https://github.com/istanbuljs/babel-plugin-istanbul
) (**BSD-3-Clause**)

[babel-plugin-jest-hoist@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[babel-plugin-macros@2.8.0](https://github.com/kentcdodds/babel-plugin-macros
) (**MIT**)

[babel-plugin-named-asset-import@0.3.6](https://github.com/facebook/create-react-app
) (**MIT**)

[babel-plugin-syntax-object-rest-spread@6.13.0](https://github.com/babel/babel/tree/master/packages/babel-plugin-syntax-object-rest-spread
) (**MIT**)

[babel-plugin-transform-object-rest-spread@6.26.0](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-object-rest-spread
) (**MIT**)

[babel-plugin-transform-react-remove-prop-types@0.4.24](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types
) (**MIT**)

[babel-preset-jest@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[babel-preset-react-app@9.1.1](https://github.com/facebook/create-react-app
) (**MIT**)

[babel-runtime@6.26.0](https://github.com/babel/babel/tree/master/packages/babel-runtime
) (**MIT**)

[babylon@6.18.0](https://github.com/babel/babylon
) (**MIT**)

[balanced-match@1.0.0](https://github.com/juliangruber/balanced-match
) (**MIT**)

[base64-js@1.3.1](https://github.com/beatgammit/base64-js
) (**MIT**)

[base@0.11.2](https://github.com/node-base/base
) (**MIT**)

[batch@0.6.1](https://github.com/visionmedia/batch
) (**MIT**)

[bcrypt-pbkdf@1.0.2](https://github.com/joyent/node-bcrypt-pbkdf
) (**BSD-3-Clause**)

[big.js@5.2.2](https://github.com/MikeMcl/big.js
) (**MIT**)

[binary-extensions@1.13.1](https://github.com/sindresorhus/binary-extensions
) (**MIT**)

[binary-extensions@2.0.0](https://github.com/sindresorhus/binary-extensions
) (**MIT**)

[bindings@1.5.0](https://github.com/TooTallNate/node-bindings
) (**MIT**)

[block-stream@0.0.9](https://github.com/isaacs/block-stream
) (**ISC**)

[bluebird@3.7.2](https://github.com/petkaantonov/bluebird
) (**MIT**)

[bn.js@4.11.8](https://github.com/indutny/bn.js
) (**MIT**)

[body-parser@1.19.0](https://github.com/expressjs/body-parser
) (**MIT**)

[bonjour@3.5.0](https://github.com/watson/bonjour
) (**MIT**)

[boolbase@1.0.0](https://github.com/fb55/boolbase
) (**ISC**)

[brace-expansion@1.1.11](https://github.com/juliangruber/brace-expansion
) (**MIT**)

[braces@2.3.2](https://github.com/micromatch/braces
) (**MIT**)

[braces@3.0.2](https://github.com/micromatch/braces
) (**MIT**)

[brorand@1.1.0](https://github.com/indutny/brorand
) (**MIT**)

[browser-process-hrtime@1.0.0](https://github.com/kumavis/browser-process-hrtime
) (**BSD-2-Clause**)

[browser-resolve@1.11.3](https://github.com/shtylman/node-browser-resolve
) (**MIT**)

[browserify-aes@1.2.0](https://github.com/crypto-browserify/browserify-aes
) (**MIT**)

[browserify-cipher@1.0.1](https://github.com/crypto-browserify/browserify-cipher
) (**MIT**)

[browserify-des@1.0.2](https://github.com/crypto-browserify/browserify-des
) (**MIT**)

[browserify-rsa@4.0.1](https://github.com/crypto-browserify/browserify-rsa
) (**MIT**)

[browserify-sign@4.0.4](https://github.com/crypto-browserify/browserify-sign
) (**ISC**)

[browserify-zlib@0.2.0](https://github.com/devongovett/browserify-zlib
) (**MIT**)

[browserslist@4.8.6](https://github.com/browserslist/browserslist
) (**MIT**)

[browserslist@4.9.1](https://github.com/browserslist/browserslist
) (**MIT**)

[bser@2.1.1](https://github.com/facebook/watchman
) (**Apache-2.0**)

[buffer-from@1.1.1](https://github.com/LinusU/buffer-from
) (**MIT**)

[buffer-indexof@1.1.1](https://github.com/soldair/node-buffer-indexof
) (**MIT**)

[buffer-xor@1.0.3](https://github.com/crypto-browserify/buffer-xor
) (**MIT**)

[buffer@4.9.2](https://github.com/feross/buffer
) (**MIT**)

[builtin-status-codes@3.0.0](https://github.com/bendrucker/builtin-status-codes
) (**MIT**)

[bytes@3.0.0](https://github.com/visionmedia/bytes.js
) (**MIT**)

[bytes@3.1.0](https://github.com/visionmedia/bytes.js
) (**MIT**)

[cacache@12.0.3](https://github.com/npm/cacache
) (**ISC**)

[cacache@13.0.1](https://github.com/npm/cacache
) (**ISC**)

[cache-base@1.0.1](https://github.com/jonschlinkert/cache-base
) (**MIT**)

[call-me-maybe@1.0.1](https://github.com/limulus/call-me-maybe
) (**MIT**)

[caller-callsite@2.0.0](https://github.com/sindresorhus/caller-callsite
) (**MIT**)

[caller-path@2.0.0](https://github.com/sindresorhus/caller-path
) (**MIT**)

[callsites@2.0.0](https://github.com/sindresorhus/callsites
) (**MIT**)

[callsites@3.1.0](https://github.com/sindresorhus/callsites
) (**MIT**)

[camel-case@4.1.1](https://github.com/blakeembrey/change-case
) (**MIT**)

[camelcase-keys@2.1.0](https://github.com/sindresorhus/camelcase-keys
) (**MIT**)

[camelcase@2.1.1](https://github.com/sindresorhus/camelcase
) (**MIT**)

[camelcase@3.0.0](https://github.com/sindresorhus/camelcase
) (**MIT**)

[camelcase@5.0.0](https://github.com/sindresorhus/camelcase
) (**MIT**)

[camelcase@5.3.1](https://github.com/sindresorhus/camelcase
) (**MIT**)

[caniuse-api@3.0.0](https://github.com/nyalab/caniuse-api
) (**MIT**)

[caniuse-lite@1.0.30001033](https://github.com/ben-eb/caniuse-lite
) (**CC-BY-4.0**)

[capture-exit@2.0.0](https://github.com/stefanpenner/capture-exit
) (**ISC**)

[cardinal@0.4.4](https://github.com/thlorenz/cardinal
) (**MIT**)

[case-sensitive-paths-webpack-plugin@2.3.0](https://github.com/Urthen/case-sensitive-paths-webpack-plugin
) (**MIT**)

[caseless@0.12.0](https://github.com/mikeal/caseless
) (**Apache-2.0**)

[chalk@1.1.3](https://github.com/chalk/chalk
) (**MIT**)

[chalk@2.4.2](https://github.com/chalk/chalk
) (**MIT**)

[chalk@3.0.0](https://github.com/chalk/chalk
) (**MIT**)

[chardet@0.7.0](https://github.com/runk/node-chardet
) (**MIT**)

[cheerio@1.0.0-rc.3](https://github.com/cheeriojs/cheerio
) (**MIT**)

[chokidar@2.1.8](https://github.com/paulmillr/chokidar
) (**MIT**)

[chokidar@3.3.1](https://github.com/paulmillr/chokidar
) (**MIT**)

[chownr@1.1.3](https://github.com/isaacs/chownr
) (**ISC**)

[chownr@1.1.4](https://github.com/isaacs/chownr
) (**ISC**)

[chroma-js@2.1.0](https://github.com/gka/chroma.js
) (**(BSD-3-Clause AND Apache-2.0)**)

[chrome-trace-event@1.0.2](github.com:samccone/chrome-trace-event
) (**MIT**)

[ci-info@2.0.0](https://github.com/watson/ci-info
) (**MIT**)

[cipher-base@1.0.4](https://github.com/crypto-browserify/cipher-base
) (**MIT**)

[class-utils@0.3.6](https://github.com/jonschlinkert/class-utils
) (**MIT**)

[classnames@2.2.6](https://github.com/JedWatson/classnames
) (**MIT**)

[clean-css@4.2.3](https://github.com/jakubpawlowicz/clean-css
) (**MIT**)

[clean-stack@2.2.0](https://github.com/sindresorhus/clean-stack
) (**MIT**)

[cli-cursor@3.1.0](https://github.com/sindresorhus/cli-cursor
) (**MIT**)

[cli-width@2.2.0](https://github.com/knownasilya/cli-width
) (**ISC**)

[cliui@3.2.0](https://github.com/yargs/cliui
) (**ISC**)

[cliui@4.1.0](https://github.com/yargs/cliui
) (**ISC**)

[cliui@5.0.0](https://github.com/yargs/cliui
) (**ISC**)

[clone-deep@0.2.4](https://github.com/jonschlinkert/clone-deep
) (**MIT**)

[clone-deep@4.0.1](https://github.com/jonschlinkert/clone-deep
) (**MIT**)

[clsx@1.1.0](https://github.com/lukeed/clsx
) (**MIT**)

[co@4.6.0](https://github.com/tj/co
) (**MIT**)

[coa@2.0.2](https://github.com/veged/coa
) (**MIT**)

[code-point-at@1.1.0](https://github.com/sindresorhus/code-point-at
) (**MIT**)

[coffee-script@1.12.7](https://github.com/jashkenas/coffeescript
) (**MIT**)

[collection-visit@1.0.0](https://github.com/jonschlinkert/collection-visit
) (**MIT**)

[color-convert@1.9.3](https://github.com/Qix-/color-convert
) (**MIT**)

[color-convert@2.0.1](https://github.com/Qix-/color-convert
) (**MIT**)

[color-name@1.1.3](https://github.com/dfcreative/color-name
) (**MIT**)

[color-name@1.1.4](https://github.com/colorjs/color-name
) (**MIT**)

[color-string@1.5.3](https://github.com/Qix-/color-string
) (**MIT**)

[color@3.1.2](https://github.com/Qix-/color
) (**MIT**)

[combined-stream@1.0.8](https://github.com/felixge/node-combined-stream
) (**MIT**)

[commander@2.20.3](https://github.com/tj/commander.js
) (**MIT**)

[commander@4.1.1](https://github.com/tj/commander.js
) (**MIT**)

[common-tags@1.8.0](https://github.com/declandewet/common-tags
) (**MIT**)

[commondir@1.0.1](https://github.com/substack/node-commondir
) (**MIT**)

[component-emitter@1.3.0](https://github.com/component/emitter
) (**MIT**)

[compose-function@3.0.3](https://github.com/stoeffel/compose-function
) (**MIT**)

[compressible@2.0.18](https://github.com/jshttp/compressible
) (**MIT**)

[compression@1.7.4](https://github.com/expressjs/compression
) (**MIT**)

[concat-map@0.0.1](https://github.com/substack/node-concat-map
) (**MIT**)

[concat-stream@1.6.2](https://github.com/maxogden/concat-stream
) (**MIT**)

[confusing-browser-globals@1.0.9](https://github.com/facebook/create-react-app
) (**MIT**)

[connect-history-api-fallback@1.6.0](https://github.com/bripkens/connect-history-api-fallback
) (**MIT**)

[connected-react-router@6.7.0](https://github.com/supasate/connected-react-router
) (**MIT**)

[console-browserify@1.2.0](https://github.com/browserify/console-browserify
) (**MIT**)

[console-control-strings@1.1.0](https://github.com/iarna/console-control-strings
) (**ISC**)

[constants-browserify@1.0.0](https://github.com/juliangruber/constants-browserify
) (**MIT**)

[contains-path@0.1.0](https://github.com/jonschlinkert/contains-path
) (**MIT**)

[content-disposition@0.5.3](https://github.com/jshttp/content-disposition
) (**MIT**)

[content-type@1.0.4](https://github.com/jshttp/content-type
) (**MIT**)

[convert-source-map@0.3.5](https://github.com/thlorenz/convert-source-map
) (**MIT**)

[convert-source-map@1.7.0](https://github.com/thlorenz/convert-source-map
) (**MIT**)

[cookie-signature@1.0.6](https://github.com/visionmedia/node-cookie-signature
) (**MIT**)

[cookie@0.4.0](https://github.com/jshttp/cookie
) (**MIT**)

[copy-concurrently@1.0.5](https://github.com/npm/copy-concurrently
) (**ISC**)

[copy-descriptor@0.1.1](https://github.com/jonschlinkert/copy-descriptor
) (**MIT**)

[core-js-compat@3.6.4](https://github.com/zloirock/core-js
) (**MIT**)

[core-js-pure@3.6.4](https://github.com/zloirock/core-js
) (**MIT**)

[core-js@2.6.11](https://github.com/zloirock/core-js
) (**MIT**)

[core-js@3.6.4](https://github.com/zloirock/core-js
) (**MIT**)

[core-util-is@1.0.2](https://github.com/isaacs/core-util-is
) (**MIT**)

[cosmiconfig@5.2.1](https://github.com/davidtheclark/cosmiconfig
) (**MIT**)

[cosmiconfig@6.0.0](https://github.com/davidtheclark/cosmiconfig
) (**MIT**)

[create-ecdh@4.0.3](https://github.com/crypto-browserify/createECDH
) (**MIT**)

[create-hash@1.2.0](https://github.com/crypto-browserify/createHash
) (**MIT**)

[create-hmac@1.1.7](https://github.com/crypto-browserify/createHmac
) (**MIT**)

[cross-env@6.0.3](https://github.com/kentcdodds/cross-env
) (**MIT**)

[cross-spawn@3.0.1](https://github.com/IndigoUnited/node-cross-spawn
) (**MIT**)

[cross-spawn@6.0.5](https://github.com/moxystudio/node-cross-spawn
) (**MIT**)

[cross-spawn@7.0.1](https://github.com/moxystudio/node-cross-spawn
) (**MIT**)

[crypto-browserify@3.12.0](https://github.com/crypto-browserify/crypto-browserify
) (**MIT**)

[css-blank-pseudo@0.1.4](https://github.com/csstools/css-blank-pseudo
) (**CC0-1.0**)

[css-color-names@0.0.4](https://github.com/bahamas10/css-color-names
) (**MIT**)

[css-declaration-sorter@4.0.1](https://github.com/Siilwyn/css-declaration-sorter
) (**MIT**)

[css-has-pseudo@0.10.0](https://github.com/csstools/css-has-pseudo
) (**CC0-1.0**)

[css-loader@3.4.2](https://github.com/webpack-contrib/css-loader
) (**MIT**)

[css-prefers-color-scheme@3.1.1](https://github.com/csstools/css-prefers-color-scheme
) (**CC0-1.0**)

[css-select-base-adapter@0.1.1](https://github.com/nrkn/css-select-base-adapter
) (**MIT**)

[css-select@1.2.0](https://github.com/fb55/css-select
) (**BSD***)

[css-select@2.1.0](https://github.com/fb55/css-select
) (**BSD-2-Clause**)

[css-tree@1.0.0-alpha.37](https://github.com/csstree/csstree
) (**MIT**)

[css-vendor@2.0.7](https://github.com/cssinjs/css-vendor
) (**MIT**)

[css-what@2.1.3](https://github.com/fb55/css-what
) (**BSD-2-Clause**)

[css-what@3.2.1](https://github.com/fb55/css-what
) (**BSD-2-Clause**)

[css.escape@1.5.1](https://github.com/mathiasbynens/CSS.escape
) (**MIT**)

[css@2.2.4](https://github.com/reworkcss/css
) (**MIT**)

[csscolorparser@1.0.3](https://github.com/deanm/css-color-parser-js
) (**MIT**)

[cssdb@4.4.0](https://github.com/csstools/cssdb
) (**CC0-1.0**)

[cssesc@2.0.0](https://github.com/mathiasbynens/cssesc
) (**MIT**)

[cssesc@3.0.0](https://github.com/mathiasbynens/cssesc
) (**MIT**)

[cssnano-preset-default@4.0.7](https://github.com/cssnano/cssnano
) (**MIT**)

[cssnano-util-get-arguments@4.0.0](https://github.com/cssnano/cssnano
) (**MIT**)

[cssnano-util-get-match@4.0.0](https://github.com/cssnano/cssnano
) (**MIT**)

[cssnano-util-raw-cache@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[cssnano-util-same-parent@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[cssnano@4.1.10](https://github.com/cssnano/cssnano
) (**MIT**)

[csso@4.0.2](https://github.com/css/csso
) (**MIT**)

[cssom@0.3.8](https://github.com/NV/CSSOM
) (**MIT**)

[cssstyle@1.4.0](https://github.com/jsakas/CSSStyleDeclaration
) (**MIT**)

[csstype@2.6.9](https://github.com/frenic/csstype
) (**MIT**)

[currently-unhandled@0.4.1](https://github.com/jamestalmage/currently-unhandled
) (**MIT**)

[cyclist@1.0.1](https://github.com/mafintosh/cyclist
) (**MIT**)

[d@1.0.1](https://github.com/medikoo/d
) (**ISC**)

[damerau-levenshtein@1.0.6](https://github.com/tad-lispy/node-damerau-levenshtein
) (**BSD-2-Clause**)

[dashdash@1.14.1](https://github.com/trentm/node-dashdash
) (**MIT**)

[data-urls@1.1.0](https://github.com/jsdom/data-urls
) (**MIT**)

[date-fns@2.10.0](https://github.com/date-fns/date-fns
) (**MIT**)

[debug@2.6.9](https://github.com/visionmedia/debug
) (**MIT**)

[debug@3.2.6](https://github.com/visionmedia/debug
) (**MIT**)

[debug@4.1.1](https://github.com/visionmedia/debug
) (**MIT**)

[decamelize@1.2.0](https://github.com/sindresorhus/decamelize
) (**MIT**)

[decode-uri-component@0.2.0](https://github.com/SamVerschueren/decode-uri-component
) (**MIT**)

[deep-equal@1.1.1](https://github.com/substack/node-deep-equal
) (**MIT**)

[deep-extend@0.6.0](https://github.com/unclechu/node-deep-extend
) (**MIT**)

[deep-is@0.1.3](https://github.com/thlorenz/deep-is
) (**MIT**)

[default-gateway@4.2.0](https://github.com/silverwind/default-gateway
) (**BSD-2-Clause**)

[define-properties@1.1.3](https://github.com/ljharb/define-properties
) (**MIT**)

[define-property@0.2.5](https://github.com/jonschlinkert/define-property
) (**MIT**)

[define-property@1.0.0](https://github.com/jonschlinkert/define-property
) (**MIT**)

[define-property@2.0.2](https://github.com/jonschlinkert/define-property
) (**MIT**)

[del@4.1.1](https://github.com/sindresorhus/del
) (**MIT**)

[delayed-stream@1.0.0](https://github.com/felixge/node-delayed-stream
) (**MIT**)

[delegates@1.0.0](https://github.com/visionmedia/node-delegates
) (**MIT**)

[depd@1.1.2](https://github.com/dougwilson/nodejs-depd
) (**MIT**)

[des.js@1.0.1](https://github.com/indutny/des.js
) (**MIT**)

[destroy@1.0.4](https://github.com/stream-utils/destroy
) (**MIT**)

[detect-libc@1.0.3](https://github.com/lovell/detect-libc
) (**Apache-2.0**)

[detect-newline@2.1.0](https://github.com/sindresorhus/detect-newline
) (**MIT**)

[detect-node@2.0.4](https://github.com/iliakan/detect-node
) (**ISC**)

[detect-port-alt@1.1.6](https://github.com/node-modules/detect-port
) (**MIT**)

[diff-sequences@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[diffie-hellman@5.0.3](https://github.com/crypto-browserify/diffie-hellman
) (**MIT**)

[dir-glob@2.0.0](https://github.com/kevva/dir-glob
) (**MIT**)

[discontinuous-range@1.0.0](https://github.com/dtudury/discontinuous-range
) (**MIT**)

[dns-equal@1.0.0](https://github.com/watson/dns-equal
) (**MIT**)

[dns-packet@1.3.1](https://github.com/mafintosh/dns-packet
) (**MIT**)

[dns-txt@2.0.2](https://github.com/watson/dns-txt
) (**MIT**)

[doctrine@1.5.0](https://github.com/eslint/doctrine
) (**BSD**)

[doctrine@2.1.0](https://github.com/eslint/doctrine
) (**Apache-2.0**)

[doctrine@3.0.0](https://github.com/eslint/doctrine
) (**Apache-2.0**)

[dom-accessibility-api@0.3.0](https://github.com/eps1lon/dom-accessibility-api
) (**MIT**)

[dom-converter@0.2.0](https://github.com/AriaMinaei/dom-converter
) (**MIT**)

[dom-helpers@5.1.3](https://github.com/jquense/dom-helpers
) (**MIT**)

[dom-serializer@0.1.1](https://github.com/cheeriojs/dom-renderer
) (**MIT**)

[domain-browser@1.2.0](https://github.com/bevry/domain-browser
) (**MIT**)

[domelementtype@1.3.1](https://github.com/fb55/domelementtype
) (**BSD-2-Clause**)

[domexception@1.0.1](https://github.com/jsdom/domexception
) (**MIT**)

[domhandler@2.4.2](https://github.com/fb55/DomHandler
) (**BSD-2-Clause**)

[domutils@1.5.1](https://github.com/FB55/domutils
) (**BSD***)

[domutils@1.7.0](https://github.com/FB55/domutils
) (**BSD-2-Clause**)

[dot-case@3.0.3](https://github.com/blakeembrey/change-case
) (**MIT**)

[dot-prop@5.2.0](https://github.com/sindresorhus/dot-prop
) (**MIT**)

[dotenv-expand@5.1.0](
) (**BSD-2-Clause**)

[dotenv@8.2.0](https://github.com/motdotla/dotenv
) (**BSD-2-Clause**)

[draft-js-plugins-editor@3.0.0](https://github.com/draft-js-plugins/draft-js-plugins
) (**MIT**)

[draft-js@0.11.4](https://github.com/facebook/draft-js
) (**MIT**)

[draftjs-to-html@0.9.1](https://github.com/jpuri/draftjs-to-html
) (**MIT**)

[duplexer@0.1.1](https://github.com/Raynos/duplexer
) (**MIT**)

[duplexify@3.7.1](https://github.com/mafintosh/duplexify
) (**MIT**)

[earcut@2.2.2](https://github.com/mapbox/earcut
) (**ISC**)

[ecc-jsbn@0.1.2](https://github.com/quartzjer/ecc-jsbn
) (**MIT**)

[ee-first@1.1.1](https://github.com/jonathanong/ee-first
) (**MIT**)

[electron-to-chromium@1.3.375](https://github.com/kilian/electron-to-chromium
) (**ISC**)

[elliptic@6.5.2](https://github.com/indutny/elliptic
) (**MIT**)

[emoji-regex@7.0.3](https://github.com/mathiasbynens/emoji-regex
) (**MIT**)

[emoji-regex@8.0.0](https://github.com/mathiasbynens/emoji-regex
) (**MIT**)

[emojis-list@2.1.0](https://github.com/kikobeats/emojis-list
) (**MIT**)

[emojis-list@3.0.0](https://github.com/kikobeats/emojis-list
) (**MIT**)

[encodeurl@1.0.2](https://github.com/pillarjs/encodeurl
) (**MIT**)

[encoding@0.1.12](https://github.com/andris9/encoding
) (**MIT**)

[end-of-stream@1.4.4](https://github.com/mafintosh/end-of-stream
) (**MIT**)

[enhanced-resolve@4.1.1](https://github.com/webpack/enhanced-resolve
) (**MIT**)

[entities@1.1.2](https://github.com/fb55/entities
) (**BSD-2-Clause**)

[enzyme-adapter-react-16@1.15.2](https://github.com/airbnb/enzyme
) (**MIT**)

[enzyme-adapter-utils@1.13.0](https://github.com/airbnb/enzyme
) (**MIT**)

[enzyme-shallow-equal@1.0.1](https://github.com/airbnb/enzyme
) (**MIT**)

[enzyme@3.11.0](https://github.com/airbnb/enzyme
) (**MIT**)

[errno@0.1.7](https://github.com/rvagg/node-errno
) (**MIT**)

[error-ex@1.3.2](https://github.com/qix-/node-error-ex
) (**MIT**)

[es-abstract@1.17.4](https://github.com/ljharb/es-abstract
) (**MIT**)

[es-to-primitive@1.2.1](https://github.com/ljharb/es-to-primitive
) (**MIT**)

[es5-ext@0.10.53](https://github.com/medikoo/es5-ext
) (**ISC**)

[es6-iterator@2.0.3](https://github.com/medikoo/es6-iterator
) (**MIT**)

[es6-symbol@3.1.3](https://github.com/medikoo/es6-symbol
) (**ISC**)

[escape-html@1.0.3](https://github.com/component/escape-html
) (**MIT**)

[escape-string-regexp@1.0.5](https://github.com/sindresorhus/escape-string-regexp
) (**MIT**)

[escape-string-regexp@2.0.0](https://github.com/sindresorhus/escape-string-regexp
) (**MIT**)

[escodegen@1.14.1](https://github.com/estools/escodegen
) (**BSD-2-Clause**)

[eslint-config-prettier@6.10.0](https://github.com/prettier/eslint-config-prettier
) (**MIT**)

[eslint-config-react-app@5.2.0](https://github.com/facebook/create-react-app
) (**MIT**)

[eslint-config-react@1.1.7](https://github.com/patrio/eslint-config-react
) (**MIT**)

[eslint-import-resolver-node@0.3.3](https://github.com/benmosher/eslint-plugin-import
) (**MIT**)

[eslint-loader@3.0.3](https://github.com/webpack-contrib/eslint-loader
) (**MIT**)

[eslint-module-utils@2.5.2](https://github.com/benmosher/eslint-plugin-import
) (**MIT**)

[eslint-plugin-flowtype@4.6.0](https://github.com/gajus/eslint-plugin-flowtype
) (**BSD-3-Clause**)

[eslint-plugin-import@2.20.0](https://github.com/benmosher/eslint-plugin-import
) (**MIT**)

[eslint-plugin-jsx-a11y@6.2.3](https://github.com/evcohen/eslint-plugin-jsx-a11y
) (**MIT**)

[eslint-plugin-prettier@3.1.2](https://github.com/prettier/eslint-plugin-prettier
) (**MIT**)

[eslint-plugin-react-hooks@1.7.0](https://github.com/facebook/react
) (**MIT**)

[eslint-plugin-react@7.18.0](https://github.com/yannickcr/eslint-plugin-react
) (**MIT**)

[eslint-plugin-react@7.19.0](https://github.com/yannickcr/eslint-plugin-react
) (**MIT**)

[eslint-scope@4.0.3](https://github.com/eslint/eslint-scope
) (**BSD-2-Clause**)

[eslint-scope@5.0.0](https://github.com/eslint/eslint-scope
) (**BSD-2-Clause**)

[eslint-utils@1.4.3](https://github.com/mysticatea/eslint-utils
) (**MIT**)

[eslint-visitor-keys@1.1.0](https://github.com/eslint/eslint-visitor-keys
) (**Apache-2.0**)

[eslint@6.8.0](https://github.com/eslint/eslint
) (**MIT**)

[espree@6.2.1](https://github.com/eslint/espree
) (**BSD-2-Clause**)

[esprima@1.0.4](https://github.com/ariya/esprima
) (**BSD**)

[esprima@4.0.1](https://github.com/jquery/esprima
) (**BSD-2-Clause**)

[esquery@1.1.0](https://github.com/jrfeenst/esquery
) (**BSD-3-Clause**)

[esrecurse@4.2.1](https://github.com/estools/esrecurse
) (**BSD-2-Clause**)

[estraverse@4.3.0](https://github.com/estools/estraverse
) (**BSD-2-Clause**)

[esutils@2.0.3](https://github.com/estools/esutils
) (**BSD-2-Clause**)

[etag@1.8.1](https://github.com/jshttp/etag
) (**MIT**)

[eventemitter3@4.0.0](https://github.com/primus/eventemitter3
) (**MIT**)

[events@3.1.0](https://github.com/Gozala/events
) (**MIT**)

[eventsource@1.0.7](https://github.com/EventSource/eventsource
) (**MIT**)

[evp_bytestokey@1.0.3](https://github.com/crypto-browserify/EVP_BytesToKey
) (**MIT**)

[exec-sh@0.3.4](https://github.com/tsertkov/exec-sh
) (**MIT**)

[execa@1.0.0](https://github.com/sindresorhus/execa
) (**MIT**)

[exit@0.1.2](https://github.com/cowboy/node-exit
) (**MIT**)

[expand-brackets@2.1.4](https://github.com/jonschlinkert/expand-brackets
) (**MIT**)

[expect@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[express@4.17.1](https://github.com/expressjs/express
) (**MIT**)

[ext@1.4.0](https://github.com/medikoo/es5-ext/tree/ext
) (**ISC**)

[extend-shallow@2.0.1](https://github.com/jonschlinkert/extend-shallow
) (**MIT**)

[extend-shallow@3.0.2](https://github.com/jonschlinkert/extend-shallow
) (**MIT**)

[extend@3.0.2](https://github.com/justmoon/node-extend
) (**MIT**)

[external-editor@3.1.0](https://github.com/mrkmg/node-external-editor
) (**MIT**)

[extglob@2.0.4](https://github.com/micromatch/extglob
) (**MIT**)

[extsprintf@1.3.0](https://github.com/davepacheco/node-extsprintf
) (**MIT**)

[fast-deep-equal@3.1.1](https://github.com/epoberezkin/fast-deep-equal
) (**MIT**)

[fast-diff@1.2.0](https://github.com/jhchen/fast-diff
) (**Apache-2.0**)

[fast-glob@2.2.7](https://github.com/mrmlnc/fast-glob
) (**MIT**)

[fast-json-stable-stringify@2.1.0](https://github.com/epoberezkin/fast-json-stable-stringify
) (**MIT**)

[fast-levenshtein@2.0.6](https://github.com/hiddentao/fast-levenshtein
) (**MIT**)

[faye-websocket@0.10.0](https://github.com/faye/faye-websocket-node
) (**MIT**)

[faye-websocket@0.11.3](https://github.com/faye/faye-websocket-node
) (**Apache-2.0**)

[fb-watchman@2.0.1](https://github.com/facebook/watchman
) (**Apache-2.0**)

[fbjs-css-vars@1.0.2](https://github.com/facebook/fbjs
) (**MIT**)

[fbjs@1.0.0](https://github.com/facebook/fbjs
) (**MIT**)

[figgy-pudding@3.5.1](https://github.com/zkat/figgy-pudding
) (**ISC**)

[figures@3.2.0](https://github.com/sindresorhus/figures
) (**MIT**)

[file-entry-cache@5.0.1](https://github.com/royriojas/file-entry-cache
) (**MIT**)

[file-loader@4.3.0](https://github.com/webpack-contrib/file-loader
) (**MIT**)

[file-uri-to-path@1.0.0](https://github.com/TooTallNate/file-uri-to-path
) (**MIT**)

[filesize@6.0.1](https://github.com/avoidwork/filesize.js
) (**BSD-3-Clause**)

[fill-range@4.0.0](https://github.com/jonschlinkert/fill-range
) (**MIT**)

[fill-range@7.0.1](https://github.com/jonschlinkert/fill-range
) (**MIT**)

[finalhandler@1.1.2](https://github.com/pillarjs/finalhandler
) (**MIT**)

[find-cache-dir@0.1.1](https://github.com/jamestalmage/find-cache-dir
) (**MIT**)

[find-cache-dir@2.1.0](https://github.com/avajs/find-cache-dir
) (**MIT**)

[find-cache-dir@3.3.1](https://github.com/avajs/find-cache-dir
) (**MIT**)

[find-up@1.1.2](https://github.com/sindresorhus/find-up
) (**MIT**)

[find-up@2.1.0](https://github.com/sindresorhus/find-up
) (**MIT**)

[find-up@3.0.0](https://github.com/sindresorhus/find-up
) (**MIT**)

[find-up@4.1.0](https://github.com/sindresorhus/find-up
) (**MIT**)

[flat-cache@2.0.1](https://github.com/royriojas/flat-cache
) (**MIT**)

[flatted@2.0.1](https://github.com/WebReflection/flatted
) (**ISC**)

[flatten@1.0.3](https://github.com/mk-pmb/flatten-js
) (**MIT**)

[flush-write-stream@1.1.1](https://github.com/mafintosh/flush-write-stream
) (**MIT**)

[follow-redirects@1.10.0](https://github.com/follow-redirects/follow-redirects
) (**MIT**)

[for-in@0.1.8](https://github.com/jonschlinkert/for-in
) (**MIT**)

[for-in@1.0.2](https://github.com/jonschlinkert/for-in
) (**MIT**)

[for-own@0.1.5](https://github.com/jonschlinkert/for-own
) (**MIT**)

[forever-agent@0.6.1](https://github.com/mikeal/forever-agent
) (**Apache-2.0**)

[fork-ts-checker-webpack-plugin@3.1.1](https://github.com/TypeStrong/fork-ts-checker-webpack-plugin
) (**MIT**)

[form-data@2.3.3](https://github.com/form-data/form-data
) (**MIT**)

[forwarded@0.1.2](https://github.com/jshttp/forwarded
) (**MIT**)

[fragment-cache@0.2.1](https://github.com/jonschlinkert/fragment-cache
) (**MIT**)

[fresh@0.5.2](https://github.com/jshttp/fresh
) (**MIT**)

[from2@2.3.0](https://github.com/hughsk/from2
) (**MIT**)

[fs-extra@4.0.3](https://github.com/jprichardson/node-fs-extra
) (**MIT**)

[fs-extra@7.0.1](https://github.com/jprichardson/node-fs-extra
) (**MIT**)

[fs-extra@8.1.0](https://github.com/jprichardson/node-fs-extra
) (**MIT**)

[fs-minipass@1.2.7](https://github.com/npm/fs-minipass
) (**ISC**)

[fs-minipass@2.1.0](https://github.com/npm/fs-minipass
) (**ISC**)

[fs-write-stream-atomic@1.0.10](https://github.com/npm/fs-write-stream-atomic
) (**ISC**)

[fs.realpath@1.0.0](https://github.com/isaacs/fs.realpath
) (**ISC**)

[fsevents@1.2.11](https://github.com/strongloop/fsevents
) (**MIT**)

[fsevents@2.1.2](https://github.com/fsevents/fsevents
) (**MIT**)

[fstream@1.0.12](https://github.com/npm/fstream
) (**ISC**)

[function-bind@1.1.1](https://github.com/Raynos/function-bind
) (**MIT**)

[function.prototype.name@1.1.2](https://github.com/es-shims/Function.prototype.name
) (**MIT**)

[functional-red-black-tree@1.0.1](https://github.com/mikolalysenko/functional-red-black-tree
) (**MIT**)

[functions-have-names@1.2.1](https://github.com/ljharb/functions-have-names
) (**MIT**)

[gapi@0.0.3](https://github.com/phated/node-gapi
) (**MIT**)

[gauge@2.7.4](https://github.com/iarna/gauge
) (**ISC**)

[gaze@1.1.3](https://github.com/shama/gaze
) (**MIT**)

[gensync@1.0.0-beta.1](
) (**MIT**)

[geojson-vt@3.2.1](https://github.com/mapbox/geojson-vt
) (**ISC**)

[geojson@0.5.0](https://github.com/caseycesari/geojson.js
) (**MIT**)

[get-caller-file@1.0.3](https://github.com/stefanpenner/get-caller-file
) (**ISC**)

[get-caller-file@2.0.5](https://github.com/stefanpenner/get-caller-file
) (**ISC**)

[get-own-enumerable-property-symbols@3.0.2](https://github.com/mightyiam/get-own-enumerable-property-symbols
) (**ISC**)

[get-stdin@4.0.1](https://github.com/sindresorhus/get-stdin
) (**MIT**)

[get-stdin@6.0.0](https://github.com/sindresorhus/get-stdin
) (**MIT**)

[get-stream@4.1.0](https://github.com/sindresorhus/get-stream
) (**MIT**)

[get-value@2.0.6](https://github.com/jonschlinkert/get-value
) (**MIT**)

[getpass@0.1.7](https://github.com/arekinath/node-getpass
) (**MIT**)

[gl-matrix@3.2.1](https://github.com/toji/gl-matrix
) (**MIT**)

[glob-parent@3.1.0](https://github.com/es128/glob-parent
) (**ISC**)

[glob-parent@5.1.0](https://github.com/gulpjs/glob-parent
) (**ISC**)

[glob-to-regexp@0.3.0](https://github.com/fitzgen/glob-to-regexp
) (**BSD***)

[glob@7.1.6](https://github.com/isaacs/node-glob
) (**ISC**)

[global-modules@2.0.0](https://github.com/jonschlinkert/global-modules
) (**MIT**)

[global-prefix@3.0.0](https://github.com/jonschlinkert/global-prefix
) (**MIT**)

[globals@11.12.0](https://github.com/sindresorhus/globals
) (**MIT**)

[globals@12.4.0](https://github.com/sindresorhus/globals
) (**MIT**)

[globby@6.1.0](https://github.com/sindresorhus/globby
) (**MIT**)

[globby@8.0.2](https://github.com/sindresorhus/globby
) (**MIT**)

[globule@1.3.1](https://github.com/cowboy/node-globule
) (**MIT**)

[graceful-fs@4.2.3](https://github.com/isaacs/node-graceful-fs
) (**ISC**)

[grid-index@1.1.0](https://github.com/mapbox/grid-index
) (**ISC**)

[growly@1.3.0](https://github.com/theabraham/growly
) (**MIT**)

[gud@1.0.0](https://github.com/jamiebuilds/global-unique-id
) (**MIT**)

[gzip-size@5.1.1](https://github.com/sindresorhus/gzip-size
) (**MIT**)

[hammerjs@2.0.8](https://github.com/hammerjs/hammer.js
) (**MIT**)

[handle-thing@2.0.0](https://github.com/indutny/handle-thing
) (**MIT**)

[har-schema@2.0.0](https://github.com/ahmadnassri/har-schema
) (**ISC**)

[har-validator@5.1.3](https://github.com/ahmadnassri/node-har-validator
) (**MIT**)

[harmony-reflect@1.6.1](git+https://tvcutsem@github.com/tvcutsem/harmony-reflect
) (**(Apache-2.0 OR MPL-1.1)**)

[has-ansi@2.0.0](https://github.com/sindresorhus/has-ansi
) (**MIT**)

[has-flag@3.0.0](https://github.com/sindresorhus/has-flag
) (**MIT**)

[has-flag@4.0.0](https://github.com/sindresorhus/has-flag
) (**MIT**)

[has-symbols@1.0.1](https://github.com/ljharb/has-symbols
) (**MIT**)

[has-unicode@2.0.1](https://github.com/iarna/has-unicode
) (**ISC**)

[has-value@0.3.1](https://github.com/jonschlinkert/has-value
) (**MIT**)

[has-value@1.0.0](https://github.com/jonschlinkert/has-value
) (**MIT**)

[has-values@0.1.4](https://github.com/jonschlinkert/has-values
) (**MIT**)

[has-values@1.0.0](https://github.com/jonschlinkert/has-values
) (**MIT**)

[has@1.0.3](https://github.com/tarruda/has
) (**MIT**)

[hash-base@3.0.4](https://github.com/crypto-browserify/hash-base
) (**MIT**)

[hash.js@1.1.7](https://github.com/indutny/hash.js
) (**MIT**)

[he@1.2.0](https://github.com/mathiasbynens/he
) (**MIT**)

[hex-color-regex@1.1.0](https://github.com/regexps/hex-color-regex
) (**MIT**)

[highcharts-react-official@2.2.2](https://github.com/highcharts/highcharts-react
) (**MIT***)

[highcharts@8.0.4](https://github.com/highcharts/highcharts-dist
) (**Custom: https://www.npmjs.com/package/highcharts-export-server**)

[history@4.10.1](https://github.com/ReactTraining/history
) (**MIT**)

[hmac-drbg@1.0.1](https://github.com/indutny/hmac-drbg
) (**MIT**)

[hoist-non-react-statics@3.3.2](https://github.com/mridgway/hoist-non-react-statics
) (**BSD-3-Clause**)

[hosted-git-info@2.8.8](https://github.com/npm/hosted-git-info
) (**ISC**)

[hourglass@0.1.0](
) (**UNLICENSED**)

[hpack.js@2.1.6](https://github.com/indutny/hpack.js
) (**MIT**)

[hsl-regex@1.0.0](https://github.com/regexps/hsl-regex
) (**MIT**)

[hsla-regex@1.0.0](https://github.com/regexps/hsla-regex
) (**MIT**)

[html-comment-regex@1.1.2](https://github.com/stevemao/html-comment-regex
) (**MIT**)

[html-element-map@1.2.0](https://github.com/ljharb/html-element-map
) (**MIT**)

[html-encoding-sniffer@1.0.2](https://github.com/jsdom/html-encoding-sniffer
) (**MIT**)

[html-entities@1.2.1](https://github.com/mdevils/node-html-entities
) (**MIT**)

[html-escaper@2.0.0](https://github.com/WebReflection/html-escaper
) (**MIT**)

[html-minifier-terser@5.0.4](https://github.com/DanielRuf/html-minifier-terser
) (**MIT**)

[html-webpack-plugin@4.0.0-beta.11](https://github.com/jantimon/html-webpack-plugin
) (**MIT**)

[htmlparser2@3.10.1](https://github.com/fb55/htmlparser2
) (**MIT**)

[http-deceiver@1.2.7](https://github.com/indutny/http-deceiver
) (**MIT**)

[http-errors@1.6.3](https://github.com/jshttp/http-errors
) (**MIT**)

[http-errors@1.7.2](https://github.com/jshttp/http-errors
) (**MIT**)

[http-parser-js@0.4.10](https://github.com/creationix/http-parser-js
) (**MIT**)

[http-proxy-middleware@0.19.1](https://github.com/chimurai/http-proxy-middleware
) (**MIT**)

[http-proxy@1.18.0](https://github.com/http-party/node-http-proxy
) (**MIT**)

[http-signature@1.2.0](https://github.com/joyent/node-http-signature
) (**MIT**)

[https-browserify@1.0.0](https://github.com/substack/https-browserify
) (**MIT**)

[hyphenate-style-name@1.0.3](https://github.com/rexxars/hyphenate-style-name
) (**BSD-3-Clause**)

[iconv-lite@0.4.24](https://github.com/ashtuchkin/iconv-lite
) (**MIT**)

[icss-utils@4.1.1](https://github.com/css-modules/icss-utils
) (**ISC**)

[identity-obj-proxy@3.0.0](https://github.com/keyanzhang/identity-obj-proxy
) (**MIT**)

[ieee754@1.1.13](https://github.com/feross/ieee754
) (**BSD-3-Clause**)

[iferr@0.1.5](https://github.com/shesek/iferr
) (**MIT**)

[ignore-walk@3.0.3](https://github.com/isaacs/ignore-walk
) (**ISC**)

[ignore@3.3.10](https://github.com/kaelzhang/node-ignore
) (**MIT**)

[ignore@4.0.6](https://github.com/kaelzhang/node-ignore
) (**MIT**)

[immer@1.10.0](https://github.com/mweststrate/immer
) (**MIT**)

[immutable@3.7.6](https://github.com/facebook/immutable-js
) (**BSD-3-Clause**)

[import-cwd@2.1.0](https://github.com/sindresorhus/import-cwd
) (**MIT**)

[import-fresh@2.0.0](https://github.com/sindresorhus/import-fresh
) (**MIT**)

[import-fresh@3.2.1](https://github.com/sindresorhus/import-fresh
) (**MIT**)

[import-from@2.1.0](https://github.com/sindresorhus/import-from
) (**MIT**)

[import-local@2.0.0](https://github.com/sindresorhus/import-local
) (**MIT**)

[imurmurhash@0.1.4](https://github.com/jensyt/imurmurhash-js
) (**MIT**)

[in-publish@2.0.0](https://github.com/iarna/in-publish
) (**ISC**)

[indent-string@2.1.0](https://github.com/sindresorhus/indent-string
) (**MIT**)

[indent-string@4.0.0](https://github.com/sindresorhus/indent-string
) (**MIT**)

[indexes-of@1.0.1](https://github.com/dominictarr/indexes-of
) (**MIT**)

[infer-owner@1.0.4](https://github.com/npm/infer-owner
) (**ISC**)

[inflight@1.0.6](https://github.com/npm/inflight
) (**ISC**)

[inherits@2.0.1](https://github.com/isaacs/inherits
) (**ISC**)

[inherits@2.0.3](https://github.com/isaacs/inherits
) (**ISC**)

[inherits@2.0.4](https://github.com/isaacs/inherits
) (**ISC**)

[ini@1.3.5](https://github.com/isaacs/ini
) (**ISC**)

[inquirer@7.0.4](https://github.com/SBoudrias/Inquirer.js
) (**MIT**)

[inquirer@7.1.0](https://github.com/SBoudrias/Inquirer.js
) (**MIT**)

[internal-ip@4.3.0](https://github.com/sindresorhus/internal-ip
) (**MIT**)

[internal-slot@1.0.2](https://github.com/ljharb/internal-slot
) (**MIT**)

[invariant@2.2.4](https://github.com/zertosh/invariant
) (**MIT**)

[invert-kv@1.0.0](https://github.com/sindresorhus/invert-kv
) (**MIT**)

[invert-kv@2.0.0](https://github.com/sindresorhus/invert-kv
) (**MIT**)

[ip-regex@2.1.0](https://github.com/sindresorhus/ip-regex
) (**MIT**)

[ip@1.1.5](https://github.com/indutny/node-ip
) (**MIT**)

[ipaddr.js@1.9.1](https://github.com/whitequark/ipaddr.js
) (**MIT**)

[is-absolute-url@2.1.0](https://github.com/sindresorhus/is-absolute-url
) (**MIT**)

[is-absolute-url@3.0.3](https://github.com/sindresorhus/is-absolute-url
) (**MIT**)

[is-accessor-descriptor@0.1.6](https://github.com/jonschlinkert/is-accessor-descriptor
) (**MIT**)

[is-accessor-descriptor@1.0.0](https://github.com/jonschlinkert/is-accessor-descriptor
) (**MIT**)

[is-arguments@1.0.4](https://github.com/ljharb/is-arguments
) (**MIT**)

[is-arrayish@0.2.1](https://github.com/qix-/node-is-arrayish
) (**MIT**)

[is-arrayish@0.3.2](https://github.com/qix-/node-is-arrayish
) (**MIT**)

[is-binary-path@1.0.1](https://github.com/sindresorhus/is-binary-path
) (**MIT**)

[is-binary-path@2.1.0](https://github.com/sindresorhus/is-binary-path
) (**MIT**)

[is-boolean-object@1.0.1](https://github.com/ljharb/is-boolean-object
) (**MIT**)

[is-buffer@1.1.6](https://github.com/feross/is-buffer
) (**MIT**)

[is-callable@1.1.5](https://github.com/ljharb/is-callable
) (**MIT**)

[is-ci@2.0.0](https://github.com/watson/is-ci
) (**MIT**)

[is-color-stop@1.1.0](https://github.com/pigcan/is-color-stop
) (**MIT**)

[is-data-descriptor@0.1.4](https://github.com/jonschlinkert/is-data-descriptor
) (**MIT**)

[is-data-descriptor@1.0.0](https://github.com/jonschlinkert/is-data-descriptor
) (**MIT**)

[is-date-object@1.0.2](https://github.com/ljharb/is-date-object
) (**MIT**)

[is-descriptor@0.1.6](https://github.com/jonschlinkert/is-descriptor
) (**MIT**)

[is-descriptor@1.0.2](https://github.com/jonschlinkert/is-descriptor
) (**MIT**)

[is-directory@0.3.1](https://github.com/jonschlinkert/is-directory
) (**MIT**)

[is-docker@2.0.0](https://github.com/sindresorhus/is-docker
) (**MIT**)

[is-extendable@0.1.1](https://github.com/jonschlinkert/is-extendable
) (**MIT**)

[is-extendable@1.0.1](https://github.com/jonschlinkert/is-extendable
) (**MIT**)

[is-extglob@2.1.1](https://github.com/jonschlinkert/is-extglob
) (**MIT**)

[is-finite@1.1.0](https://github.com/sindresorhus/is-finite
) (**MIT**)

[is-fullwidth-code-point@1.0.0](https://github.com/sindresorhus/is-fullwidth-code-point
) (**MIT**)

[is-fullwidth-code-point@2.0.0](https://github.com/sindresorhus/is-fullwidth-code-point
) (**MIT**)

[is-fullwidth-code-point@3.0.0](https://github.com/sindresorhus/is-fullwidth-code-point
) (**MIT**)

[is-generator-fn@2.1.0](https://github.com/sindresorhus/is-generator-fn
) (**MIT**)

[is-glob@3.1.0](https://github.com/jonschlinkert/is-glob
) (**MIT**)

[is-glob@4.0.1](https://github.com/micromatch/is-glob
) (**MIT**)

[is-in-browser@1.1.3](https://github.com/tuxsudo/is-in-browser
) (**MIT**)

[is-number-object@1.0.4](https://github.com/inspect-js/is-number-object
) (**MIT**)

[is-number@3.0.0](https://github.com/jonschlinkert/is-number
) (**MIT**)

[is-number@7.0.0](https://github.com/jonschlinkert/is-number
) (**MIT**)

[is-obj@1.0.1](https://github.com/sindresorhus/is-obj
) (**MIT**)

[is-obj@2.0.0](https://github.com/sindresorhus/is-obj
) (**MIT**)

[is-path-cwd@2.2.0](https://github.com/sindresorhus/is-path-cwd
) (**MIT**)

[is-path-in-cwd@2.1.0](https://github.com/sindresorhus/is-path-in-cwd
) (**MIT**)

[is-path-inside@2.1.0](https://github.com/sindresorhus/is-path-inside
) (**MIT**)

[is-plain-obj@1.1.0](https://github.com/sindresorhus/is-plain-obj
) (**MIT**)

[is-plain-object@2.0.4](https://github.com/jonschlinkert/is-plain-object
) (**MIT**)

[is-promise@2.1.0](https://github.com/then/is-promise
) (**MIT**)

[is-regex@1.0.5](https://github.com/ljharb/is-regex
) (**MIT**)

[is-regexp@1.0.0](https://github.com/sindresorhus/is-regexp
) (**MIT**)

[is-resolvable@1.1.0](https://github.com/shinnn/is-resolvable
) (**ISC**)

[is-root@2.1.0](https://github.com/sindresorhus/is-root
) (**MIT**)

[is-stream@1.1.0](https://github.com/sindresorhus/is-stream
) (**MIT**)

[is-string@1.0.5](https://github.com/ljharb/is-string
) (**MIT**)

[is-subset@0.1.1](https://github.com/studio-b12/is-subset
) (**MIT**)

[is-svg@3.0.0](https://github.com/sindresorhus/is-svg
) (**MIT**)

[is-symbol@1.0.3](https://github.com/inspect-js/is-symbol
) (**MIT**)

[is-typedarray@1.0.0](https://github.com/hughsk/is-typedarray
) (**MIT**)

[is-utf8@0.2.1](https://github.com/wayfind/is-utf8
) (**MIT**)

[is-windows@1.0.2](https://github.com/jonschlinkert/is-windows
) (**MIT**)

[is-wsl@1.1.0](https://github.com/sindresorhus/is-wsl
) (**MIT**)

[is-wsl@2.1.1](https://github.com/sindresorhus/is-wsl
) (**MIT**)

[isarray@0.0.1](https://github.com/juliangruber/isarray
) (**MIT**)

[isarray@1.0.0](https://github.com/juliangruber/isarray
) (**MIT**)

[isexe@2.0.0](https://github.com/isaacs/isexe
) (**ISC**)

[isobject@2.1.0](https://github.com/jonschlinkert/isobject
) (**MIT**)

[isobject@3.0.1](https://github.com/jonschlinkert/isobject
) (**MIT**)

[isomorphic-fetch@2.2.1](https://github.com/matthew-andrews/isomorphic-fetch
) (**MIT**)

[isstream@0.1.2](https://github.com/rvagg/isstream
) (**MIT**)

[istanbul-lib-coverage@2.0.5](https://github.com/istanbuljs/istanbuljs
) (**BSD-3-Clause**)

[istanbul-lib-instrument@3.3.0](https://github.com/istanbuljs/istanbuljs
) (**BSD-3-Clause**)

[istanbul-lib-report@2.0.8](https://github.com/istanbuljs/istanbuljs
) (**BSD-3-Clause**)

[istanbul-lib-source-maps@3.0.6](https://github.com/istanbuljs/istanbuljs
) (**BSD-3-Clause**)

[istanbul-reports@2.2.7](https://github.com/istanbuljs/istanbuljs
) (**BSD-3-Clause**)

[jest-changed-files@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-cli@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-config@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-diff@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-docblock@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-each@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-environment-jsdom-fourteen@1.0.1](https://github.com/ianschmitz/jest-environment-jsdom-fourteen
) (**MIT**)

[jest-environment-jsdom@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-environment-node@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-get-type@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-haste-map@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-jasmine2@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-leak-detector@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-matcher-utils@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-message-util@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-mock@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-pnp-resolver@1.2.1](https://github.com/arcanis/jest-pnp-resolver
) (**MIT**)

[jest-regex-util@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-resolve-dependencies@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-resolve@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-runner@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-runtime@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-serializer@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-snapshot@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-util@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-validate@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-watch-typeahead@0.4.2](https://github.com/jest-community/jest-watch-typeahead
) (**MIT**)

[jest-watcher@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-worker@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[jest-worker@25.1.0](https://github.com/facebook/jest
) (**MIT**)

[jest@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[js-base64@2.5.2](https://github.com/dankogai/js-base64
) (**BSD-3-Clause**)

[js-tokens@3.0.2](https://github.com/lydell/js-tokens
) (**MIT**)

[js-tokens@4.0.0](https://github.com/lydell/js-tokens
) (**MIT**)

[js-yaml@3.13.1](https://github.com/nodeca/js-yaml
) (**MIT**)

[jsbn@0.1.1](https://github.com/andyperlitch/jsbn
) (**MIT**)

[jsdom@11.12.0](https://github.com/jsdom/jsdom
) (**MIT**)

[jsdom@14.1.0](https://github.com/jsdom/jsdom
) (**MIT**)

[jsesc@0.5.0](https://github.com/mathiasbynens/jsesc
) (**MIT**)

[jsesc@2.5.2](https://github.com/mathiasbynens/jsesc
) (**MIT**)

[json-parse-better-errors@1.0.2](https://github.com/zkat/json-parse-better-errors
) (**MIT**)

[json-schema-traverse@0.4.1](https://github.com/epoberezkin/json-schema-traverse
) (**MIT**)

[json-schema@0.2.3](BSD) (**AFLv2.1**)

[json-stable-stringify-without-jsonify@1.0.1](https://github.com/samn/json-stable-stringify
) (**MIT**)

[json-stable-stringify@1.0.1](https://github.com/substack/json-stable-stringify
) (**MIT**)

[json-stringify-safe@5.0.1](https://github.com/isaacs/json-stringify-safe
) (**ISC**)

[json3@3.3.3](https://github.com/bestiejs/json3
) (**MIT**)

[json5@1.0.1](https://github.com/json5/json5
) (**MIT**)

[json5@2.1.1](https://github.com/json5/json5
) (**MIT**)

[jsonfile@4.0.0](https://github.com/jprichardson/node-jsonfile
) (**MIT**)

[jsonify@0.0.0](https://github.com/substack/jsonify
) (**Public Domain**)

[jsonp@0.2.1](https://github.com/LearnBoost/jsonp
) (**MIT***)

[jsprim@1.4.1](https://github.com/joyent/node-jsprim
) (**MIT**)

[jss-plugin-camel-case@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss-plugin-default-unit@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss-plugin-global@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss-plugin-nested@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss-plugin-props-sort@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss-plugin-rule-value-function@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss-plugin-vendor-prefixer@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jss@10.0.4](https://github.com/cssinjs/jss
) (**MIT**)

[jsx-ast-utils@2.2.3](https://github.com/evcohen/jsx-ast-utils
) (**MIT**)

[kdbush@3.0.0](https://github.com/mourner/kdbush
) (**ISC**)

[killable@1.0.1](https://github.com/marten-de-vries/killable
) (**ISC**)

[kind-of@2.0.1](https://github.com/jonschlinkert/kind-of
) (**MIT**)

[kind-of@3.2.2](https://github.com/jonschlinkert/kind-of
) (**MIT**)

[kind-of@4.0.0](https://github.com/jonschlinkert/kind-of
) (**MIT**)

[kind-of@5.1.0](https://github.com/jonschlinkert/kind-of
) (**MIT**)

[kind-of@6.0.3](https://github.com/jonschlinkert/kind-of
) (**MIT**)

[kleur@3.0.3](https://github.com/lukeed/kleur
) (**MIT**)

[last-call-webpack-plugin@3.0.0](https://github.com/NMFR/last-call-webpack-plugin
) (**MIT**)

[lazy-cache@0.2.7](https://github.com/jonschlinkert/lazy-cache
) (**MIT**)

[lazy-cache@1.0.4](https://github.com/jonschlinkert/lazy-cache
) (**MIT**)

[lcid@1.0.0](https://github.com/sindresorhus/lcid
) (**MIT**)

[lcid@2.0.0](https://github.com/sindresorhus/lcid
) (**MIT**)

[left-pad@1.3.0](https://github.com/stevemao/left-pad
) (**WTFPL**)

[leven@3.1.0](https://github.com/sindresorhus/leven
) (**MIT**)

[levenary@1.1.1](https://github.com/tanhauhau/levenary
) (**MIT**)

[levn@0.3.0](https://github.com/gkz/levn
) (**MIT**)

[lines-and-columns@1.1.6](https://github.com/eventualbuddha/lines-and-columns
) (**MIT**)

[load-json-file@1.1.0](https://github.com/sindresorhus/load-json-file
) (**MIT**)

[load-json-file@2.0.0](https://github.com/sindresorhus/load-json-file
) (**MIT**)

[load-json-file@4.0.0](https://github.com/sindresorhus/load-json-file
) (**MIT**)

[loader-fs-cache@1.0.2](
) (**MIT**)

[loader-runner@2.4.0](https://github.com/webpack/loader-runner
) (**MIT**)

[loader-utils@1.2.3](https://github.com/webpack/loader-utils
) (**MIT**)

[loader-utils@1.4.0](https://github.com/webpack/loader-utils
) (**MIT**)

[locate-path@2.0.0](https://github.com/sindresorhus/locate-path
) (**MIT**)

[locate-path@3.0.0](https://github.com/sindresorhus/locate-path
) (**MIT**)

[locate-path@5.0.0](https://github.com/sindresorhus/locate-path
) (**MIT**)

[lodash._reinterpolate@3.0.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash.escape@4.0.1](https://github.com/lodash/lodash
) (**MIT**)

[lodash.flattendeep@4.4.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash.isequal@4.5.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash.memoize@4.1.2](https://github.com/lodash/lodash
) (**MIT**)

[lodash.sortby@4.7.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash.template@4.5.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash.templatesettings@4.2.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash.uniq@4.5.0](https://github.com/lodash/lodash
) (**MIT**)

[lodash@4.17.15](https://github.com/lodash/lodash
) (**MIT**)

[loglevel@1.6.7](https://github.com/pimterry/loglevel
) (**MIT**)

[loose-envify@1.4.0](https://github.com/zertosh/loose-envify
) (**MIT**)

[loud-rejection@1.6.0](https://github.com/sindresorhus/loud-rejection
) (**MIT**)

[lower-case@2.0.1](https://github.com/blakeembrey/change-case
) (**MIT**)

[lru-cache@4.1.5](https://github.com/isaacs/node-lru-cache
) (**ISC**)

[lru-cache@5.1.1](https://github.com/isaacs/node-lru-cache
) (**ISC**)

[make-dir@2.1.0](https://github.com/sindresorhus/make-dir
) (**MIT**)

[make-dir@3.0.2](https://github.com/sindresorhus/make-dir
) (**MIT**)

[makeerror@1.0.11](https://github.com/daaku/nodejs-makeerror
) (**BSD-3-Clause**)

[mamacro@0.0.3](
) (**MIT**)

[map-age-cleaner@0.1.3](https://github.com/SamVerschueren/map-age-cleaner
) (**MIT**)

[map-cache@0.2.2](https://github.com/jonschlinkert/map-cache
) (**MIT**)

[map-obj@1.0.1](https://github.com/sindresorhus/map-obj
) (**MIT**)

[map-visit@1.0.0](https://github.com/jonschlinkert/map-visit
) (**MIT**)

[mapbox-gl@1.8.1](https://github.com/mapbox/mapbox-gl-js
) (**MIT***)

[md5.js@1.3.5](https://github.com/crypto-browserify/md5.js
) (**MIT**)

[mdn-data@2.0.4](https://github.com/mdn/data
) (**CC0-1.0**)

[media-typer@0.3.0](https://github.com/jshttp/media-typer
) (**MIT**)

[mem@4.3.0](https://github.com/sindresorhus/mem
) (**MIT**)

[memory-fs@0.4.1](https://github.com/webpack/memory-fs
) (**MIT**)

[memory-fs@0.5.0](https://github.com/webpack/memory-fs
) (**MIT**)

[meow@3.7.0](https://github.com/sindresorhus/meow
) (**MIT**)

[merge-deep@3.0.2](https://github.com/jonschlinkert/merge-deep
) (**MIT**)

[merge-descriptors@1.0.1](https://github.com/component/merge-descriptors
) (**MIT**)

[merge-stream@2.0.0](https://github.com/grncdr/merge-stream
) (**MIT**)

[merge2@1.3.0](https://github.com/teambition/merge2
) (**MIT**)

[methods@1.1.2](https://github.com/jshttp/methods
) (**MIT**)

[microevent.ts@0.1.1](https://github.com/DirtyHairy/microevent
) (**MIT**)

[micromatch@3.1.10](https://github.com/micromatch/micromatch
) (**MIT**)

[miller-rabin@4.0.1](https://github.com/indutny/miller-rabin
) (**MIT**)

[mime-db@1.43.0](https://github.com/jshttp/mime-db
) (**MIT**)

[mime-types@2.1.26](https://github.com/jshttp/mime-types
) (**MIT**)

[mime@1.6.0](https://github.com/broofa/node-mime
) (**MIT**)

[mime@2.4.4](https://github.com/broofa/node-mime
) (**MIT**)

[mimic-fn@2.1.0](https://github.com/sindresorhus/mimic-fn
) (**MIT**)

[min-indent@1.0.0](https://github.com/thejameskyle/min-indent
) (**MIT**)

[mini-create-react-context@0.3.2](https://github.com/StringEpsilon/mini-create-react-context
) (**MIT**)

[mini-css-extract-plugin@0.9.0](https://github.com/webpack-contrib/mini-css-extract-plugin
) (**MIT**)

[minimalistic-assert@1.0.1](https://github.com/calvinmetcalf/minimalistic-assert
) (**ISC**)

[minimalistic-crypto-utils@1.0.1](https://github.com/indutny/minimalistic-crypto-utils
) (**MIT**)

[minimatch@3.0.4](https://github.com/isaacs/minimatch
) (**ISC**)

[minimist@0.0.5](https://github.com/substack/minimist
) (**MIT**)

[minimist@0.0.8](https://github.com/substack/minimist
) (**MIT**)

[minimist@1.2.0](https://github.com/substack/minimist
) (**MIT**)

[minimist@1.2.3](https://github.com/substack/minimist
) (**MIT**)

[minimist@1.2.5](https://github.com/substack/minimist
) (**MIT**)

[minipass-collect@1.0.2](
) (**ISC**)

[minipass-flush@1.0.5](https://github.com/isaacs/minipass-flush
) (**ISC**)

[minipass-pipeline@1.2.2](
) (**ISC**)

[minipass@2.9.0](https://github.com/isaacs/minipass
) (**ISC**)

[minipass@3.1.1](https://github.com/isaacs/minipass
) (**ISC**)

[minizlib@1.3.3](https://github.com/isaacs/minizlib
) (**MIT**)

[mississippi@3.0.0](https://github.com/maxogden/mississippi
) (**BSD-2-Clause**)

[mixin-deep@1.3.2](https://github.com/jonschlinkert/mixin-deep
) (**MIT**)

[mixin-object@2.0.1](https://github.com/jonschlinkert/mixin-object
) (**MIT**)

[mjolnir.js@2.4.0](https://github.com/uber-web/mjolnir.js
) (**MIT**)

[mkdirp@0.5.1](https://github.com/substack/node-mkdirp
) (**MIT**)

[moo@0.5.1](https://github.com/tjvr/moo
) (**BSD-3-Clause**)

[move-concurrently@1.0.1](https://github.com/npm/move-concurrently
) (**ISC**)

[ms@2.0.0](https://github.com/zeit/ms
) (**MIT**)

[ms@2.1.1](https://github.com/zeit/ms
) (**MIT**)

[ms@2.1.2](https://github.com/zeit/ms
) (**MIT**)

[multicast-dns-service-types@1.1.0](https://github.com/mafintosh/multicast-dns-service-types
) (**MIT**)

[multicast-dns@6.2.3](https://github.com/mafintosh/multicast-dns
) (**MIT**)

[murmurhash-js@1.0.0](https://github.com/mikolalysenko/murmurhash-js
) (**MIT**)

[mute-stream@0.0.8](https://github.com/isaacs/mute-stream
) (**ISC**)

[nan@2.14.0](https://github.com/nodejs/nan
) (**MIT**)

[nanomatch@1.2.13](https://github.com/micromatch/nanomatch
) (**MIT**)

[natural-compare@1.4.0](https://github.com/litejs/natural-compare-lite
) (**MIT**)

[nearley@2.19.1](https://github.com/hardmath123/nearley
) (**MIT**)

[needle@2.4.0](https://github.com/tomas/needle
) (**MIT**)

[negotiator@0.6.2](https://github.com/jshttp/negotiator
) (**MIT**)

[neo-async@2.6.1](https://github.com/suguru03/neo-async
) (**MIT**)

[Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json/blob/master/LICENSE.md
) (**MIT**)

[next-tick@1.0.0](https://github.com/medikoo/next-tick
) (**MIT**)

[nice-try@1.0.5](https://github.com/electerious/nice-try
) (**MIT**)

[no-case@3.0.3](https://github.com/blakeembrey/change-case
) (**MIT**)

[node-fetch@1.7.3](https://github.com/bitinn/node-fetch
) (**MIT**)

[node-forge@0.9.0](https://github.com/digitalbazaar/forge
) (**(BSD-3-Clause OR GPL-2.0)**)

[node-gyp@3.8.0](https://github.com/nodejs/node-gyp
) (**MIT**)

[node-int64@0.4.0](https://github.com/broofa/node-int64
) (**MIT**)

[node-libs-browser@2.2.1](https://github.com/webpack/node-libs-browser
) (**MIT**)

[node-modules-regexp@1.0.0](https://github.com/jamestalmage/node-modules-regexp
) (**MIT**)

[node-notifier@5.4.3](https://github.com/mikaelbr/node-notifier
) (**MIT**)

[node-pre-gyp@0.14.0](https://github.com/mapbox/node-pre-gyp
) (**BSD-3-Clause**)

[node-releases@1.1.51](https://github.com/chicoxyzzy/node-releases
) (**MIT**)

[node-sass@4.13.1](https://github.com/sass/node-sass
) (**MIT**)

[nopt@3.0.6](https://github.com/npm/nopt
) (**ISC**)

[nopt@4.0.1](https://github.com/npm/nopt
) (**ISC**)

[normalize-package-data@2.5.0](https://github.com/npm/normalize-package-data
) (**BSD-2-Clause**)

[normalize-path@2.1.1](https://github.com/jonschlinkert/normalize-path
) (**MIT**)

[normalize-path@3.0.0](https://github.com/jonschlinkert/normalize-path
) (**MIT**)

[normalize-range@0.1.2](https://github.com/jamestalmage/normalize-range
) (**MIT**)

[normalize-url@1.9.1](https://github.com/sindresorhus/normalize-url
) (**MIT**)

[normalize-url@3.3.0](https://github.com/sindresorhus/normalize-url
) (**MIT**)

[npgsql](https://github.com/npgsql/npgsql/blob/master/LICENSE
) (**PostgreSQL**)

[npm-bundled@1.1.1](https://github.com/npm/npm-bundled
) (**ISC**)

[npm-normalize-package-bin@1.0.1](https://github.com/npm/npm-normalize-package-bin
) (**ISC**)

[npm-packlist@1.4.7](https://github.com/npm/npm-packlist
) (**ISC**)

[npm-run-path@2.0.2](https://github.com/sindresorhus/npm-run-path
) (**MIT**)

[npmlog@4.1.2](https://github.com/npm/npmlog
) (**ISC**)

[nth-check@1.0.2](https://github.com/fb55/nth-check
) (**BSD-2-Clause**)

[num2fraction@1.2.2](https://github.com/yisibl/num2fraction
) (**MIT**)

[number-is-nan@1.0.1](https://github.com/sindresorhus/number-is-nan
) (**MIT**)

[nwsapi@2.2.0](https://github.com/dperini/nwsapi
) (**MIT**)

[oauth-sign@0.9.0](https://github.com/mikeal/oauth-sign
) (**Apache-2.0**)

[object-assign@4.1.1](https://github.com/sindresorhus/object-assign
) (**MIT**)

[object-copy@0.1.0](https://github.com/jonschlinkert/object-copy
) (**MIT**)

[object-hash@2.0.3](https://github.com/puleos/object-hash
) (**MIT**)

[object-inspect@1.7.0](https://github.com/substack/object-inspect
) (**MIT**)

[object-is@1.0.2](https://github.com/es-shims/object-is
) (**MIT**)

[object-keys@1.1.1](https://github.com/ljharb/object-keys
) (**MIT**)

[object-path@0.11.4](https://github.com/mariocasciaro/object-path
) (**MIT**)

[object-visit@1.0.1](https://github.com/jonschlinkert/object-visit
) (**MIT**)

[object.assign@4.1.0](https://github.com/ljharb/object.assign
) (**MIT**)

[object.entries@1.1.1](https://github.com/es-shims/Object.entries
) (**MIT**)

[object.fromentries@2.0.2](https://github.com/es-shims/Object.fromEntries
) (**MIT**)

[object.getownpropertydescriptors@2.1.0](https://github.com/es-shims/object.getownpropertydescriptors
) (**MIT**)

[object.pick@1.3.0](https://github.com/jonschlinkert/object.pick
) (**MIT**)

[object.values@1.1.1](https://github.com/es-shims/Object.values
) (**MIT**)

[obuf@1.1.2](https://github.com/indutny/offset-buffer
) (**MIT**)

[on-finished@2.3.0](https://github.com/jshttp/on-finished
) (**MIT**)

[on-headers@1.0.2](https://github.com/jshttp/on-headers
) (**MIT**)

[once@1.4.0](https://github.com/isaacs/once
) (**ISC**)

[onetime@5.1.0](https://github.com/sindresorhus/onetime
) (**MIT**)

[open@7.0.3](https://github.com/sindresorhus/open
) (**MIT**)

[opn@5.5.0](https://github.com/sindresorhus/opn
) (**MIT**)

[optimize-css-assets-webpack-plugin@5.0.3](https://github.com/NMFR/optimize-css-assets-webpack-plugin
) (**MIT**)

[optionator@0.8.3](https://github.com/gkz/optionator
) (**MIT**)

[original@1.0.2](https://github.com/unshiftio/original
) (**MIT**)

[os-browserify@0.3.0](https://github.com/CoderPuppy/os-browserify
) (**MIT**)

[os-homedir@1.0.2](https://github.com/sindresorhus/os-homedir
) (**MIT**)

[os-locale@1.4.0](https://github.com/sindresorhus/os-locale
) (**MIT**)

[os-locale@3.1.0](https://github.com/sindresorhus/os-locale
) (**MIT**)

[os-tmpdir@1.0.2](https://github.com/sindresorhus/os-tmpdir
) (**MIT**)

[osenv@0.1.5](https://github.com/npm/osenv
) (**ISC**)

[p-defer@1.0.0](https://github.com/sindresorhus/p-defer
) (**MIT**)

[p-each-series@1.0.0](https://github.com/sindresorhus/p-each-series
) (**MIT**)

[p-finally@1.0.0](https://github.com/sindresorhus/p-finally
) (**MIT**)

[p-is-promise@2.1.0](https://github.com/sindresorhus/p-is-promise
) (**MIT**)

[p-limit@1.3.0](https://github.com/sindresorhus/p-limit
) (**MIT**)

[p-limit@2.2.2](https://github.com/sindresorhus/p-limit
) (**MIT**)

[p-locate@2.0.0](https://github.com/sindresorhus/p-locate
) (**MIT**)

[p-locate@3.0.0](https://github.com/sindresorhus/p-locate
) (**MIT**)

[p-locate@4.1.0](https://github.com/sindresorhus/p-locate
) (**MIT**)

[p-map@2.1.0](https://github.com/sindresorhus/p-map
) (**MIT**)

[p-map@3.0.0](https://github.com/sindresorhus/p-map
) (**MIT**)

[p-reduce@1.0.0](https://github.com/sindresorhus/p-reduce
) (**MIT**)

[p-retry@3.0.1](https://github.com/sindresorhus/p-retry
) (**MIT**)

[p-try@1.0.0](https://github.com/sindresorhus/p-try
) (**MIT**)

[p-try@2.2.0](https://github.com/sindresorhus/p-try
) (**MIT**)

[pako@1.0.11](https://github.com/nodeca/pako
) (**(MIT AND Zlib)**)

[parallel-transform@1.2.0](https://github.com/mafintosh/parallel-transform
) (**MIT**)

[param-case@3.0.3](https://github.com/blakeembrey/change-case
) (**MIT**)

[parent-module@1.0.1](https://github.com/sindresorhus/parent-module
) (**MIT**)

[parse-asn1@5.1.5](https://github.com/crypto-browserify/parse-asn1
) (**ISC**)

[parse-json@2.2.0](https://github.com/sindresorhus/parse-json
) (**MIT**)

[parse-json@4.0.0](https://github.com/sindresorhus/parse-json
) (**MIT**)

[parse-json@5.0.0](https://github.com/sindresorhus/parse-json
) (**MIT**)

[parse5@3.0.3](https://github.com/inikulin/parse5
) (**MIT**)

[parse5@4.0.0](https://github.com/inikulin/parse5
) (**MIT**)

[parse5@5.1.0](https://github.com/inikulin/parse5
) (**MIT**)

[parseurl@1.3.3](https://github.com/pillarjs/parseurl
) (**MIT**)

[pascal-case@3.1.1](https://github.com/blakeembrey/change-case
) (**MIT**)

[pascalcase@0.1.1](https://github.com/jonschlinkert/pascalcase
) (**MIT**)

[path-browserify@0.0.1](https://github.com/substack/path-browserify
) (**MIT**)

[path-dirname@1.0.2](https://github.com/es128/path-dirname
) (**MIT**)

[path-exists@2.1.0](https://github.com/sindresorhus/path-exists
) (**MIT**)

[path-exists@3.0.0](https://github.com/sindresorhus/path-exists
) (**MIT**)

[path-exists@4.0.0](https://github.com/sindresorhus/path-exists
) (**MIT**)

[path-is-absolute@1.0.1](https://github.com/sindresorhus/path-is-absolute
) (**MIT**)

[path-is-inside@1.0.2](https://github.com/domenic/path-is-inside
) (**(WTFPL OR MIT)**)

[path-key@2.0.1](https://github.com/sindresorhus/path-key
) (**MIT**)

[path-key@3.1.1](https://github.com/sindresorhus/path-key
) (**MIT**)

[path-parse@1.0.6](https://github.com/jbgutierrez/path-parse
) (**MIT**)

[path-to-regexp@0.1.7](https://github.com/component/path-to-regexp
) (**MIT**)

[path-to-regexp@1.8.0](https://github.com/pillarjs/path-to-regexp
) (**MIT**)

[path-type@1.1.0](https://github.com/sindresorhus/path-type
) (**MIT**)

[path-type@2.0.0](https://github.com/sindresorhus/path-type
) (**MIT**)

[path-type@3.0.0](https://github.com/sindresorhus/path-type
) (**MIT**)

[path-type@4.0.0](https://github.com/sindresorhus/path-type
) (**MIT**)

[pbf@3.2.1](https://github.com/mapbox/pbf
) (**BSD-3-Clause**)

[pbkdf2@3.0.17](https://github.com/crypto-browserify/pbkdf2
) (**MIT**)

[performance-now@2.1.0](https://github.com/braveg1rl/performance-now
) (**MIT**)

[picomatch@2.2.1](https://github.com/micromatch/picomatch
) (**MIT**)

[pify@2.3.0](https://github.com/sindresorhus/pify
) (**MIT**)

[pify@3.0.0](https://github.com/sindresorhus/pify
) (**MIT**)

[pify@4.0.1](https://github.com/sindresorhus/pify
) (**MIT**)

[pinkie-promise@2.0.1](https://github.com/floatdrop/pinkie-promise
) (**MIT**)

[pinkie@2.0.4](https://github.com/floatdrop/pinkie
) (**MIT**)

[pirates@4.0.1](https://github.com/ariporad/pirates
) (**MIT**)

[pkg-dir@1.0.0](https://github.com/sindresorhus/pkg-dir
) (**MIT**)

[pkg-dir@2.0.0](https://github.com/sindresorhus/pkg-dir
) (**MIT**)

[pkg-dir@3.0.0](https://github.com/sindresorhus/pkg-dir
) (**MIT**)

[pkg-dir@4.2.0](https://github.com/sindresorhus/pkg-dir
) (**MIT**)

[pkg-up@3.1.0](https://github.com/sindresorhus/pkg-up
) (**MIT**)

[pn@1.1.0](https://github.com/cscott/node-pn
) (**MIT**)

[pnp-webpack-plugin@1.6.0](https://github.com/arcanis/pnp-webpack-plugin
) (**MIT**)

[popper.js@1.16.1](https://github.com/FezVrasta/popper.js
) (**MIT**)

[portfinder@1.0.25](https://github.com/indexzero/node-portfinder
) (**MIT**)

[posix-character-classes@0.1.1](https://github.com/jonschlinkert/posix-character-classes
) (**MIT**)

[postcss-attribute-case-insensitive@4.0.2](https://github.com/Semigradsky/postcss-attribute-case-insensitive
) (**MIT**)

[postcss-browser-comments@3.0.0](https://github.com/csstools/postcss-browser-comments
) (**CC0-1.0**)

[postcss-calc@7.0.2](https://github.com/postcss/postcss-calc
) (**MIT**)

[postcss-color-functional-notation@2.0.1](https://github.com/jonathantneal/postcss-color-functional-notation
) (**CC0-1.0**)

[postcss-color-gray@5.0.0](https://github.com/postcss/postcss-color-gray
) (**ISC**)

[postcss-color-hex-alpha@5.0.3](https://github.com/postcss/postcss-color-hex-alpha
) (**MIT**)

[postcss-color-mod-function@3.0.3](https://github.com/jonathantneal/postcss-color-mod-function
) (**CC0-1.0**)

[postcss-color-rebeccapurple@4.0.1](https://github.com/postcss/postcss-color-rebeccapurple
) (**MIT**)

[postcss-colormin@4.0.3](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-convert-values@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-custom-media@7.0.8](https://github.com/postcss/postcss-custom-media
) (**MIT**)

[postcss-custom-properties@8.0.11](https://github.com/postcss/postcss-custom-properties
) (**MIT**)

[postcss-custom-selectors@5.1.2](https://github.com/postcss/postcss-custom-selectors
) (**MIT**)

[postcss-dir-pseudo-class@5.0.0](https://github.com/jonathantneal/postcss-dir-pseudo-class
) (**CC0-1.0**)

[postcss-discard-comments@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-discard-duplicates@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-discard-empty@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-discard-overridden@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-double-position-gradients@1.0.0](https://github.com/jonathantneal/postcss-double-position-gradients
) (**CC0-1.0**)

[postcss-env-function@2.0.2](https://github.com/jonathantneal/postcss-env-function
) (**CC0-1.0**)

[postcss-flexbugs-fixes@4.1.0](https://github.com/luisrudge/postcss-flexbugs-fixes
) (**MIT**)

[postcss-focus-visible@4.0.0](https://github.com/jonathantneal/postcss-focus-visible
) (**CC0-1.0**)

[postcss-focus-within@3.0.0](https://github.com/jonathantneal/postcss-focus-within
) (**CC0-1.0**)

[postcss-font-variant@4.0.0](https://github.com/postcss/postcss-font-variant
) (**MIT**)

[postcss-gap-properties@2.0.0](https://github.com/jonathantneal/postcss-gap-properties
) (**CC0-1.0**)

[postcss-image-set-function@3.0.1](https://github.com/jonathantneal/postcss-image-set-function
) (**CC0-1.0**)

[postcss-initial@3.0.2](https://github.com/maximkoretskiy/postcss-initial
) (**MIT**)

[postcss-lab-function@2.0.1](https://github.com/jonathantneal/postcss-lab-function
) (**CC0-1.0**)

[postcss-load-config@2.1.0](https://github.com/michael-ciniawsky/postcss-load-config
) (**MIT**)

[postcss-loader@3.0.0](https://github.com/postcss/postcss-loader
) (**MIT**)

[postcss-logical@3.0.0](https://github.com/jonathantneal/postcss-logical
) (**CC0-1.0**)

[postcss-media-minmax@4.0.0](https://github.com/postcss/postcss-media-minmax
) (**MIT**)

[postcss-merge-longhand@4.0.11](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-merge-rules@4.0.3](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-minify-font-values@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-minify-gradients@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-minify-params@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-minify-selectors@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-modules-extract-imports@2.0.0](https://github.com/css-modules/postcss-modules-extract-imports
) (**ISC**)

[postcss-modules-local-by-default@3.0.2](https://github.com/css-modules/postcss-modules-local-by-default
) (**MIT**)

[postcss-modules-scope@2.1.1](https://github.com/css-modules/postcss-modules-scope
) (**ISC**)

[postcss-modules-values@3.0.0](https://github.com/css-modules/postcss-modules-values
) (**ISC**)

[postcss-nesting@7.0.1](https://github.com/jonathantneal/postcss-nesting
) (**CC0-1.0**)

[postcss-normalize-charset@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-display-values@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-positions@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-repeat-style@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-string@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-timing-functions@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-unicode@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-url@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize-whitespace@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-normalize@8.0.1](https://github.com/csstools/postcss-normalize
) (**CC0-1.0**)

[postcss-ordered-values@4.1.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-overflow-shorthand@2.0.0](https://github.com/jonathantneal/postcss-overflow-shorthand
) (**CC0-1.0**)

[postcss-page-break@2.0.0](https://github.com/shrpne/postcss-page-break
) (**MIT**)

[postcss-place@4.0.1](https://github.com/jonathantneal/postcss-place
) (**CC0-1.0**)

[postcss-preset-env@6.7.0](https://github.com/csstools/postcss-preset-env
) (**CC0-1.0**)

[postcss-pseudo-class-any-link@6.0.0](https://github.com/jonathantneal/postcss-pseudo-class-any-link
) (**CC0-1.0**)

[postcss-reduce-initial@4.0.3](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-reduce-transforms@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-replace-overflow-wrap@3.0.0](https://github.com/MattDiMu/postcss-replace-overflow-wrap
) (**MIT**)

[postcss-safe-parser@4.0.1](https://github.com/postcss/postcss-safe-parser
) (**MIT**)

[postcss-selector-matches@4.0.0](https://github.com/postcss/postcss-selector-matches
) (**MIT**)

[postcss-selector-not@4.0.0](https://github.com/postcss/postcss-selector-not
) (**MIT**)

[postcss-selector-parser@3.1.2](https://github.com/postcss/postcss-selector-parser
) (**MIT**)

[postcss-selector-parser@5.0.0](https://github.com/postcss/postcss-selector-parser
) (**MIT**)

[postcss-selector-parser@6.0.2](https://github.com/postcss/postcss-selector-parser
) (**MIT**)

[postcss-svgo@4.0.2](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-unique-selectors@4.0.1](https://github.com/cssnano/cssnano
) (**MIT**)

[postcss-value-parser@3.3.1](https://github.com/TrySound/postcss-value-parser
) (**MIT**)

[postcss-value-parser@4.0.3](https://github.com/TrySound/postcss-value-parser
) (**MIT**)

[postcss-values-parser@2.0.1](https://github.com/lesshint/postcss-values-parser
) (**MIT**)

[postcss@7.0.21](https://github.com/postcss/postcss
) (**MIT**)

[postcss@7.0.27](https://www.postgresql.org/about/licence/) (**MIT**)

[PostgreSQL](https://github.com/postcss/postcss
) (**PostgreSQL**)

[potpack@1.0.1](https://github.com/mapbox/potpack
) (**ISC**)

[prelude-ls@1.1.2](https://github.com/gkz/prelude-ls
) (**MIT**)

[prepend-http@1.0.4](https://github.com/sindresorhus/prepend-http
) (**MIT**)

[prettier-linter-helpers@1.0.0](https://github.com/prettier/prettier-linter-helpers
) (**MIT**)

[prettier@1.19.1](https://github.com/prettier/prettier
) (**MIT**)

[pretty-bytes@5.3.0](https://github.com/sindresorhus/pretty-bytes
) (**MIT**)

[pretty-error@2.1.1](https://github.com/AriaMinaei/pretty-error
) (**MIT**)

[pretty-format@24.9.0](https://github.com/facebook/jest
) (**MIT**)

[pretty-format@25.1.0](https://github.com/facebook/jest
) (**MIT**)

[private@0.1.8](https://github.com/benjamn/private
) (**MIT**)

[process-nextick-args@2.0.1](https://github.com/calvinmetcalf/process-nextick-args
) (**MIT**)

[process@0.11.10](https://github.com/shtylman/node-process
) (**MIT**)

[progress@2.0.3](https://github.com/visionmedia/node-progress
) (**MIT**)

[promise-inflight@1.0.1](https://github.com/iarna/promise-inflight
) (**ISC**)

[promise@7.3.1](https://github.com/then/promise
) (**MIT**)

[promise@8.1.0](https://github.com/then/promise
) (**MIT**)

[prompts@2.3.1](https://github.com/terkelg/prompts
) (**MIT**)

[prop-types-exact@1.2.0](https://github.com/airbnb/prop-types-exact
) (**MIT**)

[prop-types@15.7.2](https://github.com/facebook/prop-types
) (**MIT**)

[protocol-buffers-schema@3.4.0](https://github.com/mafintosh/protocol-buffers-schema
) (**MIT**)

[proxy-addr@2.0.6](https://github.com/jshttp/proxy-addr
) (**MIT**)

[prr@1.0.1](https://github.com/rvagg/prr
) (**MIT**)

[pseudomap@1.0.2](https://github.com/isaacs/pseudomap
) (**ISC**)

[psl@1.7.0](https://github.com/lupomontero/psl
) (**MIT**)

[public-encrypt@4.0.3](https://github.com/crypto-browserify/publicEncrypt
) (**MIT**)

[pump@2.0.1](https://github.com/mafintosh/pump
) (**MIT**)

[pump@3.0.0](https://github.com/mafintosh/pump
) (**MIT**)

[pumpify@1.5.1](https://github.com/mafintosh/pumpify
) (**MIT**)

[punycode@1.3.2](https://github.com/bestiejs/punycode.js
) (**MIT**)

[punycode@1.4.1](https://github.com/bestiejs/punycode.js
) (**MIT**)

[punycode@2.1.1](https://github.com/bestiejs/punycode.js
) (**MIT**)

[q@1.5.1](https://github.com/kriskowal/q
) (**MIT**)

[qs@6.5.2](https://github.com/ljharb/qs
) (**BSD-3-Clause**)

[qs@6.7.0](https://github.com/ljharb/qs
) (**BSD-3-Clause**)

[query-string@4.3.4](https://github.com/sindresorhus/query-string
) (**MIT**)

[querystring-es3@0.2.1](https://github.com/mike-spainhower/querystring
) (**MIT**)

[querystring@0.2.0](https://github.com/Gozala/querystring
) (**MIT**)

[querystringify@2.1.1](https://github.com/unshiftio/querystringify
) (**MIT**)

[quickselect@2.0.0](
) (**ISC**)

[raf@3.4.1](https://github.com/chrisdickinson/raf
) (**MIT**)

[railroad-diagrams@1.0.0](https://github.com/tabatkins/railroad-diagrams
) (**CC0-1.0**)

[randexp@0.4.6](https://github.com/fent/randexp.js
) (**MIT**)

[randombytes@2.1.0](https://github.com/crypto-browserify/randombytes
) (**MIT**)

[randomfill@1.0.4](https://github.com/crypto-browserify/randomfill
) (**MIT**)

[range-parser@1.2.1](https://github.com/jshttp/range-parser
) (**MIT**)

[raw-body@2.4.0](https://github.com/stream-utils/raw-body
) (**MIT**)

[rc@1.2.8](https://github.com/dominictarr/rc
) (**(BSD-2-Clause OR MIT OR Apache-2.0)**)

[react-app-polyfill@1.0.6](https://github.com/facebook/create-react-app
) (**MIT**)

[react-dev-utils@10.2.0](https://github.com/facebook/create-react-app
) (**MIT**)

[react-dom@16.13.0](https://github.com/facebook/react
) (**MIT**)

[react-error-overlay@6.0.6](https://github.com/facebook/create-react-app
) (**MIT**)

[react-facebook-login@4.1.1](https://github.com/keppelen/react-facebook-login
) (**MIT**)

[react-html-parser@2.0.2](https://github.com/wrakky/react-html-parser
) (**MIT**)

[react-is@16.13.0](https://github.com/facebook/react
) (**MIT**)

[react-map-gl@5.2.3](https://github.com/uber/react-map-gl
) (**MIT**)

[react-redux@7.2.0](https://github.com/reduxjs/react-redux
) (**MIT**)

[react-router-dom@5.1.2](https://github.com/ReactTraining/react-router
) (**MIT**)

[react-router@5.1.2](https://github.com/ReactTraining/react-router
) (**MIT**)

[react-scripts@3.4.0](https://github.com/facebook/create-react-app
) (**MIT**)

[react-share@4.0.1](https://github.com/nygardk/react-share
) (**MIT**)

[react-sortable-hoc@1.11.0](https://github.com/clauderic/react-sortable-hoc
) (**MIT**)

[react-splitter-layout@4.0.0](https://github.com/zesik/react-splitter-layout
) (**MIT**)

[react-test-renderer@16.13.0](https://github.com/facebook/react
) (**MIT**)

[react-transition-group@4.3.0](https://github.com/reactjs/react-transition-group
) (**BSD-3-Clause**)

[react-virtualized-auto-sizer@1.0.2](https://github.com/bvaughn/react-virtualized-auto-sizer
) (**MIT**)

[react@16.13.0](https://github.com/facebook/react
) (**MIT**)

[read-pkg-up@1.0.1](https://github.com/sindresorhus/read-pkg-up
) (**MIT**)

[read-pkg-up@2.0.0](https://github.com/sindresorhus/read-pkg-up
) (**MIT**)

[read-pkg-up@4.0.0](https://github.com/sindresorhus/read-pkg-up
) (**MIT**)

[read-pkg@1.1.0](https://github.com/sindresorhus/read-pkg
) (**MIT**)

[read-pkg@2.0.0](https://github.com/sindresorhus/read-pkg
) (**MIT**)

[read-pkg@3.0.0](https://github.com/sindresorhus/read-pkg
) (**MIT**)

[readable-stream@2.3.6](https://github.com/nodejs/readable-stream
) (**MIT**)

[readable-stream@2.3.7](https://github.com/nodejs/readable-stream
) (**MIT**)

[readable-stream@3.6.0](https://github.com/nodejs/readable-stream
) (**MIT**)

[readdirp@2.2.1](https://github.com/paulmillr/readdirp
) (**MIT**)

[readdirp@3.3.0](https://github.com/paulmillr/readdirp
) (**MIT**)

[realpath-native@1.1.0](https://github.com/SimenB/realpath-native
) (**MIT**)

[recursive-readdir@2.2.2](https://github.com/jergason/recursive-readdir
) (**MIT**)

[redent@1.0.0](https://github.com/sindresorhus/redent
) (**MIT**)

[redent@3.0.0](https://github.com/sindresorhus/redent
) (**MIT**)

[redeyed@0.4.4](https://github.com/thlorenz/redeyed
) (**MIT**)

[redux-devtools-extension@2.13.8](https://github.com/zalmoxisus/redux-devtools-extension
) (**MIT**)

[redux-persist@6.0.0](https://github.com/rt2zz/redux-persist
) (**MIT**)

[redux-thunk@2.3.0](https://github.com/reduxjs/redux-thunk
) (**MIT**)

[redux@4.0.5](https://github.com/reduxjs/redux
) (**MIT**)

[reflect.ownkeys@0.2.0](https://github.com/glenjamin/Reflect.ownKeys
) (**MIT**)

[regenerate-unicode-properties@8.1.0](https://github.com/mathiasbynens/regenerate-unicode-properties
) (**MIT**)

[regenerate@1.4.0](https://github.com/mathiasbynens/regenerate
) (**MIT**)

[regenerator-runtime@0.11.1](https://github.com/facebook/regenerator/tree/master/packages/regenerator-runtime
) (**MIT**)

[regenerator-runtime@0.13.4](https://github.com/facebook/regenerator/tree/master/packages/regenerator-runtime
) (**MIT**)

[regenerator-transform@0.14.2](https://github.com/facebook/regenerator/tree/master/packages/regenerator-transform
) (**MIT**)

[regex-not@1.0.2](https://github.com/jonschlinkert/regex-not
) (**MIT**)

[regex-parser@2.2.10](https://github.com/IonicaBizau/regex-parser.js
) (**MIT**)

[regexp.prototype.flags@1.3.0](https://github.com/es-shims/RegExp.prototype.flags
) (**MIT**)

[regexpp@2.0.1](https://github.com/mysticatea/regexpp
) (**MIT**)

[regexpp@3.0.0](https://github.com/mysticatea/regexpp
) (**MIT**)

[regexpu-core@4.6.0](https://github.com/mathiasbynens/regexpu-core
) (**MIT**)

[regjsgen@0.5.1](https://github.com/bnjmnt4n/regjsgen
) (**MIT**)

[regjsparser@0.6.4](https://github.com/jviereck/regjsparser
) (**BSD-2-Clause**)

[relateurl@0.2.7](https://github.com/stevenvachon/relateurl
) (**MIT**)

[remove-trailing-separator@1.1.0](https://github.com/darsain/remove-trailing-separator
) (**ISC**)

[renderkid@2.0.3](https://github.com/AriaMinaei/RenderKid
) (**MIT**)

[repeat-element@1.1.3](https://github.com/jonschlinkert/repeat-element
) (**MIT**)

[repeat-string@1.6.1](https://github.com/jonschlinkert/repeat-string
) (**MIT**)

[repeating@2.0.1](https://github.com/sindresorhus/repeating
) (**MIT**)

[request-promise-core@1.1.3](https://github.com/request/promise-core
) (**ISC**)

[request-promise-native@1.0.8](https://github.com/request/request-promise-native
) (**ISC**)

[request@2.88.2](https://github.com/request/request
) (**Apache-2.0**)

[require-directory@2.1.1](https://github.com/troygoode/node-require-directory
) (**MIT**)

[require-main-filename@1.0.1](https://github.com/yargs/require-main-filename
) (**ISC**)

[require-main-filename@2.0.0](https://github.com/yargs/require-main-filename
) (**ISC**)

[requires-port@1.0.0](https://github.com/unshiftio/requires-port
) (**MIT**)

[resolve-cwd@2.0.0](https://github.com/sindresorhus/resolve-cwd
) (**MIT**)

[resolve-from@3.0.0](https://github.com/sindresorhus/resolve-from
) (**MIT**)

[resolve-from@4.0.0](https://github.com/sindresorhus/resolve-from
) (**MIT**)

[resolve-pathname@3.0.0](https://github.com/mjackson/resolve-pathname
) (**MIT**)

[resolve-protobuf-schema@2.1.0](https://github.com/mafintosh/resolve-protobuf-schema
) (**MIT**)

[resolve-url-loader@3.1.1](https://github.com/bholloway/resolve-url-loader
) (**MIT**)

[resolve-url@0.2.1](https://github.com/lydell/resolve-url
) (**MIT**)

[resolve@1.1.7](https://github.com/substack/node-resolve
) (**MIT**)

[resolve@1.15.0](https://github.com/browserify/resolve
) (**MIT**)

[resolve@1.15.1](https://github.com/browserify/resolve
) (**MIT**)

[restore-cursor@3.1.0](https://github.com/sindresorhus/restore-cursor
) (**MIT**)

[ret@0.1.15](https://github.com/fent/ret.js
) (**MIT**)

[retry@0.12.0](https://github.com/tim-kos/node-retry
) (**MIT**)

[rework-visit@1.0.0](
) (**MIT**)

[rework@1.0.1](https://github.com/reworkcss/rework
) (**MIT***)

[rgb-regex@1.0.1](https://github.com/regexps/rgb-regex
) (**MIT**)

[rgba-regex@1.0.0](https://github.com/johnotander/rgba-regex
) (**MIT**)

[rifm@0.7.0](https://github.com/istarkov/rifm
) (**MIT**)

[rimraf@2.6.3](https://github.com/isaacs/rimraf
) (**ISC**)

[rimraf@2.7.1](https://github.com/isaacs/rimraf
) (**ISC**)

[ripemd160@2.0.2](https://github.com/crypto-browserify/ripemd160
) (**MIT**)

[rst-selector-parser@2.2.3](https://github.com/aweary/rst-selector-parser
) (**BSD-3-Clause**)

[rsvp@4.8.5](https://github.com/tildeio/rsvp.js
) (**MIT**)

[run-async@2.4.0](https://github.com/SBoudrias/run-async
) (**MIT**)

[run-queue@1.0.3](https://github.com/iarna/run-queue
) (**ISC**)

[rw@1.3.3](https://github.com/mbostock/rw
) (**BSD-3-Clause**)

[rxjs@6.5.4](https://github.com/reactivex/rxjs
) (**Apache-2.0**)

[safe-buffer@5.1.2](https://github.com/feross/safe-buffer
) (**MIT**)

[safe-buffer@5.2.0](https://github.com/feross/safe-buffer
) (**MIT**)

[safe-regex@1.1.0](https://github.com/substack/safe-regex
) (**MIT**)

[safer-buffer@2.1.2](https://github.com/ChALkeR/safer-buffer
) (**MIT**)

[sane@4.1.0](https://github.com/amasad/sane
) (**MIT**)

[sanitize.css@10.0.0](https://github.com/csstools/sanitize.css
) (**CC0-1.0**)

[sass-graph@2.2.4](https://github.com/xzyfer/sass-graph
) (**MIT**)

[sass-loader@8.0.2](https://github.com/webpack-contrib/sass-loader
) (**MIT**)

[sax@1.2.4](https://github.com/isaacs/sax-js
) (**ISC**)

[saxes@3.1.11](https://github.com/lddubeau/saxes
) (**ISC**)

[scheduler@0.19.0](https://github.com/facebook/react
) (**MIT**)

[schema-utils@1.0.0](https://github.com/webpack-contrib/schema-utils
) (**MIT**)

[schema-utils@2.6.5](https://github.com/webpack/schema-utils
) (**MIT**)

[scss-tokenizer@0.2.3](https://github.com/sasstools/scss-tokenizer
) (**MIT**)

[select-hose@2.0.0](https://github.com/indutny/select-hose
) (**MIT**)

[selfsigned@1.10.7](https://github.com/jfromaniello/selfsigned
) (**MIT**)

[semver@5.3.0](https://github.com/npm/node-semver
) (**ISC**)

[semver@5.7.1](https://github.com/npm/node-semver
) (**ISC**)

[semver@6.3.0](https://github.com/npm/node-semver
) (**ISC**)

[semver@7.0.0](https://github.com/npm/node-semver
) (**ISC**)

[send@0.17.1](https://github.com/pillarjs/send
) (**MIT**)

[serialize-javascript@2.1.2](https://github.com/yahoo/serialize-javascript
) (**BSD-3-Clause**)

[serve-index@1.9.1](https://github.com/expressjs/serve-index
) (**MIT**)

[serve-static@1.14.1](https://github.com/expressjs/serve-static
) (**MIT**)

[set-blocking@2.0.0](https://github.com/yargs/set-blocking
) (**ISC**)

[set-value@2.0.1](https://github.com/jonschlinkert/set-value
) (**MIT**)

[setimmediate@1.0.5](https://github.com/YuzuJS/setImmediate
) (**MIT**)

[setprototypeof@1.1.0](https://github.com/wesleytodd/setprototypeof
) (**ISC**)

[setprototypeof@1.1.1](https://github.com/wesleytodd/setprototypeof
) (**ISC**)

[sha.js@2.4.11](https://github.com/crypto-browserify/sha.js
) (**(MIT AND BSD-3-Clause)**)

[shallow-clone@0.1.2](https://github.com/jonschlinkert/shallow-clone
) (**MIT**)

[shallow-clone@3.0.1](https://github.com/jonschlinkert/shallow-clone
) (**MIT**)

[sharkdown@0.1.1](
) (**BSD-2-Clause**)

[shebang-command@1.2.0](https://github.com/kevva/shebang-command
) (**MIT**)

[shebang-command@2.0.0](https://github.com/kevva/shebang-command
) (**MIT**)

[shebang-regex@1.0.0](https://github.com/sindresorhus/shebang-regex
) (**MIT**)

[shebang-regex@3.0.0](https://github.com/sindresorhus/shebang-regex
) (**MIT**)

[shell-quote@1.7.2](https://github.com/substack/node-shell-quote
) (**MIT**)

[shellwords@0.1.1](https://github.com/jimmycuadra/shellwords
) (**MIT**)

[side-channel@1.0.2](https://github.com/ljharb/side-channel
) (**MIT**)

[signal-exit@3.0.2](https://github.com/tapjs/signal-exit
) (**ISC**)

[simple-swizzle@0.2.2](https://github.com/qix-/node-simple-swizzle
) (**MIT**)

[sisteransi@1.0.4](https://github.com/terkelg/sisteransi
) (**MIT**)

[slash@1.0.0](https://github.com/sindresorhus/slash
) (**MIT**)

[slash@2.0.0](https://github.com/sindresorhus/slash
) (**MIT**)

[slash@3.0.0](https://github.com/sindresorhus/slash
) (**MIT**)

[slice-ansi@2.1.0](https://github.com/chalk/slice-ansi
) (**MIT**)

[snapdragon-node@2.1.1](https://github.com/jonschlinkert/snapdragon-node
) (**MIT**)

[snapdragon-util@3.0.1](https://github.com/jonschlinkert/snapdragon-util
) (**MIT**)

[snapdragon@0.8.2](https://github.com/jonschlinkert/snapdragon
) (**MIT**)

[sockjs-client@1.4.0](https://github.com/sockjs/sockjs-client
) (**MIT**)

[sockjs@0.3.19](https://github.com/sockjs/sockjs-node
) (**MIT**)

[sort-keys@1.1.2](https://github.com/sindresorhus/sort-keys
) (**MIT**)

[source-list-map@2.0.1](https://github.com/webpack/source-list-map
) (**MIT**)

[source-map-resolve@0.5.3](https://github.com/lydell/source-map-resolve
) (**MIT**)

[source-map-support@0.5.16](https://github.com/evanw/node-source-map-support
) (**MIT**)

[source-map-url@0.4.0](https://github.com/lydell/source-map-url
) (**MIT**)

[source-map@0.4.4](https://github.com/mozilla/source-map
) (**BSD-3-Clause**)

[source-map@0.5.7](https://github.com/mozilla/source-map
) (**BSD-3-Clause**)

[source-map@0.6.1](https://github.com/mozilla/source-map
) (**BSD-3-Clause**)

[spdx-correct@3.1.0](https://github.com/jslicense/spdx-correct.js
) (**Apache-2.0**)

[spdx-exceptions@2.2.0](https://github.com/kemitchell/spdx-exceptions.json
) (**CC-BY-3.0**)

[spdx-expression-parse@3.0.0](https://github.com/jslicense/spdx-expression-parse.js
) (**MIT**)

[spdx-license-ids@3.0.5](https://github.com/shinnn/spdx-license-ids
) (**CC0-1.0**)

[spdy-transport@3.0.0](https://github.com/spdy-http2/spdy-transport
) (**MIT**)

[spdy@4.0.1](https://github.com/indutny/node-spdy
) (**MIT**)

[split-string@3.1.0](https://github.com/jonschlinkert/split-string
) (**MIT**)

[split@0.2.10](https://github.com/dominictarr/split
) (**MIT***)

[sprintf-js@1.0.3](https://github.com/alexei/sprintf.js
) (**BSD-3-Clause**)

[sshpk@1.16.1](https://github.com/joyent/node-sshpk
) (**MIT**)

[ssri@6.0.1](https://github.com/zkat/ssri
) (**ISC**)

[ssri@7.1.0](https://github.com/npm/ssri
) (**ISC**)

[stable@0.1.8](https://github.com/Two-Screen/stable
) (**MIT**)

[stack-utils@1.0.2](https://github.com/tapjs/stack-utils
) (**MIT**)

[static-extend@0.1.2](https://github.com/jonschlinkert/static-extend
) (**MIT**)

[statuses@1.5.0](https://github.com/jshttp/statuses
) (**MIT**)

[stdout-stream@1.4.1](https://github.com/mafintosh/stdout-stream
) (**MIT**)

[stealthy-require@1.1.1](https://github.com/analog-nico/stealthy-require
) (**ISC**)

[stream-browserify@2.0.2](https://github.com/browserify/stream-browserify
) (**MIT**)

[stream-each@1.2.3](https://github.com/mafintosh/stream-each
) (**MIT**)

[stream-http@2.8.3](https://github.com/jhiesey/stream-http
) (**MIT**)

[stream-shift@1.0.1](https://github.com/mafintosh/stream-shift
) (**MIT**)

[strict-uri-encode@1.1.0](https://github.com/kevva/strict-uri-encode
) (**MIT**)

[string-length@2.0.0](https://github.com/sindresorhus/string-length
) (**MIT**)

[string-length@3.1.0](https://github.com/sindresorhus/string-length
) (**MIT**)

[string-width@1.0.2](https://github.com/sindresorhus/string-width
) (**MIT**)

[string-width@2.1.1](https://github.com/sindresorhus/string-width
) (**MIT**)

[string-width@3.1.0](https://github.com/sindresorhus/string-width
) (**MIT**)

[string-width@4.2.0](https://github.com/sindresorhus/string-width
) (**MIT**)

[string.prototype.matchall@4.0.2](https://github.com/ljharb/String.prototype.matchAll
) (**MIT**)

[string.prototype.trim@1.2.1](https://github.com/es-shims/String.prototype.trim
) (**MIT**)

[string.prototype.trimleft@2.1.1](https://github.com/es-shims/String.prototype.trimLeft
) (**MIT**)

[string.prototype.trimright@2.1.1](https://github.com/es-shims/String.prototype.trimRight
) (**MIT**)

[string_decoder@1.1.1](https://github.com/nodejs/string_decoder
) (**MIT**)

[string_decoder@1.3.0](https://github.com/nodejs/string_decoder
) (**MIT**)

[stringify-object@3.3.0](https://github.com/yeoman/stringify-object
) (**BSD-2-Clause**)

[strip-ansi@3.0.1](https://github.com/chalk/strip-ansi
) (**MIT**)

[strip-ansi@4.0.0](https://github.com/chalk/strip-ansi
) (**MIT**)

[strip-ansi@5.2.0](https://github.com/chalk/strip-ansi
) (**MIT**)

[strip-ansi@6.0.0](https://github.com/chalk/strip-ansi
) (**MIT**)

[strip-bom@2.0.0](https://github.com/sindresorhus/strip-bom
) (**MIT**)

[strip-bom@3.0.0](https://github.com/sindresorhus/strip-bom
) (**MIT**)

[strip-comments@1.0.2](https://github.com/jonschlinkert/strip-comments
) (**MIT**)

[strip-eof@1.0.0](https://github.com/sindresorhus/strip-eof
) (**MIT**)

[strip-indent@1.0.1](https://github.com/sindresorhus/strip-indent
) (**MIT**)

[strip-indent@3.0.0](https://github.com/sindresorhus/strip-indent
) (**MIT**)

[strip-json-comments@2.0.1](https://github.com/sindresorhus/strip-json-comments
) (**MIT**)

[strip-json-comments@3.0.1](https://github.com/sindresorhus/strip-json-comments
) (**MIT**)

[style-loader@0.23.1](https://github.com/webpack-contrib/style-loader
) (**MIT**)

[stylehacks@4.0.3](https://github.com/cssnano/cssnano
) (**MIT**)

[supercluster@7.0.0](https://github.com/mapbox/supercluster
) (**ISC**)

[supports-color@2.0.0](https://github.com/chalk/supports-color
) (**MIT**)

[supports-color@5.5.0](https://github.com/chalk/supports-color
) (**MIT**)

[supports-color@6.1.0](https://github.com/chalk/supports-color
) (**MIT**)

[supports-color@7.1.0](https://github.com/chalk/supports-color
) (**MIT**)

[svg-parser@2.0.4](https://github.com/Rich-Harris/svg-parser
) (**MIT**)

[svgo@1.3.2](https://github.com/svg/svgo
) (**MIT**)

[symbol-observable@1.2.0](https://github.com/blesh/symbol-observable
) (**MIT**)

[symbol-tree@3.2.4](https://github.com/jsdom/js-symbol-tree
) (**MIT**)

[table@5.4.6](https://github.com/gajus/table
) (**BSD-3-Clause**)

[tapable@1.1.3](https://github.com/webpack/tapable
) (**MIT**)

[tar@2.2.2](https://github.com/isaacs/node-tar
) (**ISC**)

[tar@4.4.13](https://github.com/npm/node-tar
) (**ISC**)

[terser-webpack-plugin@1.4.3](https://github.com/webpack-contrib/terser-webpack-plugin
) (**MIT**)

[terser-webpack-plugin@2.3.4](https://github.com/webpack-contrib/terser-webpack-plugin
) (**MIT**)

[terser@4.6.6](https://github.com/terser/terser
) (**BSD-2-Clause**)

[test-exclude@5.2.3](https://github.com/istanbuljs/istanbuljs
) (**ISC**)

[text-table@0.2.0](https://github.com/substack/text-table
) (**MIT**)

[throat@4.1.0](https://github.com/ForbesLindesay/throat
) (**MIT**)

[through2@2.0.5](https://github.com/rvagg/through2
) (**MIT**)

[through@2.3.8](https://github.com/dominictarr/through
) (**MIT**)

[thunky@1.1.0](https://github.com/mafintosh/thunky
) (**MIT**)

[timers-browserify@2.0.11](https://github.com/jryans/timers-browserify
) (**MIT**)

[timsort@0.3.0](https://github.com/mziccard/node-timsort
) (**MIT**)

[tiny-invariant@1.1.0](https://github.com/alexreardon/tiny-invariant
) (**MIT**)

[tiny-warning@1.0.3](https://github.com/alexreardon/tiny-warning
) (**MIT**)

[tinyqueue@2.0.3](https://github.com/mourner/tinyqueue
) (**ISC**)

[tmp@0.0.33](https://github.com/raszi/node-tmp
) (**MIT**)

[tmpl@1.0.4](https://github.com/daaku/nodejs-tmpl
) (**BSD-3-Clause**)

[to-arraybuffer@1.0.1](https://github.com/jhiesey/to-arraybuffer
) (**MIT**)

[to-fast-properties@2.0.0](https://github.com/sindresorhus/to-fast-properties
) (**MIT**)

[to-object-path@0.3.0](https://github.com/jonschlinkert/to-object-path
) (**MIT**)

[to-regex-range@2.1.1](https://github.com/micromatch/to-regex-range
) (**MIT**)

[to-regex-range@5.0.1](https://github.com/micromatch/to-regex-range
) (**MIT**)

[to-regex@3.0.2](https://github.com/jonschlinkert/to-regex
) (**MIT**)

[toidentifier@1.0.0](https://github.com/component/toidentifier
) (**MIT**)

[tough-cookie@2.5.0](https://github.com/salesforce/tough-cookie
) (**BSD-3-Clause**)

[tr46@1.0.1](https://github.com/Sebmaster/tr46.js
) (**MIT**)

[trim-newlines@1.0.0](https://github.com/sindresorhus/trim-newlines
) (**MIT**)

[true-case-path@1.0.3](https://github.com/barsh/true-case-path
) (**Apache-2.0**)

[ts-pnp@1.1.5](https://github.com/arcanis/ts-pnp
) (**MIT**)

[ts-react-google-login-component@1.1.2](
) (**MIT**)

[tslib@1.11.1](https://github.com/Microsoft/tslib
) (**Apache-2.0**)

[tsutils@3.17.1](https://github.com/ajafff/tsutils
) (**MIT**)

[tty-browserify@0.0.0](https://github.com/substack/tty-browserify
) (**MIT**)

[tunnel-agent@0.6.0](https://github.com/mikeal/tunnel-agent
) (**Apache-2.0**)

[tweetnacl@0.14.5](https://github.com/dchest/tweetnacl-js
) (**Unlicense**)

[type-check@0.3.2](https://github.com/gkz/type-check
) (**MIT**)

[type-fest@0.11.0](https://github.com/sindresorhus/type-fest
) (**(MIT OR CC0-1.0)**)

[type-fest@0.8.1](https://github.com/sindresorhus/type-fest
) (**(MIT OR CC0-1.0)**)

[type-is@1.6.18](https://github.com/jshttp/type-is
) (**MIT**)

[type@1.2.0](https://github.com/medikoo/type
) (**ISC**)

[type@2.0.0](https://github.com/medikoo/type
) (**ISC**)

[typedarray@0.0.6](https://github.com/substack/typedarray
) (**MIT**)

[typescript@3.7.5](https://github.com/Microsoft/TypeScript
) (**Apache-2.0**)

[ua-parser-js@0.7.21](https://github.com/faisalman/ua-parser-js
) (**MIT**)

[unicode-canonical-property-names-ecmascript@1.0.4](https://github.com/mathiasbynens/unicode-canonical-property-names-ecmascript
) (**MIT**)

[unicode-match-property-ecmascript@1.0.4](https://github.com/mathiasbynens/unicode-match-property-ecmascript
) (**MIT**)

[unicode-match-property-value-ecmascript@1.1.0](https://github.com/mathiasbynens/unicode-match-property-value-ecmascript
) (**MIT**)

[unicode-property-aliases-ecmascript@1.0.5](https://github.com/mathiasbynens/unicode-property-aliases-ecmascript
) (**MIT**)

[union-value@1.0.1](https://github.com/jonschlinkert/union-value
) (**MIT**)

[uniq@1.0.1](https://github.com/mikolalysenko/uniq
) (**MIT**)

[uniqs@2.0.0](https://github.com/fgnass/uniqs
) (**MIT**)

[unique-filename@1.1.1](https://github.com/iarna/unique-filename
) (**ISC**)

[unique-slug@2.0.2](https://github.com/iarna/unique-slug
) (**ISC**)

[universalify@0.1.2](https://github.com/RyanZim/universalify
) (**MIT**)

[unpipe@1.0.0](https://github.com/stream-utils/unpipe
) (**MIT**)

[unquote@1.1.1](https://github.com/lakenen/node-unquote
) (**MIT**)

[unset-value@1.0.0](https://github.com/jonschlinkert/unset-value
) (**MIT**)

[upath@1.2.0](https://github.com/anodynos/upath
) (**MIT**)

[uri-js@4.2.2](https://github.com/garycourt/uri-js
) (**BSD-2-Clause**)

[urix@0.1.0](https://github.com/lydell/urix
) (**MIT**)

[url-loader@2.3.0](https://github.com/webpack-contrib/url-loader
) (**MIT**)

[url-parse@1.4.7](https://github.com/unshiftio/url-parse
) (**MIT**)

[url@0.11.0](https://github.com/defunctzombie/node-url
) (**MIT**)

[use@3.1.1](https://github.com/jonschlinkert/use
) (**MIT**)

[util-deprecate@1.0.2](https://github.com/TooTallNate/util-deprecate
) (**MIT**)

[util.promisify@1.0.0](https://github.com/ljharb/util.promisify
) (**MIT**)

[util.promisify@1.0.1](https://github.com/ljharb/util.promisify
) (**MIT**)

[util@0.10.3](https://github.com/defunctzombie/node-util
) (**MIT**)

[util@0.11.1](https://github.com/defunctzombie/node-util
) (**MIT**)

[utila@0.4.0](https://github.com/AriaMinaei/utila
) (**MIT**)

[utils-merge@1.0.1](https://github.com/jaredhanson/utils-merge
) (**MIT**)

[uuid@3.4.0](https://github.com/uuidjs/uuid
) (**MIT**)

[uuid@7.0.2](https://github.com/uuidjs/uuid
) (**MIT**)

[uuidv4@6.0.6](https://github.com/thenativeweb/uuidv4
) (**MIT**)

[v8-compile-cache@2.1.0](https://github.com/zertosh/v8-compile-cache
) (**MIT**)

[validate-npm-package-license@3.0.4](https://github.com/kemitchell/validate-npm-package-license.js
) (**Apache-2.0**)

[value-equal@1.0.1](https://github.com/mjackson/value-equal
) (**MIT**)

[vary@1.1.2](https://github.com/jshttp/vary
) (**MIT**)

[vendors@1.0.4](https://github.com/wooorm/vendors
) (**MIT**)

[verror@1.10.0](https://github.com/davepacheco/node-verror
) (**MIT**)

[viewport-mercator-project@7.0.1](https://github.com/uber-web/math.gl
) (**MIT**)

[vm-browserify@1.1.2](https://github.com/substack/vm-browserify
) (**MIT**)

[vt-pbf@3.1.1](https://github.com/mapbox/vt-pbf
) (**MIT**)

[w3c-hr-time@1.0.2](https://github.com/jsdom/w3c-hr-time
) (**MIT**)

[w3c-xmlserializer@1.1.2](https://github.com/jsdom/w3c-xmlserializer
) (**MIT**)

[wait-for-expect@3.0.2](https://github.com/TheBrainFamily/wait-for-expect
) (**MIT**)

[walker@1.0.7](https://github.com/daaku/nodejs-walker
) (**Apache-2.0**)

[watchpack@1.6.0](https://github.com/webpack/watchpack
) (**MIT**)

[wbuf@1.7.3](https://github.com/indutny/wbuf
) (**MIT**)

[webidl-conversions@4.0.2](https://github.com/jsdom/webidl-conversions
) (**BSD-2-Clause**)

[webpack-dev-middleware@3.7.2](https://github.com/webpack/webpack-dev-middleware
) (**MIT**)

[webpack-dev-server@3.10.2](https://github.com/webpack/webpack-dev-server
) (**MIT**)

[webpack-log@2.0.0](https://github.com/webpack-contrib/webpack-log
) (**MIT**)

[webpack-manifest-plugin@2.2.0](https://github.com/danethurber/webpack-manifest-plugin
) (**MIT**)

[webpack-sources@1.4.3](https://github.com/webpack/webpack-sources
) (**MIT**)

[webpack@4.41.5](https://github.com/webpack/webpack
) (**MIT**)

[websocket-driver@0.7.3](https://github.com/faye/websocket-driver-node
) (**Apache-2.0**)

[websocket-extensions@0.1.3](https://github.com/faye/websocket-extensions-node
) (**MIT**)

[wgs84@0.0.0](https://github.com/mapbox/wgs84
) (**BSD-2-Clause**)

[whatwg-encoding@1.0.5](https://github.com/jsdom/whatwg-encoding
) (**MIT**)

[whatwg-fetch@3.0.0](https://github.com/github/fetch
) (**MIT**)

[whatwg-mimetype@2.3.0](https://github.com/jsdom/whatwg-mimetype
) (**MIT**)

[whatwg-url@6.5.0](https://github.com/jsdom/whatwg-url
) (**MIT**)

[whatwg-url@7.1.0](https://github.com/jsdom/whatwg-url
) (**MIT**)

[which-module@1.0.0](https://github.com/nexdrew/which-module
) (**ISC**)

[which-module@2.0.0](https://github.com/nexdrew/which-module
) (**ISC**)

[which@1.3.1](https://github.com/isaacs/node-which
) (**ISC**)

[which@2.0.2](https://github.com/isaacs/node-which
) (**ISC**)

[wide-align@1.1.3](https://github.com/iarna/wide-align
) (**ISC**)

[word-wrap@1.2.3](https://github.com/jonschlinkert/word-wrap
) (**MIT**)

[workbox-background-sync@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-broadcast-update@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-build@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-cacheable-response@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-core@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-expiration@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-google-analytics@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-navigation-preload@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-precaching@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-range-requests@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-routing@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-strategies@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-streams@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-sw@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-webpack-plugin@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[workbox-window@4.3.1](https://github.com/googlechrome/workbox
) (**MIT**)

[worker-farm@1.7.0](https://github.com/rvagg/node-worker-farm
) (**MIT**)

[worker-rpc@0.1.1](https://github.com/DirtyHairy/worker-rpc
) (**MIT**)

[wrap-ansi@2.1.0](https://github.com/chalk/wrap-ansi
) (**MIT**)

[wrap-ansi@5.1.0](https://github.com/chalk/wrap-ansi
) (**MIT**)

[wrappy@1.0.2](https://github.com/npm/wrappy
) (**ISC**)

[write-file-atomic@2.4.1](https://github.com/iarna/write-file-atomic
) (**ISC**)

[write@1.0.3](https://github.com/jonschlinkert/write
) (**MIT**)

[ws@5.2.2](https://github.com/websockets/ws
) (**MIT**)

[ws@6.2.1](https://github.com/websockets/ws
) (**MIT**)

[xml-name-validator@3.0.0](https://github.com/jsdom/xml-name-validator
) (**Apache-2.0**)

[xmlchars@2.2.0](https://github.com/lddubeau/xmlchars
) (**MIT**)

[xregexp@4.3.0](https://github.com/slevithan/xregexp
) (**MIT**)

[xtend@4.0.2](https://github.com/Raynos/xtend
) (**MIT**)

[y18n@3.2.1](https://github.com/yargs/y18n
) (**ISC**)

[y18n@4.0.0](https://github.com/yargs/y18n
) (**ISC**)

[yallist@2.1.2](https://github.com/isaacs/yallist
) (**ISC**)

[yallist@3.1.1](https://github.com/isaacs/yallist
) (**ISC**)

[yallist@4.0.0](https://github.com/isaacs/yallist
) (**ISC**)

[yaml@1.8.2](https://github.com/eemeli/yaml
) (**ISC**)

[yargs-parser@11.1.1](https://github.com/yargs/yargs-parser
) (**ISC**)

[yargs-parser@13.1.1](https://github.com/yargs/yargs-parser
) (**ISC**)

[yargs-parser@5.0.0](https://github.com/yargs/yargs-parser
) (**ISC**)

[yargs@12.0.5](https://github.com/yargs/yargs
) (**MIT**)

[yargs@13.3.0](https://github.com/yargs/yargs
) (**MIT**)

[yargs@7.1.0](https://github.com/yargs/yargs) (**MIT**)



### Contact Us
If you run into any issues, please contact us at contact.reach.project@gmail.com.
