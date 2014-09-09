# reduce [![build status][travis-svg]][travis-url]

[![browser support][testling-png]][testling-url]

## Example

Like `Array.prototype.reduce` but works on Object and accepts optional
`this` value

``` js
var reduce = require("reduce")

reduce({
    key: "value"
    , key2: "value2"
    , ...
}, function (acc, value, key) {
    /* real code */
    acc[key] = value
    return acc
}, {
    this: "context"
}, {
    initial: "value"
})
```

## Installation

`npm install reduce`

## Contributors

 - Raynos

## MIT Licenced

  [travis-svg]: https://secure.travis-ci.org/Raynos/reduce.svg
  [travis-url]: http://travis-ci.org/Raynos/reduce
  [testling-png]: https://ci.testling.com/Raynos/reduce.png
  [testling-url]: https://ci.testling.com/Raynos/reduce

