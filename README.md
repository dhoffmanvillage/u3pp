# Unit 3 Programming Project

For this project, you will be completing parts of the `Main` and `LeapYear` classes in ordfer to fulfill the specs or each part below.

## PART A - Main.java

For **Part A** you are going to complete the class `Main`. In order to do so, you will need to:

1. Take input from the user with a `Scanner`. Use that input to update the variable `year`.
   - Note: To convert a `String` to an `int`, you can use the code: `int intName = Integer.parseInt(stringName);`
2. At the end of the `main` method, make sure to close the `Scanner`

## PART B - LeapYear.java

For **PART B**, you need to complete the method `boolean isLeapYear(int year)` in the `LeapYear` class. A `year` is a leap year based on the following rules:

1. Everything before 1582 is not a leap year
2. Every year between 1582 and now that is exactly divisible by four is a leap year.
   - Years that are evenly divisble by 100 are not leap years unless they are evenly divisible by 400
   - - Example: 1700, 1800, and 1900 are not leap years
   - - Example: 1600 and 2000 are leap years

Your function should `return true` if the `year` is a leap year and `false` if the year is not a leap year.

When **PART A** and **PART B** are both done, they should function together like the **Sample Run** below

### Sample Run

```java
Enter a year (or enter STOP to end):  2000
2000 is a leap year
Enter a year (or enter STOP to end):  1900
1900 is not a leap year
Enter a year (or enter STOP to end):  1956
1956 is a leap year
Enter a year (or enter STOP to end):  1580
1580 is not a leap year
Enter a year (or enter STOP to end):  STOP
```

## Grading Breakdown

- Attempted code in all **YOUR CODE HERE** areas: 40 points
- Correctly updated all comments: 20 points
- Passed all Test Cases: 40 points
