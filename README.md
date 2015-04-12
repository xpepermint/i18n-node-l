# [i18n-node](https://github.com/mashpie/i18n-node)-rev

> The __l function extension for i18n-node for translating express routes.


## Setup

Install the package.

```
npm install --save i18n i18n-l
```

Extend the `i18n` module and translate a route.

```js
// index.js (example ExpressJS application)
...
var i18n = require('i18n');
require('i18n-l')(i18n);
...
app.get( i18n.__l('/products'), function (req, res) {
  ...
});

```
