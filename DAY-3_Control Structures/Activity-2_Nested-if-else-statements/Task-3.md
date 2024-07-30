# DAY-2 CONTROL STRUCTURES

Write a program to find the `largest of three numbers` using nested-if-else statements

## Solutions

Here's a JavaScript program to find the `largest of three numbers` using nested if-else statements:

<details>
  <summary>Click For Solution</summary>

```JS
function findLargest(a, b, c) {
  let largest;

  if (a >= b) {
    if (a >= c) {
      largest = a;
    } else {
      largest = c;
    }
  } else {
    if (b >= c) {
      largest = b;
    } else {
      largest = c;
    }
  }

  console.log("The largest number is: " + largest);
}

// Test the function with different sets of numbers
findLargest(10, 20, 30);  // The largest number is: 30
findLargest(50, 20, 30);  // The largest number is: 50
findLargest(10, 90, 30);  // The largest number is: 90
findLargest(10, 20, 20);  // The largest number is: 20
```

### Explanation

This function `findLargest` takes three numbers as arguments and uses nested `if-else` statements to determine which number is the largest. It then logs the largest number to the console.

</details>
