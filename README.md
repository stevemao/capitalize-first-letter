#  [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]

Capitalize the first letter of a string

## Synopsis

```javascript
var capitalize = require('./')

var test = require('tape')

test('Capitalize first letter', function (t) {
  t.plan(1)
  t.equal(capitalize("united states"), "United states")
})
```

## Install

```
npm install capitalize-first-letter
```

## License

MIT

[npm-image]: https://badge.fury.io/js/capitalize-first-letter.svg
[npm-url]: https://npmjs.org/package/capitalize-first-letter
[travis-image]: https://travis-ci.org/stevemao/capitalize-first-letter.svg?branch=master
[travis-url]: https://travis-ci.org/stevemao/capitalize-first-letter
