# Loan Qualification Checker

## Overview

In this challenge, you will build a **Loan Qualification Checker App** using JavaScript conditionals.
The program determines whether an applicant qualifies for a **duplex**, **condo**, or **car loan** based on their **annual income** and **credit score**.

A **credit score** represents how reliable someone is when it comes to managing borrowed money — higher scores indicate better creditworthiness.

This project helps you practice:

* Using conditional statements (`if`, `else if`, `else`)
* Comparing numeric values with relational operators (`>=`, `<`)
* Working with functions that return specific results
* Declaring and testing multiple variables

---

## Objective

Create a program that checks an applicant’s loan eligibility based on minimum income and credit score requirements for different loan types.
Return the correct qualification message for each scenario.

---

## User Stories

1. Create variables that store the minimum income and credit score requirements for each loan type:

   * `minIncomeForDuplex` = 60000
   * `minCreditScoreForDuplex` = 700
   * `minIncomeForCondo` = 45000
   * `minCreditScoreForCondo` = 680
   * `minIncomeForCar` = 30000
   * `minCreditScoreForCar` = 650

2. Define a function named `getLoanMessage` that takes two arguments:

   * `annualIncome`
   * `creditScore`

3. Inside the function:

   * If both values meet or exceed the duplex requirements, return
     `"You qualify for a duplex, condo, and car loan."`
   * Else if both values meet or exceed the condo requirements, return
     `"You qualify for a condo and car loan."`
   * Else if both values meet or exceed the car requirements, return
     `"You qualify for a car loan."`
   * Otherwise, return
     `"You don't qualify for any loans."`

4. Outside the function:

   * Create four variables that call the function with different inputs:

     * `duplexLoanMsg = getLoanMessage(85000, 850)`
     * `condoLoanMsg = getLoanMessage(65000, 690)`
     * `carLoanMsg = getLoanMessage(45000, 660)`
     * `noLoanMsg = getLoanMessage(25000, 550)`

5. Log each variable to the console to display the result.

---

## How It Works

1. The program uses conditional logic to compare the applicant’s income and credit score against predefined thresholds.
2. Depending on which thresholds are met, the function returns the appropriate qualification message.
3. The results are then printed to the console to show which loan(s) the applicant qualifies for.

---

## Technologies Used

* JavaScript (ES6)
* Node.js or browser console environment

---

## Goal

When you run the program, it should correctly determine and display which type of loan(s) each applicant qualifies for — or inform them that they don’t qualify for any.

---

# بررسی شرایط دریافت وام

## معرفی
در این چالش، شما یک برنامه بررسی شرایط دریافت وام با استفاده از **جاوااسکریپت** می‌سازید.  
این برنامه مشخص می‌کند که آیا یک متقاضی بر اساس **درآمد سالانه** و **امتیاز اعتباری** خود واجد شرایط دریافت وام هست یا نه.

امتیاز اعتباری نشان‌دهنده میزان اعتبار فرد در بازپرداخت بدهی‌هاست؛ هرچه این عدد بالاتر باشد، اعتمادپذیری مالی فرد بیشتر است.

این تمرین به شما کمک می‌کند مهارت‌های زیر را تمرین کنید:
- استفاده از شرط‌ها (if / else if / else)
- مقایسه مقادیر عددی با عملگرهای منطقی
- کار با توابعی که مقدار برمی‌گردانند
- تعریف و بررسی چند متغیر به‌صورت هم‌زمان

---

## هدف
ساخت برنامه‌ای که شرایط دریافت وام را بر اساس حداقل درآمد و حداقل امتیاز اعتباری برای انواع مختلف وام بررسی کند و پیام مناسب را برگرداند.

---

## شرایط وام‌ها
حداقل شرایط برای هر نوع وام به شکل زیر است:

### وام دوبلکس
- حداقل درآمد سالانه: ۶۰٬۰۰۰
- حداقل امتیاز اعتباری: ۷۰۰

### وام کاندو
- حداقل درآمد سالانه: ۴۵٬۰۰۰
- حداقل امتیاز اعتباری: ۶۸۰

### وام خودرو
- حداقل درآمد سالانه: ۳۰٬۰۰۰
- حداقل امتیاز اعتباری: ۶۵۰

---

## داستان‌های کاربر
- متغیرهایی برای ذخیره حداقل درآمد و امتیاز اعتباری هر نوع وام تعریف کنید.
- تابعی به نام `getLoanMessage` بسازید که دو ورودی بگیرد:
  - درآمد سالانه
  - امتیاز اعتباری
- داخل تابع:
  - اگر شرایط وام دوبلکس برقرار بود → پیام دریافت هر سه وام (دوبلکس، کاندو، خودرو) را برگردانید.
  - در غیر این صورت، اگر شرایط وام کاندو برقرار بود → پیام دریافت وام کاندو و خودرو را برگردانید.
  - در غیر این صورت، اگر شرایط وام خودرو برقرار بود → پیام دریافت وام خودرو را برگردانید.
  - اگر هیچ‌کدام برقرار نبود → پیام عدم واجد شرایط بودن برای هیچ وامی را برگردانید.
- خارج از تابع:
  - چند متغیر تعریف کنید که تابع را با ورودی‌های مختلف فراخوانی می‌کنند.
  - نتیجه هر کدام را در کنسول نمایش دهید.

---

## نحوه عملکرد
برنامه با استفاده از منطق شرطی، درآمد و امتیاز اعتباری متقاضی را با مقادیر حداقل مقایسه می‌کند.  
بسته به این‌که کدام شرایط برقرار باشد، پیام مناسب برگردانده می‌شود و نتیجه در کنسول نمایش داده خواهد شد.

---

## هدف نهایی
در پایان این چالش، برنامه شما باید:
- به‌درستی تشخیص دهد هر فرد واجد شرایط کدام نوع وام است.
- پیام واضح و درست برای هر حالت نمایش دهد.
- در صورتی که شرایط هیچ وامی فراهم نبود، این موضوع را به‌درستی اعلام کند.

