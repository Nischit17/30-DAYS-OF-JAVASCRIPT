# DAY-2 OPERATORS

Write a program that uses the `&&` operator to combine two conditions and log the result to the console

## Solutions

Here is a simple JavaScript program that uses the `&& (logical AND)` operator to combine two conditions and logs the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Define two conditions
let condition1 = true;
let condition2 = false;

// Combine the conditions using &&
let result = condition1 && condition2;

// Log the result to the console
console.log("The result of condition1 && condition2 is: " + result);

// Example with numbers
let number1 = 10;
let number2 = 20;

// Check if both numbers are greater than 5
let areBothGreaterThanFive = (number1 > 5) && (number2 > 5);

// Log the result to the console
console.log(number1 + " and " + number2 + " are both greater than 5: " + areBothGreaterThanFive);
```

### Explanation

You can run this code in any JavaScript environment, such as a web browser's console or a Node.js runtime.

</details>
