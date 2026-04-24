# Boolean Check Function

## Overview

In this challenge, you will build a simple JavaScript function that checks whether a given value is classified as a **boolean primitive**.
Boolean primitives in JavaScript are only `true` and `false`.

This project helps you practice:

* Understanding JavaScript data types
* Using the `typeof` operator
* Returning boolean values from functions
* Writing clean and concise conditional logic

---

## Objective

Create a function that determines if a given input is a boolean primitive (`true` or `false`).

---

## User Stories

1. Define a function named `booWho` that receives one argument.
2. If the argument passed to the function is a boolean primitive, the function should return `true`.
3. If the argument is any other data type (string, number, object, null, undefined, array, etc.), the function should return `false`.

---

## How It Works

The function uses the `typeof` operator to check the data type of the input value.
If `typeof checkValue` equals `'boolean'`, the function returns `true`; otherwise, it returns `false`.

This approach ensures that only true boolean primitives (`true` and `false`) are accepted.

## Technologies Used

* JavaScript (ES6)
* Node.js or any browser console environment

---

## Goal

When you run your code, all tests should pass by correctly identifying whether the given input is a boolean primitive.
