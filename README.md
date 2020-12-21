# is-value-empty
This is simple library fro check whether value is empty. This libry support all kind of data types 

# Installation
```sh
$ npm install is-value-empty
or
$ yarn add is-value-empty
```
# Example

```js
const isEmpty = require('is-value-empty')
or
import isEmpty from 'is-value-empty'

/* ------------- Object and Arrays ------------- */
console.log(isEmpty([])); //return true
console.log(isEmpty([1, 2])); // return false
console.log(isEmpty({})); //return true
console.log(isEmpty({ foo: "bar" })); //return false

/* ------------- primitive ------------- */
console.log(isEmpty("")); //return true
console.log(isEmpty(" ")); //return true
console.log(isEmpty(null)); //return true
console.log(isEmpty(undefined)); //return true

console.log(isEmpty(0)); //return true
console.log(isEmpty(1)); //return false
console.log(isEmpty(-1)); //return false

console.log(isEmpty(true)); //return false
console.log(isEmpty(false)); //return false

```

# API
### isEmpty(val)
check value is empty

# License
MIT