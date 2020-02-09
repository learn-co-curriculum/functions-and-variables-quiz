# Functions and Variables

???

# Functions and Variables Quiz

Read through the code snippets carefully before answering the questions below.
After you've read the code and corresponding question, we recommend testing your
assumptions by running the code before answering. [Repl.it](https://repl.it/) is
a good place to test each code snippet.

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
( ) greeting
(X) undefined OR 'log is not a function'

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
