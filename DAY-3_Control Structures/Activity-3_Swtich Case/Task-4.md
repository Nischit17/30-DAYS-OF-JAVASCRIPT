# DAY-2 CONTROL STRUCTURES

Write a program that uses a `switch` case to determine the `day of the week` based on a `number (1-7)` and log the day name to the console.

## Solutions

Here's a JavaScript program that uses a `switch` statement to determine the day of the week based on a `number (1-7)` and log the day name to the console:

<details>
  <summary>Click For Solution</summary>

```JS
function getDayName(dayNumber) {
  let dayName;

  switch (dayNumber) {
    case 1:
      dayName = "Sunday";
      break;
    case 2:
      dayName = "Monday";
      break;
    case 3:
      dayName = "Tuesday";
      break;
    case 4:
      dayName = "Wednesday";
      break;
    case 5:
      dayName = "Thursday";
      break;
    case 6:
      dayName = "Friday";
      break;
    case 7:
      dayName = "Saturday";
      break;
    default:
      dayName = "Invalid day number";
  }

  console.log(dayName);
}

// Test the function with different day numbers
getDayName(1);  // Sunday
getDayName(4);  // Wednesday
getDayName(7);  // Saturday
getDayName(0);  // Invalid day number
```

### Explanation

This function `getDayName` takes a number as an argument and uses a `switch` statement to determine the corresponding day of the week. It then logs the day name to the console. If the number is not in the range 1-7, it logs "Invalid day number."

</details>
