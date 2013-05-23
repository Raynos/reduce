# reduce [![build status][1]][2]

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

  [1]: https://secure.travis-ci.org/Raynos/reduce.png
  [2]: http://travis-ci.org/Raynos/reduce
