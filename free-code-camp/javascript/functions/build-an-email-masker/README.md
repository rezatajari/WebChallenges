# Email Masker

## Overview

In this challenge, you will build a function that masks the **username part of an email address** with asterisks (`*`).
Masking is a technique used to hide sensitive information while keeping some identifiable parts visible — for example, showing only the first and last character of an email username.

This project helps you practice:

* Working with string manipulation in JavaScript
* Using built-in methods like `slice()`, `repeat()`, and `indexOf()`
* Constructing and returning formatted strings
* Declaring and using variables both inside and outside of functions

---

## Objective

Create a function that takes an email address as input, replaces the characters between the first and last letters of the username with asterisks, and returns the masked email address.

---

## User Stories

1. Define a function named `maskEmail` that accepts one argument, `email`.
2. Inside the function, separate the username (part before `@`) and the domain (part after `@`).
3. Keep only the first and last character of the username visible, masking the rest with asterisks (`*`).
4. Combine the masked username with the domain and return the new masked email.
5. Outside the function, declare a variable named `email` and assign it a valid email address.
6. Call the `maskEmail` function with the `email` variable and print the result to the console.

---

## How It Works

1. The `@` symbol is used to determine where to split the email.
2. The username is isolated using string slicing methods.
3. The masked portion is created by repeating the asterisk character for the appropriate number of times.
4. The masked username and domain are then concatenated into a single string.
5. The result is an email address that hides the sensitive part of the username while keeping it recognizable.

---

## Technologies Used

* JavaScript (ES6)
* Node.js or any browser console environment

---

## Goal

When you run your program, it should output a masked version of any given email address, keeping the first and last letters of the username visible while replacing the middle characters with asterisks.
