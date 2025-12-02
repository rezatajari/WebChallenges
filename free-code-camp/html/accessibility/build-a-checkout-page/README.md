
# Build a Checkout Page

## Goal

Build a functional checkout page that satisfies a strict set of structural, semantic, and accessibility-related user stories. The project must pass all automated tests defined in the challenge.

---

## User Stories to Satisfy

### Page Structure

1. The page must contain exactly one top-level heading containing the text "Checkout".
2. Immediately after that heading, there must be **two section elements**.

### First Section: Cart Summary

3. The first section must contain a second-level heading with the text "Your Cart".
4. The first section must contain at least one image with descriptive alternate text.

### Second Section: Payment Form

5. The second section must contain a second-level heading with the text "Payment Information".
6. A form element must appear inside this second section.

### Required Form Fields

Inside the form, the following must exist:

7. An input for the cardholder name

   * Must have **id="card-name"** and **name="card-name"**
   * Must be of type **text**
   * Must have a label correctly associated with it

8. An input for the card number

   * Must have **id="card-number"** and **name="card-number"**
   * Must be of type **text**
   * Must have a label correctly associated with it

9. At least **two input elements must include the required attribute**.

10. Each required input's label must contain:

    * A visually-displayed star symbol
    * That star must be wrapped inside a span
    * The span must have **aria-hidden="true"**

### Card Number Help Text

11. A help paragraph with:

    * **id="card-number-help"**
    * Non-empty text explaining the required card-number format
    * Must appear *immediately after* the card number input
    * The card-number input must reference it using **aria-describedby**

---

## Common Mistakes to Avoid

* Forgetting the **form** element entirely.
* Not matching the required **id** and **name** attributes exactly.
* Using `type="number"` for card numbers (tests expect **text**).
* Putting the star (*) outside the label instead of inside it.
* Forgeting `aria-hidden="true"` on star spans.
* Adding help text in the wrong position (it must be directly after the card number input).
* Using labels that reference the wrong `for` IDs.
* Omitting required attributes on at least two inputs.

---

## Summary of What You Need to Fix in Your Version

Your current implementation must be adjusted to meet these requirements:

* The payment inputs must be inside a **form**.
* The cardholder name input must use `card-name` as both id and name.
* The card number input must use `card-number` as both id and name and use `type="text"`.
* All required inputs must include a star inside a span with `aria-hidden="true"`.
* The `<p>` describing card number format must have the id `card-number-help`.
* The card-number input needs `aria-describedby="card-number-help"`.

Once these corrections are applied, the tests will pass.

---

<div dir="rtl">

# ساخت صفحهٔ نهایی خرید

## هدف  
در این تمرین باید یک صفحهٔ نهایی خرید بسازید که تمام قوانین ساختاری، معنایی و الزامات دسترس‌پذیری را رعایت کند. این صفحه باید تمام تست‌های خودکار تعریف‌شده در چالش را با موفقیت پشت سر بگذارد.

---

## سناریوهای مورد انتظار

### ساختار صفحه  
• صفحه باید دقیقاً یک عنوان سطح یک داشته باشد که شامل متن «Checkout» باشد.  
• بلافاصله بعد از این عنوان باید دو عنصر بخش (section) قرار بگیرد.

---

### بخش اول: خلاصهٔ سبد خرید  
• باید یک عنوان سطح دو با متن «Your Cart» داشته باشد.  
• باید حداقل یک تصویر با متن جایگزین توصیفی داشته باشد.

---

### بخش دوم: فرم پرداخت  
• باید عنوان سطح دو با متن «Payment Information» داشته باشد.  
• باید یک فرم داخل این بخش قرار داشته باشد.

---

## فیلدهای الزامی فرم

### ورودی نام دارنده کارت  
داخل فرم باید یک ورودی شامل این ویژگی‌ها باشد:

• شناسه و نام ورودی:  
&nbsp;&nbsp;&nbsp;&nbsp;<code>id="card-name"</code>  
&nbsp;&nbsp;&nbsp;&nbsp;<code>name="card-name"</code>

• نوع ورودی:  
&nbsp;&nbsp;&nbsp;&nbsp;<code>type="text"</code>

• باید یک برچسب (label) درست و مرتبط با آن قرار گیرد.

---

### ورودی شماره کارت  
• شناسه و نام ورودی:  
&nbsp;&nbsp;&nbsp;&nbsp;<code>id="card-number"</code>  
&nbsp;&nbsp;&nbsp;&nbsp;<code>name="card-number"</code>

• نوع ورودی:  
&nbsp;&nbsp;&nbsp;&nbsp;<code>type="text"</code>

• باید یک برچسب درست و مرتبط داشته باشد.

---

### الزامات مربوط به فیلدهای لازم  
حداقل دو ورودی در فرم باید ویژگی required داشته باشند.

برچسب ورودی‌های لازم باید شامل موارد زیر باشد:

• یک ستارهٔ قابل مشاهده  
• ستاره باید داخل یک عنصر <code>&lt;span&gt;</code> باشد  
• این span باید ویژگی زیر را داشته باشد:  
&nbsp;&nbsp;&nbsp;&nbsp;<code>aria-hidden="true"</code>

---

## متن راهنمای شماره کارت  

پس از ورودی شماره کارت باید یک پاراگراف قرار بگیرد که دارای ویژگی زیر باشد:

• <code>id="card-number-help"</code>  
• شامل یک متن غیرخالی برای توضیح فرمت صحیح شماره کارت  
• باید بلافاصله بعد از ورودی شماره کارت قرار بگیرد

ورودی شماره کارت باید ویژگی زیر را داشته باشد:

• <code>aria-describedby="card-number-help"</code>

---

## اشتباهات متداول  

• حذف فرم به‌طور کامل  
• اشتباه نوشتن مقادیر id و name  
• استفاده از type="number" برای شماره کارت  
• قرار دادن ستاره خارج از برچسب  
• فراموش کردن aria-hidden="true"  
• قرار دادن متن راهنما در جای اشتباه  
• اتصال label به شناسهٔ اشتباه  
• نداشتن ویژگی required روی حداقل دو ورودی  

---

## خلاصهٔ موارد لازم برای اصلاح نسخهٔ شما  

• همهٔ ورودی‌های پرداخت باید داخل فرم باشند.  
• ورودی نام دارنده کارت باید از <code>id="card-name"</code> و <code>name="card-name"</code> استفاده کند.  
• شماره کارت باید از <code>id="card-number"</code> و <code>name="card-number"</code> استفاده کند و نوع آن text باشد.  
• همهٔ ورودی‌های لازم باید ستارهٔ داخل span با <code>aria-hidden="true"</code> داشته باشند.  
• متن توضیح شماره کارت باید شناسهٔ <code>id="card-number-help"</code> داشته باشد.  
• ورودی شماره کارت باید ویژگی <code>aria-describedby="card-number-help"</code> داشته باشد.

با اعمال این اصلاحات، تمام تست‌ها با موفقیت عبور خواهند کرد.

</div>
