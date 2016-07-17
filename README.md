# ng-holder

An AngularJS directive for [HolderJS](https://github.com/imsky/holder).

## Usage

### 1. Install

Install with bower:

```bash
bower install holderjs angular-holderjs --save
```

Install with npm:

```bash
bower install holderjs angular-holderjs --save
```

### 2. Add Dependency

Add as a dependency in your Angular app:

```javascript
var app = angular.module('app', [
  'ngHolder',
]);
```
### 3. Use

Use directive one of two ways:

```html
<img holder="holder.js/200x200/text:?">
<img holder data-src="holder.js/200x200/text:?">
```

## Change History

### v1.0.2 - 2016/07/17

* Added npm install method

### v1.0.1 - 2014/02/23

* Remove dependency on `holderjs` and install it separately in application

### v1.0.0 - 2014/02/23

* Initial release
