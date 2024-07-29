# DAY-2 OPERATORS

Create a script that compares two numbers using different comparison operators and combines conditions using logical operators, logging the results.

## Solutions

Here is a JavaScript script that compares two numbers using different comparison operators and combines conditions using logical operators, then logs the results to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Define two numbers
let number1 = 15;
let number2 = 10;

// Compare the numbers using different comparison operators
let isEqual = number1 == number2;
let isStrictlyEqual = number1 === number2;
let isNotEqual = number1 != number2;
let isStrictlyNotEqual = number1 !== number2;
let isGreater = number1 > number2;
let isGreaterOrEqual = number1 >= number2;
let isLess = number1 < number2;
let isLessOrEqual = number1 <= number2;

// Log the comparison results to the console
console.log(number1 + " == " + number2 + ": " + isEqual);
console.log(number1 + " === " + number2 + ": " + isStrictlyEqual);
console.log(number1 + " != " + number2 + ": " + isNotEqual);
console.log(number1 + " !== " + number2 + ": " + isStrictlyNotEqual);
console.log(number1 + " > " + number2 + ": " + isGreater);
console.log(number1 + " >= " + number2 + ": " + isGreaterOrEqual);
console.log(number1 + " < " + number2 + ": " + isLess);
console.log(number1 + " <= " + number2 + ": " + isLessOrEqual);

// Combine conditions using logical operators
let andCondition = (number1 > number2) && (number1 != number2);
let orCondition = (number1 < number2) || (number1 === number2);
let notCondition = !(number1 === number2);

// Log the logical operator results to the console
console.log("The result of (number1 > number2) && (number1 != number2): " + andCondition);
console.log("The result of (number1 < number2) || (number1 === number2): " + orCondition);
console.log("The result of !(number1 === number2): " + notCondition);
```

### Explanation

You can run this code in any JavaScript environment, such as a web browser's console or a Node.js runtime.

</details>
