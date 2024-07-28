# DAY-1 VARIABLES AND DATA TYPES

Create a script that demonstrates the difference in behaviour between `let` and `const` when it comes to reassignment.

## Solutions

Here is a script that demonstrates the difference in behavior between `let` and `const` when it comes to reassignment:

<details>
  <summary>Click For Solution</summary>

```JS
// Using let for a variable
let myLetVariable = "Initial value with let";
console.log("myLetVariable initial value:", myLetVariable);

myLetVariable = "Reassigned value with let";
console.log("myLetVariable after reassignment:", myLetVariable);

// Using const for a variable
const myConstVariable = "Initial value with const";
console.log("myConstVariable initial value:", myConstVariable);

try {
    myConstVariable = "Attempt to reassign value with const";
} catch (error) {
    console.log("Error when reassigning myConstVariable:", error.message);
}
```

### Explanation

In this script:

- A variable `myLetVariable` is declared with `let` and assigned an initial value. It is then reassigned a new value, demonstrating that variables declared with `let` can be reassigned.

- A variable `myConstVariable` is declared with `const` and assigned an initial value. When an attempt is made to reassign it, a `TypeError` is thrown, demonstrating that variables declared with `const` cannot be reassigned.

</details>
