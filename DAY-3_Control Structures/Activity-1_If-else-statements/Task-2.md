# DAY-2 CONTROL STRUCTURES

Write a program to check if a person is eligible to `vote (age >= 18)` and log the result to the console

## Solutions

Here's a simple JavaScript program to check if a person is eligible to `vote` based on their age, and log the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
function checkVotingEligibility(age) {
  if (age >= 18) {
    console.log("The person is eligible to vote.");
  } else {
    console.log("The person is not eligible to vote.");
  }
}

// Test the function with different ages
checkVotingEligibility(20);  // The person is eligible to vote.
checkVotingEligibility(17);  // The person is not eligible to vote.
checkVotingEligibility(18);  // The person is eligible to vote.
```

### Explanation

This function `checkVotingEligibility` takes an age as an argument and uses an `if-else` statement to determine if the person is eligible to vote. It then logs the appropriate message to the console.

</details>
