## Useful Notes

### Object Destructuring

Consider the following object:
```
let myPeople = {
    person1: {
        firstName: 'Gary',
        lastName: 'Unknown',
        country: 'Finland',
        languages: ['Suomi', 'Dansk']
    }
}
```

It is possible to set a variable from a value in the object like so:

```
let languages = myPeople.person1.languages;
```

Or with object destructuring:

```
let {languages} = myPeople.person1;
```

### Import/Require destructuring

Consider the following import scenario:

```
const myFirstFunction = requires('./exports.js');
const mySecondFunction = requires('./exports.js');
```

With import destructuring:

```
const {myFirstFunction, mySecondFunction} = requires('./exports.js');
```


### Promises

To instantiate a promise use the following syntax:

```
/* Callback function. Resolve and reject are
   are automatically passed in when the function
   is invoked.
*/
const callBackFunction = (resolve, reject) => {};

// As an arrow function with an existing callback function
const promiseFunction = () => {
    return new Promise(callBackFunction());

};

// As an arrorw function with a an inline/anonymous function
const promiseFunction = () => {
    return new Promise( (resolve, reject) => {} );
};
```

#### .then()

Any function that returns a promise can use `.then()` to process
the results. Consider creating an S3 bucket in AWS and then
uploading objects(s) to it.

```
const bucketCreator = () => {
    return new Promise((resolve, reject) => {
        // Create bucket logic here
    }
};

// Note that we are not invoking the function here.
const bucketPromise = bucketCreator

bucketPromise().then(() => {
    // Upload objects logic here
})
```
.then() functions can be chained. And the results of each .then()
can be passed down to the next.

#### onFullfilled/onRejected

These are option callback functions that can be passed into


#### Try/Catch
Because a promise is either a success or failure, this lends well
to error handling, using try/catch.


#### Async Arrow Function

```
const myArrow = async () => {};
```

vs.

```
async function myFunction() {};
```

### NodeJS

#### Standar Library/Core Modules

To enumerate the NodeJS standard library:

```
require('module').builtinModules;
```
