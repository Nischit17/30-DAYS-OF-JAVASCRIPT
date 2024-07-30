# DAY-2 CONTROL STRUCTURES

Write a program that uses the `ternary` operator to check if a number is `even` or `odd` and log the result to the console.

## Solutions

Here's a JavaScript program that uses the `ternary` operator to check if a number is even or odd and log the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
function checkEvenOrOdd(num) {
  const result = (num % 2 === 0) ? "The number is even." : "The number is odd.";
  console.log(result);
}

// Test the function with different numbers
checkEvenOrOdd(4);  // The number is even.
checkEvenOrOdd(7);  // The number is odd.
checkEvenOrOdd(0);  // The number is even.
checkEvenOrOdd(-3); // The number is odd.
```

### Explanation

This function `checkEvenOrOdd` takes a number as an argument and uses the ternary operator to determine if the number is even or odd. It then logs the result to the console.

</details>
