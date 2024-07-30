# DAY-2 CONTROL STRUCTURES

Write a program to check if a number is `positive`, `negative` or `zero`, and log the result to the console

## Solutions

Here's a simple JavaScript program to check if a number is `positive`, `negative`, or `zero`, and log the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
// Function to add two numbers
function checkNumber(num) {
  if (num > 0) {
    console.log("The number is positive.");
  } else if (num < 0) {
    console.log("The number is negative.");
  } else {
    console.log("The number is zero.");
  }
}

// Test the function with different values
checkNumber(10);  // The number is positive.
checkNumber(-5);  // The number is negative.
checkNumber(0);   // The number is zero.
```

### Explanation

This function `checkNumber` takes a number as an argument and uses an `if-else` statement to determine if the number is positive, negative, or zero. It then logs the appropriate message to the console.eb browser's console or a Node.js runtime.

</details>
