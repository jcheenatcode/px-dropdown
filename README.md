# px-dropdown [![Build Status](https://travis-ci.org/PredixDev/px-dropdown.svg?branch=master)](https://travis-ci.org/PredixDev/px-dropdown)

## Overview

`Px-dropdown` is a Predix UI component which can be placed in any element, and opens a customizable dropdown list.

## Usage

### Prerequisites
1. node.js
2. npm
3. bower
4. [webcomponents-lite.js polyfill](https://github.com/webcomponents/webcomponentsjs)

Node, npm and bower are necessary to install the component and dependencies. webcomponents.js adds support for web components and custom elements to your application.

### Getting Started

First, install the component via bower on the command line:

```
bower install px-dropdown --save
```

Second, import the component to your application with the following tag in your head:

```
<link rel="import" href="/bower_components/px-dropdown/px-dropdown.html"/>
```

Finally, use the component in your application:

```
<px-dropdown display-value="Text">
  <px-dropdown-content class="px-dropdown-content" max-cont-character-width="10"
  extend-dropdown="true" extend-dropdown-by="15" items='[{"key":"one", "val": "One"}, {"key":"two", "val": "Two"}, {"key":"three", "val": "Three"}, {"key":"four", "val": "How now brown cow"}]'>
  </px-dropdown-content>
</px-dropdown>
```

<br />
<hr />

## Documentation

Read the full API and view the demo [here](https://predixdev.github.io/px-dropdown).

Also, make sure to look at the `demo-angular.html` page for an example of using Polymer with Angular.

## Local Development

From the component's directory...

```
$ npm install
$ bower install
$ gulp sass
```

From the component's directory, to start a local server run:

```
$ gulp serve
```

Navigate to the root of that server (e.g. http://localhost:8080/) in a browser to open the API documentation page, with link to the "Demo" / working examples.

### LiveReload

By default gulp serve is configured to enable LiveReload and will be watching for modifications in your root directory as well as `/css`.






### GE Coding Style Guide
[GE JS Developer's Guide](https://github.com/GeneralElectric/javascript)

<br />
<hr />

## Known Issues

Please use [Github Issues](https://github.com/PredixDev/px-dropdown/issues) to submit any bugs you might find.
