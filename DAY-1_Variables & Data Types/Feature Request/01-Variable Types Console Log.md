# DAY-1 VARIABLES AND DATA TYPES

Write a script that declares variables of different data types and logs both the value and type of each variable to the console.

## Solutions

Here is a script that declares variables of different data types and logs both the value and type of each variable to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Declare variables of different data types
let myNumber = 42;
let myString = "Hello, world!";
const myBoolean = true;
const myObject = { name: "John", age: 30 };
const myArray = [1, 2, 3, 4, 5];
let myUndefined;
const myNull = null;

// Log the value and type of each variable
console.log("Value:", myNumber, "Type:", typeof myNumber);      // 42, number
console.log("Value:", myString, "Type:", typeof myString);      // "Hello, world!", string
console.log("Value:", myBoolean, "Type:", typeof myBoolean);    // true, boolean
console.log("Value:", myObject, "Type:", typeof myObject);      // { name: "John", age: 30 }, object
console.log("Value:", myArray, "Type:", typeof myArray);        // [1, 2, 3, 4, 5], object
console.log("Value:", myUndefined, "Type:", typeof myUndefined);// undefined, undefined
console.log("Value:", myNull, "Type:", typeof myNull);          // null, object
```

### Explanation

This script declares variables of various data types, including `number`, `string`, `boolean`, `object`, `array`, `undefined`, and `null`. It then logs both the value and type of each variable to the console. Note that `typeof null` returns "object" due to a known quirk in JavaScript.

</details>
