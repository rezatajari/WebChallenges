# Card Counting Assistant

## Overview

In this challenge, you will build a **Card Counting Assistant** for the casino game **Blackjack**.
Card counting is a strategy used by players to determine whether they have an advantage on the next hand by keeping track of the relative number of high and low cards remaining in the deck.

The program helps you practice:

* Declaring and using **global variables**
* Writing **functions** with parameters
* Using **conditional logic** (`if`, `switch`)
* Returning **formatted strings** based on dynamic values

---

## Objective

Create a function that tracks cards and suggests whether the player should **bet high** or **hold** based on the current count of cards seen.

---

## How Card Counting Works

1. Each card in the deck affects a global count variable:

   * **Low cards (2, 3, 4, 5, 6)** → increase count by 1
   * **Neutral cards (7, 8, 9)** → count stays the same
   * **High cards (10, "J", "Q", "K", "A")** → decrease count by 1

2. The **count** represents the balance between high and low cards remaining.

3. A **positive count** indicates the player has an advantage → bet high (`Bet`)
   A **zero or negative count** indicates no advantage → bet low or hold (`Hold`)

---

## User Stories

1. Declare a global variable named `count` using `let` and initialize it to 0.
2. Create a function named `cc` that receives a single parameter `card`.
3. Update the global `count` variable based on the value of `card`.
4. The function should return a string in the format:

   ```
   "<count> <Action>"
   ```

   * `<count>` = current value of the global count variable
   * `<Action>` = `"Bet"` if count is positive, `"Hold"` if count is zero or negative

---

## Example Flow

* The player sees a 2 → count increases
* The player sees a "K" → count decreases
* The function returns the current count and recommended action for each card seen

---

## Technologies Used

* JavaScript (ES6)
* Node.js or browser console environment

---

## Goal

By the end of this project, your program should be able to **track cards one by one**, update a global count variable, and return a string indicating whether the player should **bet** or **hold** based on the current count.

---

# دستیار شمارش کارت

## معرفی
در این چالش، شما یک **دستیار شمارش کارت** برای بازی کازینویی بلک‌جک می‌سازید.  
شمارش کارت یک استراتژی است که بازیکنان با آن تشخیص می‌دهند آیا در دست بعدی بازی برتری دارند یا نه؛ این کار با پیگیری تعداد کارت‌های بالا و پایین باقی‌مانده در دسته کارت انجام می‌شود.

این پروژه به شما کمک می‌کند مهارت‌های زیر را تمرین کنید:
- تعریف و استفاده از متغیرهای سراسری
- نوشتن تابع با پارامتر
- استفاده از منطق شرطی (if و switch)
- برگرداندن رشته‌های قالب‌بندی‌شده بر اساس مقادیر پویا

---

## هدف
ایجاد تابعی که کارت‌ها را یکی‌یکی دنبال کند و بر اساس شمارش فعلی، پیشنهاد دهد که بازیکن **شرط بالا ببندد** یا **صبر کند**.

---

## نحوه کار شمارش کارت
هر کارت در دسته کارت، روی یک متغیر سراسری به نام شمارش اثر می‌گذارد:

- کارت‌های پایین (۲، ۳، ۴، ۵، ۶) → افزایش شمارش به اندازه ۱
- کارت‌های خنثی (۷، ۸، ۹) → شمارش بدون تغییر
- کارت‌های بالا (۱۰، سرباز، بی‌بی، شاه، آس) → کاهش شمارش به اندازه ۱

مقدار شمارش نشان‌دهنده تعادل بین کارت‌های بالا و پایین باقی‌مانده است.

- اگر شمارش **مثبت** باشد → بازیکن برتری دارد → شرط بالا ببند
- اگر شمارش **صفر یا منفی** باشد → برتری وجود ندارد → صبر کن

---

## داستان‌های کاربر
- یک متغیر سراسری با نام `count` با استفاده از `let` تعریف کرده و مقدار اولیه آن را صفر قرار دهید.
- تابعی با نام `cc` ایجاد کنید که یک ورودی به نام `card` دریافت کند.
- مقدار متغیر سراسری `count` را بر اساس کارت ورودی به‌روزرسانی کنید.
- تابع باید یک رشته با قالب زیر برگرداند:

