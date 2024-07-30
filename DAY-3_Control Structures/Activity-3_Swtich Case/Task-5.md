# DAY-2 CONTROL STRUCTURES

Write a program that uses a `switch` case to assign a `grade ('A', 'B', 'C', 'D', 'F')` based on score and log the grade to the console.

## Solutions

Here's a JavaScript program that uses a `switch` statement to assign a grade `('A', 'B', 'C', 'D', 'F')` based on a score and log the grade to the console:

<details>
  <summary>Click For Solution</summary>

```JS
function getGrade(score) {
  let grade;

  switch (true) {
    case (score >= 90 && score <= 100):
      grade = 'A';
      break;
    case (score >= 80 && score < 90):
      grade = 'B';
      break;
    case (score >= 70 && score < 80):
      grade = 'C';
      break;
    case (score >= 60 && score < 70):
      grade = 'D';
      break;
    case (score >= 0 && score < 60):
      grade = 'F';
      break;
    default:
      grade = 'Invalid score';
  }

  console.log("The grade is: " + grade);
}

// Test the function with different scores
getGrade(95);  // The grade is: A
getGrade(85);  // The grade is: B
getGrade(75);  // The grade is: C
getGrade(65);  // The grade is: D
getGrade(55);  // The grade is: F
getGrade(-5);  // The grade is: Invalid score
getGrade(105); // The grade is: Invalid score
```

### Explanation

This function `getGrade` takes a score as an argument and uses a `switch` statement to determine the corresponding grade based on the score range. It then logs the grade to the console. If the score is not within the valid range (0-100), it logs "Invalid score."

</details>
