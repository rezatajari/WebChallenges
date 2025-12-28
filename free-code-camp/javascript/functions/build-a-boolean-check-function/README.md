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

---

# تابع بررسی مقدار بولی

## معرفی
در این چالش، شما یک تابع ساده در جاوااسکریپت می‌سازید که بررسی می‌کند آیا یک مقدار ورودی، از نوع مقدار بولی اولیه است یا نه.  
مقادیر بولی اولیه در جاوااسکریپت فقط شامل **درست** و **نادرست** هستند.

این پروژه به شما کمک می‌کند تا مهارت‌های زیر را تمرین کنید:
- درک انواع داده در جاوااسکریپت
- استفاده از عملگر `typeof`
- بازگرداندن مقدار بولی از توابع
- نوشتن منطق شرطی ساده و خوانا

---

## هدف
ایجاد تابعی که تشخیص دهد آیا ورودی داده‌شده یک مقدار بولی اولیه (درست یا نادرست) است یا خیر.

---

## داستان‌های کاربر
- تابعی با نام `booWho` تعریف کنید که یک ورودی دریافت می‌کند.
- اگر آرگومان ورودی از نوع بولی اولیه باشد، تابع باید مقدار **درست** برگرداند.
- اگر آرگومان از هر نوع دیگری باشد (رشته، عدد، شیء، تهی، تعریف‌نشده، آرایه و غیره)، تابع باید مقدار **نادرست** برگرداند.

---

## نحوه عملکرد
این تابع با استفاده از عملگر `typeof` نوع داده‌ی ورودی را بررسی می‌کند.  
اگر نتیجه بررسی برابر با نوع بولی باشد، خروجی **درست** خواهد بود؛ در غیر این صورت، خروجی **نادرست** برگردانده می‌شود.

این روش تضمین می‌کند که فقط مقادیر بولی واقعی (درست و نادرست) پذیرفته شوند.

---

## فناوری‌های استفاده‌شده
- جاوااسکریپت (نسخه ES6)
- محیط اجرای Node.js یا کنسول مرورگر

---

## هدف نهایی
با اجرای کد، تمام آزمون‌ها باید با موفقیت عبور کنند و تابع بتواند به‌درستی تشخیص دهد که آیا مقدار ورودی، بولی اولیه است یا خیر.
