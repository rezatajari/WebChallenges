# Fortune Teller

## Overview

In this challenge, you will build a simple Fortune Teller application using JavaScript.
The program will randomly select one of five fortune messages and display it to the user.

This project helps you practice:

* Declaring and assigning variables
* Generating random numbers with `Math.random()` and `Math.floor()`
* Using conditional logic with a `switch` statement
* Displaying results with `console.log()`

---

## Objective

Create five different fortunes and have the program display one of them at random each time it runs.

---

## User Stories

1. Initialize five variables named fortune1, fortune2, fortune3, fortune4, and fortune5.
   Each variable should hold a unique fortune message as a string.

2. Generate a random number between 1 and 5 (inclusive) and store it in a variable called randomNumber.

3. Create a variable named selectedFortune.
   Assign one of the five fortunes to this variable based on the value of randomNumber.

4. Display the selected fortune in the console output.

---

## How It Works

The program generates a random number between 1 and 5.
Each number corresponds to one of the five fortune messages.
A `switch` statement determines which fortune to display based on that number.
Finally, the selected fortune is printed to the console for the user to read.

---

## Example Output

Your fortune for today:
A pleasant surprise is waiting for you very soon.

---

## Technologies Used

* JavaScript (ES6)
* Node.js or any browser console environment

