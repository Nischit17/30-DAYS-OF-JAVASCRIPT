# DAY-2 OPERATORS

Write a program to `divide` two numbers and log the result to the console.

## Solutions

Here is a simple JavaScript program that `divides` two numbers and logs the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Function to divide two numbers
function divideNumbers(num1, num2) {
  if (num2 === 0) {
    return "Error: Division by zero is not allowed.";
  }
  return num1 / num2;
}

// Define two numbers
let number1 = 16;
let number2 = 4;

// Call the function and store the result
let result = divideNumbers(number1, number2);

// Log the result to the console
console.log("The result is: " + result);
```

### Explanation

You can run this code in any JavaScript environment, such as a web browser's console or a Node.js runtime.

</details>
