# Build a Final Exams Table

## Objective
Create a semantic HTML table that displays **students’ final grades** for a Calculus course. The table should be clearly structured with appropriate use of `<thead>`, `<tbody>`, and `<tfoot>` elements for readability and organization.

---

## Features

### Header Section
- The table includes a **caption**: “Calculus Final Exam Grades” to describe the table’s purpose.
- The `<thead>` element defines the **column headers**:
  - Last Name  
  - First Name  
  - Grade  

---

### Body Section
- The `<tbody>` contains multiple rows (`<tr>`) listing students and their corresponding grades.
- Each row includes:
  - Last Name (`<td>`)
  - First Name (`<td>`)
  - Grade (`<td>`)

Example rows:
- Davis, Alex — 54  
- Doe, Samantha — 92  
- Rodriguez, Marcus — 88  
- Thompson, Jane — 77  
- Williams, Natalie — 83  

---

### Footer Section
- The `<tfoot>` contains a summary row displaying the **average grade**.
- The `colspan="2"` attribute is used to merge two cells for the label “Average Grade”.
- The average grade shown is **78.8**.

---

## How to Use
1. Open the **index.html** file in any web browser.  
2. View the structured table showing students’ names and final grades.  
3. Review the **average grade** at the bottom of the table for a summary of performance.

---

## Technologies
- **HTML5**
- Semantic table elements:
  - `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`

---

## Notes
- The table uses **semantic HTML** to improve accessibility and structure.  
- The **caption** provides context for screen readers.  
- The **footer** summarizes data, reinforcing good data presentation practices.  
- Ideal for representing tabular data such as exam results, attendance, or reports.

---

## Challenge Tasks
- Add a new column for **Student ID**.  
- Highlight grades below 60 using inline CSS or a class.  
- Add a row showing the **highest and lowest grades** in the class.

---

<div dir="rtl">

# ساخت جدول نمرات امتحان نهایی

## هدف

ایجاد یک جدول اچ‌تی‌ام‌ال **معنایی** که نمرات نهایی دانشجویان یک درس **حسابان** را نمایش دهد.  
این جدول باید با استفادهٔ درست از بخش‌های **سر جدول، بدنه و پابرگ** طراحی شود تا خوانایی و نظم داده‌ها به‌خوبی حفظ شود.

---

## ویژگی‌ها

### بخش عنوان جدول

- جدول دارای یک عنوان توضیحی است با متن:  
  **نمرات امتحان نهایی حسابان**
- این عنوان هدف جدول را مشخص می‌کند و به درک بهتر محتوا کمک می‌کند، به‌ویژه برای ابزارهای کمکی.

---

## ساختار جدول

### سر جدول

- بخش سر جدول ستون‌های اصلی را تعریف می‌کند:
  - نام خانوادگی  
  - نام  
  - نمره  

این بخش ساختار کلی اطلاعات را مشخص کرده و باعث می‌شود داده‌ها قابل فهم‌تر شوند.

---

### بدنهٔ جدول

- بدنه شامل چندین ردیف است که هر کدام مربوط به یک دانشجو و نمرهٔ نهایی اوست.
- در هر ردیف اطلاعات زیر وجود دارد:
  - نام خانوادگی  
  - نام  
  - نمره  

#### نمونه ردیف‌ها:

- دیویس، الکس — ۵۴  
- دو، سامانتا — ۹۲  
- رودریگز، مارکوس — ۸۸  
- تامپسون، جین — ۷۷  
- ویلیامز، ناتالی — ۸۳  

---

### پابرگ جدول

- پابرگ شامل یک ردیف خلاصه است که **میانگین نمرات** را نمایش می‌دهد.
- برای برچسب «میانگین نمره»، دو خانهٔ جدول با هم ادغام شده‌اند.
- مقدار میانگین نمایش‌داده‌شده: **۷۸٫۸**

---

## نحوهٔ استفاده

- فایل صفحه را در هر مرورگر وب باز کنید.
- جدول منظم شامل نام دانشجویان و نمرات نهایی آن‌ها را مشاهده کنید.
- میانگین نمرهٔ کلاس را در انتهای جدول بررسی کنید تا دید کلی از عملکرد دانشجویان داشته باشید.

---

## فناوری‌های استفاده‌شده

- اچ‌تی‌ام‌ال نسخهٔ پنج  
- عناصر معنایی جدول:
  - جدول  
  - عنوان جدول  
  - سر جدول  
  - بدنهٔ جدول  
  - پابرگ جدول  
  - ردیف‌ها و سلول‌ها  

---

## نکات

- استفاده از ساختار معنایی باعث بهبود **دسترسی‌پذیری** و **سازمان‌دهی اطلاعات** می‌شود.
- عنوان جدول به صفحه‌خوان‌ها کمک می‌کند تا زمینهٔ داده‌ها را بهتر درک کنند.
- پابرگ جدول خلاصه‌ای مفید از داده‌ها ارائه می‌دهد.
- این نوع جدول برای نمایش نمرات، حضور و غیاب، گزارش‌ها و داده‌های مشابه بسیار مناسب است.

---

## وظایف پیشنهادی چالش

- افزودن یک ستون جدید برای **شمارهٔ دانشجویی**
- برجسته‌کردن نمرات کمتر از ۶۰ با استفاده از سبک‌دهی
- اضافه‌کردن یک ردیف برای نمایش **بیشترین و کمترین نمرهٔ کلاس**

</div>

