# Functions and Variables

???

# Functions and Variables Quiz

?: What does the following function call log to console:

```javascript
function log() {
  console.log(greeting);
  var greeting = 'Hello!';
}
log();
```

( ) 'Hello!'
(X) undefined
( ) 'undefined is not a function'

?: What does the following function call log to console:

```javascript
log();
function log() {
  console.log(greeting);
  var greeting = 'Hello!';
}
```

( ) 'Hello!'
(X) undefined
( ) 'undefined is not a function'

?: What does the following function call log to console:

```javascript
log();
var log = function() {
  console.log(greeting);
  var greeting = 'Hello!';
}
```

( ) 'Hello!'
( ) undefined
(X) 'log is not a function'

?: What does the following function log to console:

```javascript
function log(s) {
  var s = 'Mr. X';
  console.log(s);
}
log('Hello!');
```

( ) 'Hello!'
(X) 'Mr. X'
( ) undefined
( ) 'undefined is not a function'

???
