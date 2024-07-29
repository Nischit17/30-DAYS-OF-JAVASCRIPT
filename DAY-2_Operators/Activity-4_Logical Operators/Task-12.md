# DAY-2 OPERATORS

Write a program that uses the `||` operator to combine two conditions and log the result to the console

## Solutions

Here is a simple JavaScript program that uses the `|| (logical OR)` operator to combine two conditions and logs the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Define two conditions
let condition1 = false;
let condition2 = true;

// Combine the conditions using ||
let result = condition1 || condition2;

// Log the result to the console
console.log("The result of condition1 || condition2 is: " + result);

// Example with numbers
let number1 = 3;
let number2 = 7;

// Check if at least one number is greater than 5
let isAtLeastOneGreaterThanFive = (number1 > 5) || (number2 > 5);

// Log the result to the console
console.log(number1 + " or " + number2 + " is greater than 5: " + isAtLeastOneGreaterThanFive);
```

### Explanation

You can run this code in any JavaScript environment, such as a web browser's console or a Node.js runtime.

</details>
