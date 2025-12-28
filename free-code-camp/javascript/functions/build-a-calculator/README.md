# Calculator

## Overview

In this challenge, you will build a simple JavaScript program that performs several basic mathematical operations such as addition, subtraction, multiplication, division, squaring, and finding square roots.

This project helps you practice:

* Declaring and defining functions
* Using parameters and return values
* Handling arithmetic operations in JavaScript
* Using conditional statements to handle special cases (like division by zero)
* Displaying output with `console.log()`

---

## Objective

Create individual functions to perform basic arithmetic operations and display the results in the console.

---

## User Stories

1. Create a function named `calculateSum(num1, num2)` that returns the sum of two numbers.

2. Create a function named `calculateDifference(num1, num2)` that returns the difference between two numbers.

3. Create a function named `calculateProduct(num1, num2)` that returns the product of two numbers.

4. Create a function named `calculateQuotient(num1, num2)` that returns the quotient when the first number is divided by the second.

   * If `num2` is `0`, return `"Error: Division by zero"` instead of performing the calculation.

5. Create a function named `calculateSquare(num)` that returns the square of a number.

6. Create a function named `calculateSquareRoot(num)` that returns the square root of a number using `Math.sqrt()`.

7. Use `console.log()` to display the results of calling each function with various example values.

---

## How It Works

Each function takes one or two numeric arguments and performs the specified operation.
The program then prints the results to the console so you can verify that each function behaves correctly.
A conditional check prevents division by zero errors in the `calculateQuotient` function.

---

## Technologies Used

* JavaScript (ES6)
* Node.js or any browser console environment

---

# ماشین‌حساب

## معرفی
در این چالش، شما یک برنامه ساده با جاوااسکریپت می‌سازید که چند عمل ریاضی پایه را انجام می‌دهد؛ از جمله جمع، تفریق، ضرب، تقسیم، توان دوم و محاسبه ریشه دوم.

این پروژه به شما کمک می‌کند مهارت‌های زیر را تمرین کنید:
- تعریف و اعلان تابع‌ها
- استفاده از پارامترها و مقدار بازگشتی
- انجام عملیات ریاضی در جاوااسکریپت
- استفاده از شرط‌ها برای مدیریت حالت‌های خاص (مثل تقسیم بر صفر)
- نمایش خروجی با استفاده از `console.log`

---

## هدف
ایجاد چند تابع مجزا برای انجام عملیات ریاضی پایه و نمایش نتیجه آن‌ها در کنسول.

---

## داستان‌های کاربر
- تابعی با نام `calculateSum(num1, num2)` ایجاد کنید که حاصل جمع دو عدد را برگرداند.
- تابعی با نام `calculateDifference(num1, num2)` ایجاد کنید که حاصل تفریق دو عدد را برگرداند.
- تابعی با نام `calculateProduct(num1, num2)` ایجاد کنید که حاصل ضرب دو عدد را برگرداند.
- تابعی با نام `calculateQuotient(num1, num2)` ایجاد کنید که حاصل تقسیم عدد اول بر عدد دوم را برگرداند.
  - اگر عدد دوم صفر بود، به‌جای انجام محاسبه، پیام  
    **«خطا: تقسیم بر صفر»**  
    را برگرداند.
- تابعی با نام `calculateSquare(num)` ایجاد کنید که توان دوم یک عدد را برگرداند.
- تابعی با نام `calculateSquareRoot(num)` ایجاد کنید که با استفاده از تابع محاسبه ریشه دوم، ریشه دوم عدد را برگرداند.
- با استفاده از `console.log`، نتیجه اجرای هر تابع را با چند مقدار نمونه نمایش دهید.

---

## نحوه عملکرد
هر تابع یک یا دو عدد به‌عنوان ورودی دریافت می‌کند و عملیات مشخص‌شده را روی آن‌ها انجام می‌دهد.  
سپس نتیجه در کنسول چاپ می‌شود تا بتوانید از صحت عملکرد توابع مطمئن شوید.  
در تابع تقسیم، یک شرط وجود دارد تا از بروز خطای تقسیم بر صفر جلوگیری شود.

---

## فناوری‌های استفاده‌شده
- جاوااسکریپت (نسخه ES6)
- محیط اجرای Node.js یا کنسول مرورگر

