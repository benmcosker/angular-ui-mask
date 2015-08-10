# ui-mask [![Build Status](https://travis-ci.org/angular-ui/ui-mask.svg?branch=master)](https://travis-ci.org/angular-ui/ui-mask) [![npm version](https://badge.fury.io/js/angular-ui-mask.svg)](http://badge.fury.io/js/angular-ui-mask) [![Bower version](https://badge.fury.io/bo/angular-ui-mask.svg)](http://badge.fury.io/bo/angular-ui-mask) [![Join the chat at https://gitter.im/angular-ui/ui-mask](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/angular-ui/ui-mask?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Apply a mask on an input field so the user can only type pre-determined pattern.

## Requirements

- AngularJS

## Usage


You can get it from [Bower](http://bower.io/)

```sh
bower install angular-ui-mask
```

Load the script files in your application:

```html
<script type="text/javascript" src="bower_components/angular/angular.js"></script>
<script type="text/javascript" src="bower_components/angular-ui-mask/dist/mask.js"></script>
```

Add the specific module to your dependencies:

```javascript
angular.module('myApp', ['ui.mask', ...])
```
##NEW FEATURE
a new feature, clearPlaceholdersonBlur, is hardcoded into this branch that allows the placeholders to not appear on initialization and on blur. continued work will address accessibiity issues using the <span aria-live='assertive'> HTML5 attribute tied in with specific vaidation information (the key pressed and its validity).
