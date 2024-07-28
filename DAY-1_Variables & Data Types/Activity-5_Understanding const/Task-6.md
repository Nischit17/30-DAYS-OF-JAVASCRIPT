# DAY-1 VARIABLES AND DATA TYPES

Try reassigning a variable declared with `const` and observe the error.

## Solutions

Here is an example of attempting to reassign a variable declared with `const` and the resulting error:

<details>
  <summary>Click For Solution</summary>

```JS
const myConstant = "Initial value";
console.log("Initial value:", myConstant);

try {
    myConstant = "New value";
} catch (error) {
    console.log("Error:", error.message);
}
```

### Explanation

This code declares a constant named `myConstant` with an initial value of `"Initial value"`, logs that value to the console, and then attempts to reassign `myConstant` to `"New value"`. The reassignment will cause a `TypeError` because constants cannot be reassigned. The error is caught in the `try`-`catch` block and logged to the console.

</details>
