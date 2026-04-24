# Truncate a String

## Overview

In this challenge, you will create a JavaScript function that **truncates a string** to a specified length.
Truncating a string means shortening it and optionally adding `...` at the end if the original string is longer than the specified length.

This project helps you practice:

* Writing functions with parameters
* Using conditional logic (`if/else`)
* Manipulating strings and using string methods

---

## Objective

Build a function that receives a string and a number as input and returns a truncated version of the string if needed.

---

## Rules for Truncating

1. If the length of the string is **less than or equal** to the given number, return the string **unchanged**.
2. If the length of the string is **greater** than the given number:

   * Cut the string to the specified length
   * Append `...` at the end of the truncated string

---

## User Stories

1. Create a function named `truncateString` that accepts **two arguments**:

   * The first argument: the string to truncate
   * The second argument: a number representing the maximum length of the string
2. Inside the function, check the length of the string.
3. If the string is longer than the number, truncate it and add `...`.
4. If the string is shorter than or equal to the number, return it as is.
5. Return the resulting string.

---

## Example Behavior

* `"Hello, world"` truncated to length 5 → `"Hello..."`
* `"Hi"` truncated to length 5 → `"Hi"`

---

## Goal

By the end of this project, your program should:

