# DAY-1 VARIABLES AND DATA TYPES

Create variables of different types (number, string, boolean, object, array) and log each variable's type using the `typeof` operator.

## Solutions

Here's how you can create variables of different types and log each variable's type using the `typeof` operator in JavaScript:

<details>
  <summary>Click For Solution</summary>

```JS
// Declare variables of different types
var myNumber = 42;
let myString = "Hello, world!";
const myBoolean = true;
const myObject = { name: "John", age: 30 };
const myArray = [1, 2, 3, 4, 5];

// Log the type of each variable
console.log(typeof myNumber);   // "number"
console.log(typeof myString);   // "string"
console.log(typeof myBoolean);  // "boolean"
console.log(typeof myObject);   // "object"
console.log(typeof myArray);    // "object"
```

### Explanation

This code declares variables of different types (number, string, boolean, object, and array) and then logs the type of each variable using the `typeof` operator. Note that in JavaScript, arrays are a type of object, so `typeof myArray` returns `"object"`.

</details>
