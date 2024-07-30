# DAY-2 CONTROL STRUCTURES

Write a program to check if a year is a leap year using multiple conditions (divisible by 4, but not 100 unless also divisible by 400) and log the result to the console.

## Solutions

Here's a JavaScript program to check if a year is a leap year using the specified conditions and log the result to the console:

<details>
  <summary>Click For Solution</summary>

```JS
function checkLeapYear(year) {
  let isLeapYear;

  if (year % 4 === 0) {
    if (year % 100 === 0) {
      if (year % 400 === 0) {
        isLeapYear = true;
      } else {
        isLeapYear = false;
      }
    } else {
      isLeapYear = true;
    }
  } else {
    isLeapYear = false;
  }

  if (isLeapYear) {
    console.log(year + " is a leap year.");
  } else {
    console.log(year + " is not a leap year.");
  }
}

// Test the function with different years
checkLeapYear(2020);  // 2020 is a leap year.
checkLeapYear(1900);  // 1900 is not a leap year.
checkLeapYear(2000);  // 2000 is a leap year.
checkLeapYear(2021);  // 2021 is not a leap year.
```

### Explanation

This function `checkLeapYear` takes a year as an argument and uses nested `if-else` statements to determine if the year is a leap year based on the given conditions. It then logs the result to the console.

</details>
