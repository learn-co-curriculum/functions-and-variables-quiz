Functions and Variables Quiz
---

???

?: What does the following function call log to console?

``` javascript
function log() {
  console.log(x)
  var x = 'Hello!'
}

log()
```

( ) `'Hello!'`
(x) `undefined`
( ) `'undefined is not a function'`

?: What does the following function call log to console?

``` javascript
log()

function log() {
  console.log(x)
  var x = 'Hello!'
}
```

( ) `'Hello!'`
(x) `undefined`
( ) `'undefined is not a function'`

?: What does the following function call log to console?

``` javascript
log()

var log = function() {
  console.log(x)
  var x = 'Hello!'
}
```

( ) `'Hello!'`
( ) `undefined`
(x) `'undefined is not a function'`


?: What does the following function log to console?

``` javascript
function log(x) {
  var x = 'Mr. X'

  console.log(x)
}

log('Hello!')
```

( ) `'Hello!'`
(x) `'Mr. X'`
( ) `undefined`
( ) `'undefined is not a function'`

?: What does this function log?

``` javascript
function whatIsX() {
  var x = 1

  if (x) {
    let x = 2
    console.log(x)
  }

  console.log(x)
}
```

(x) `2`, `1`
( ) `2`, `2`
( ) `undefined`, `2`
( ) `undefined`, `1`
( ) Nothing, it errors out.

?: True or false: in the following example, `dictionary` can be reassigned.

``` javascript
const dictionary = {}
```

( ) True
(x) False


?: True or false: we can add a key to `dictionary` below.

``` javascript
const dictionary = {}
```

(x) True
( ) False

???
