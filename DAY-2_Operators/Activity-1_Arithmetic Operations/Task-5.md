# DAY-2 OPERATORS

Write a program to find the `remainder` when one number is divided by another and log the result to the console.

## Solutions

Here is a simple JavaScript program that finds the `r`emainder` when one number is divided by another and logs the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Function to find the remainder of two numbers
function findRemainder(num1, num2) {
  if (num2 === 0) {
    return "Error: Division by zero is not allowed.";
  }
  return num1 % num2;
}

// Define two numbers
let number1 = 17;
let number2 = 5;

// Call the function and store the result
let result = findRemainder(number1, number2);

// Log the result to the console
console.log("The remainder is: " + result);
```

### Explanation

You can run this code in any JavaScript environment, such as a web browser's console or a Node.js runtime.

</details>
