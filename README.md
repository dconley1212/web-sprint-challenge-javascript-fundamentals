# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge.

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results

### Commits

Set up codegrade early and commit your code regularly and meaningfully.

## Interview Questions

### (please edit this file and write your answer below each question.)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each.

.map method will loop through each index of an array it was given and it will create a new array by converting the array data at each index through what's being returned in the .map method. A use case would be extracting specific information from a data set to show it more clearly.

.reduce method will loop through an array and it will find the value you are looking at each index and add the value to the accumulating sum after each index until you have looped through each index of the entire array. It will give you a single value of all the values at each index added together in the array. Use case would be to help you get the total value of something so that you can then manipulate it to find important data like average test score for example.

.filter is a method that will loop through an array it is given and check each index of the array for what equates to being true in the method. If the index of the array equates to being true for the filer method then it is included in the new array. Use case would be removing repeated values.

2. Explain the difference between a callback and a higher order function.
   The callback function is a function used as an argument in a higher order function and a higher order function is a function that accepts a callback function as one of its arguments.

3. Explain what a closure is.

Closure is when a nested(inner) function will reach outside of its function and will grab a variable's value that it couldn't find within it's own scope. The outer function can't pull variables from a nested function. It is a one way street where only the nested function can pull a variable value from outside its scope.

4. Describe the four principles of the 'this' keyword.
   Window Binding: if 'this' isn't given any context it will return window, the global object in node or undefined in strict mode.

Implicit Binding: applies to objects with methods, and it's when a function is invoked you should look to the left of the dot to know what 'this' refers to.

Explicit Binding: it's when we tell a function what the 'this' keyword should be using .call, .apply, or .bind. .Call is when a function is invoked immediately and the arguments are passed 1 by 1. .Apply is when a function is invoked immediately and pass the arguments as an array. And .bind you pass in the arguments 1 by 1 and it won't be invoked immediately, but it will create a new function that can be used later.

New Binding: It is when a function is invoked with a new keyword and the this keyword inside that function is bound to the new object being constructed. When a function is invoked as a constructor function using the new keyword, this points to the new object that's created.

5. Why do we need super() in an extended class?
   We need super() because it helps us inherit all of the properties from the parent constructor function.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade.

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start`
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources

[Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
