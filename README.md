# LAB | JavaScript Basics - The Coding Dragon

## Learning Goals
- Understand and use JavaScript primitive data types (booleans, numbers, strings).
- Apply conditional statements to guide the dragon's learning decisions.
- Utilize loops for practicing coding exercises in JavaScript.

## Introduction
Welcome to the Coding Dragon's lab! In this adventure, you will help the dragon as it embarks on a quest to master JavaScript. You’ll work with booleans to track its study habits, use random numbers to determine how many topics it has studied, and calculate the total hours needed for study.

## Requirements
You'll complete the following iterations, each focusing on specific programming skills.

### Iteration 1: Study Setup
1. **Create a boolean variable `isStudyingJS`** and set it to `true` if the dragon is actively studying JavaScript.
   - Print: `"The dragon is currently studying JavaScript!"` if `isStudyingJS` is true, or `"The dragon is taking a break from studying JavaScript."` if false.

2. **Create a variable `jsTopicsCovered`** and set it to a random number between 1 and 10 to represent how many JavaScript topics the dragon has learned.
   - Print: `"The dragon has covered XX JavaScript topics."` (Replace XX with the actual number).

3. **Calculate the total `practiceHours` needed**, based on the number of topics covered (each topic takes 2 hours to study) and store it in a variable.
   - Print: `"The dragon needs YY hours to study JavaScript."` (Replace YY with `jsTopicsCovered * 2`).

### Iteration 2: Conditional Learning Check
4. **Use conditionals to evaluate the dragon’s learning:**
   - If `isStudyingJS` is `true` and `practiceHours >= 4`, print: `"Excellent job! Keep coding!"`
   - If `isStudyingJS` is `false`, print: `"The dragon should get back to studying JavaScript!"`
   - If `jsTopicsCovered < 5`, print: `"The dragon needs to cover more topics to master JavaScript."`

### Iteration 3: Looping Through Practice Exercises
5. **Simulate the dragon's practice exercises using a loop:**
   - Create a variable `exercisesCompleted` initialized to 0.
   - Use a `while` loop to increment `exercisesCompleted` by 1 until the dragon completes 10 exercises.
   - Print: `"The dragon has completed ZZ JavaScript exercises."` (where ZZ is the value of `exercisesCompleted` after each increment).
   - Once the total exercises have been completed, print: `"The dragon's practice session is over! Well done!"`

### Bonus Time!
**Bonus 1:**
1. **Create a variable `numberOfDebuggedErrors`** and set it to a random number between 1 and 5 (representing how many errors the dragon has debugged).
2. Use a `for` loop to simulate debugging each error.
   - Print: `"Error XX debugged!"` for each debugged error.
   - If the dragon debugs 3 or more errors, print: `"The dragon is becoming a debugging master!"`.

**Bonus 2:**
1. Write a function `checkCompletionStatus` that takes a boolean parameter `hasCompletedProject`.
2. Use conditionals to print:
   - If `hasCompletedProject` is `true`, print: `"The dragon has successfully completed its JavaScript project!"`
   - If `hasCompletedProject` is `false`, print: `"The dragon needs to finish its project!"`
3. Call this function using both `true` and `false` values to show the dragon's project completion status.

## Submission
Upon completion, run the following commands in your terminal:
```bash
git add .
git commit -m "Completed The Coding Dragon Lab"
git push origin master
