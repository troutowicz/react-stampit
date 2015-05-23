# react-stamp
A specialized [stampit](https://github.com/ericelliott/stampit) stamp for [React](https://github.com/facebook/react).

### Use
```js
var react = require('react-stamp');
var stampit = require('stampit');

module.exports = stampit.compose(react)
  // mixin
  .methods(...)
  // component methods
  .methods({
    ...
  });
```

[![MIT](https://img.shields.io/badge/license-MIT-blue.svg)](http://troutowicz.mit-license.org)
