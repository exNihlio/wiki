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
