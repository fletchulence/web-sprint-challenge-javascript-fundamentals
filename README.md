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

I feel like in our class we mostly used 

    - .map() is used for iterating thru a whole dataset and altering each part as needed. For example, if you need to update information in an array by adding 10 to everything (for some reason), but you didnt want to alter the previous data in any way, you could use the map function to auto-populate a new array with your new values. Also, .map() creates a newArray automatically, and doesnt change anything from the oldArray.

    - .filter is strictly for true and false values. If result yeilds true, filter will include it in the new array. If the result is false, filter will leave it out altogether. Say for example you want to go to a vacation spot that has a beach and you want to learn a new language other than english while you are there and be immersed in the culture. You would use .filter and pass in beachOptions and englishSpeaking as arguments in a boolean return statment (beachOptions && !englishSpeaking). 
    .filter also creates a newArray automatically, and doesnt change anything from the oldArray.

    - .reduce, unlike the others above, is used to produce a SINGLE VALUE from the information of the array in question - meaning that it does not populate a new array on its own, and if you need to push this value to an array you will need to do so manually. 
    The use case for reduce is for addition/multiplication as it has what is reffered to as an accumulator as a parameter. This accumulator keeps track of all the data in the array and either adds or multiplies the data to produce the final value. It also has an initial value input which is how we are able to dictate where to begin our count. Usually we use 1 if we are multiplying and 0 if we are adding(...cant use zero for multiplying bc then you would just get 0...).

2. Explain the difference between a callback and a higher order function.

please reference [(/Users/davidfletcher/Desktop/web-sprint-challenge-javascript-fundamentals/index.js)]

 simply put:
    - callback is a function that gets passed INTO another function as an attribute
    - higherOrder functions are functions which accept callback functions as arguments

    Basically, the idea is that the higher order function will 

3. Explain what a closure is.

    Closure is similar to what's happening in task 1! I can go into more detail though... Closure is the description of a function that

4. Describe the four principles of the 'this' keyword.

    1. explicit -
    2. implicit -
    3. window - 
    4. new -

5. Why do we need super() in an extended class?

    super() is used in Child classes. It is used as a replacement in ES6 which made classes (in my opinon) way easier to work with. It references the attributes that come from the Parent, just like .call does for prototypes

    the super() call is going to set all of the parent's properties onto it's child

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

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

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

