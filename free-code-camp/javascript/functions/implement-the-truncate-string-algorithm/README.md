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

---

# کوتاه‌کردن یک رشته

## معرفی
در این چالش، شما یک تابع جاوااسکریپتی می‌سازید که **یک رشته را تا طول مشخصی کوتاه می‌کند**.  
کوتاه‌کردن رشته یعنی اگر طول متن از حد تعیین‌شده بیشتر بود، آن را بریده و در انتها `...` اضافه کنیم.

این تمرین به شما کمک می‌کند مهارت‌های زیر را تمرین کنید:
- نوشتن تابع با پارامتر
- استفاده از شرط‌ها (`if / else`)
- کار با رشته‌ها و متدهای رشته‌ای

---

## هدف
ساخت تابعی که یک **رشته** و یک **عدد** دریافت کند و در صورت نیاز، نسخه کوتاه‌شده رشته را برگرداند.

---

## قوانین کوتاه‌کردن
- اگر طول رشته **کمتر یا مساوی** عدد داده‌شده باشد:
  - رشته بدون تغییر برگردانده می‌شود.
- اگر طول رشته **بیشتر** از عدد داده‌شده باشد:
  - رشته تا همان طول مشخص بریده می‌شود
  - سپس `...` به انتهای آن اضافه می‌شود

---

## داستان‌های کاربر
- تابعی به نام `truncateString` تعریف کنید که دو ورودی بگیرد:
  1. رشته‌ای که باید کوتاه شود
  2. عددی که حداکثر طول مجاز رشته را مشخص می‌کند
- داخل تابع:
  - طول رشته را بررسی کنید
  - اگر طول رشته بیشتر از عدد بود:
    - رشته را کوتاه کنید
    - `...` به انتهای آن اضافه کنید
  - اگر کوتاه‌تر یا مساوی بود:
    - همان رشته را برگردانید
- در نهایت، رشته نهایی را برگردانید

---

## رفتار نمونه
- `"Hello, world"` با طول ۵ → `"Hello..."`
- `"Hi"` با طول ۵ → `"Hi"`

---

## هدف نهایی
در پایان این پروژه، برنامه شما باید:
- تشخیص دهد چه زمانی نیاز به کوتاه‌کردن رشته وجود دارد
- رشته‌های بلندتر از حد مجاز را کوتاه کند و `...` اضافه نماید
- رشته‌های کوتاه یا هم‌اندازه را بدون تغییر برگرداند
