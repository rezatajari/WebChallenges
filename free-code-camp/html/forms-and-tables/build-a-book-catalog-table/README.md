# Build a Book Catalog Table

## Objective
Create a **Book Catalog** webpage that presents a structured table of books with details such as title, author, genre, and publication year. The page should use **semantic HTML table elements** for clear organization and accessibility.

---

## Features

### Header Section
- Contains a main heading (`<h1>`) titled **“Book Catalog”** to introduce the page’s purpose.  
- The table columns are clearly defined with headers for each attribute:
  - **Title**
  - **Author**
  - **Genre**
  - **Publication Year**

---

### Table Structure

#### Table Head (`<thead>`)
- Contains a single header row (`<tr>`) with centered text.
- Defines the structure for book information columns.

#### Table Body (`<tbody>`)
- Contains multiple rows representing individual books.
- Each row lists:
  - Book **Title**
  - **Author** name
  - **Genre**
  - **Publication Year**

Example entries:
1. *How to Contribute to Open-Source Projects – A Handbook for Beginners* by **Hillary Nyakundi** (2023, Open Source)  
2. *Learn Linux for Beginners: From Basics to Advanced Techniques* by **Zaira Hira** (2024, Linux)  
3. *How to Learn to Code and Get a Developer Job* by **Quincy Larson** (2024, Learn To Code)  
4. *The Regular Expressions Book – RegEx for JavaScript Developers* by **Kolade Chris** (2023, Regular Expressions)  
5. *The Python Code Example Handbook* by **Farhan Hasin Chowdhury** (2023, Python)

#### Table Footer (`<tfoot>`)
- Includes a summary row that displays the **total number of books (5)**.
- Uses `colspan="4"` to span across all table columns for better visual alignment.

---

## How to Use
1. Open the **index.html** file in any web browser.  
2. View the complete list of books with their respective details.  
3. Use the table headers to understand each column’s meaning (Title, Author, Genre, Year).  
4. Review the footer to see the total number of books in the catalog.

---

## Technologies
- **HTML5**
- Semantic table structure:
  - `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`
- Inline styling for header alignment (`style="text-align: center;"`)

---

## Notes
- The table is **semantically structured** for clarity and accessibility.  
- The **header row** improves readability and supports screen readers.  
- The **footer row** provides a quick summary of the catalog contents.  
- This layout can easily be extended for dynamic or larger data sets.

---

## Challenge Tasks
- Add a new column for **ISBN numbers**.  
- Include **links** to each book’s official website or documentation page.  
- Apply **CSS styling** for alternating row colors to enhance readability.  
- Add a **search or filter input** to allow users to find books by genre or author.

---

<div dir="rtl">

# ساخت جدول فهرست کتاب‌ها

## هدف

ایجاد یک صفحهٔ وب برای **فهرست کتاب‌ها** که اطلاعاتی مانند عنوان کتاب، نویسنده، ژانر و سال انتشار را در قالب یک جدول منظم نمایش دهد.  
این صفحه باید از عناصر معنایی جدول در اچ‌تی‌ام‌ال استفاده کند تا **خوانایی** و **دسترسی‌پذیری** به‌خوبی رعایت شود.

---

## ویژگی‌ها

### بخش سربرگ

- شامل یک عنوان اصلی صفحه که هدف صفحه را معرفی می‌کند:  
  **فهرست کتاب‌ها**
- ستون‌های جدول به‌صورت واضح تعریف شده‌اند و هر کدام نمایانگر یک ویژگی هستند:
  - عنوان کتاب  
  - نویسنده  
  - ژانر  
  - سال انتشار  

---

## ساختار جدول

### سر جدول

- شامل یک ردیف عنوان برای ستون‌ها  
- متن عنوان ستون‌ها به‌صورت وسط‌چین نمایش داده می‌شود  
- ساختار کلی اطلاعات کتاب‌ها را مشخص می‌کند  

---

### بدنهٔ جدول

- شامل چندین ردیف است که هر کدام نمایندهٔ یک کتاب هستند  
- در هر ردیف اطلاعات زیر نمایش داده می‌شود:
  - عنوان کتاب  
  - نام نویسنده  
  - ژانر  
  - سال انتشار  

#### نمونه کتاب‌ها:

- راهنمای مشارکت در پروژه‌های متن‌باز – نوشتهٔ هیلاری نیاکوندی (۲۰۲۳، متن‌باز)  
- یادگیری لینوکس برای مبتدیان: از مبانی تا تکنیک‌های پیشرفته – نوشتهٔ زایرا هیرا (۲۰۲۴، لینوکس)  
- چگونه برنامه‌نویسی یاد بگیریم و شغل توسعه‌دهنده بگیریم – نوشتهٔ کوینسی لارسون (۲۰۲۴، یادگیری برنامه‌نویسی)  
- کتاب عبارات منظم – ویژهٔ توسعه‌دهندگان جاوااسکریپت – نوشتهٔ کولاده کریس (۲۰۲۳، عبارات منظم)  
- راهنمای مثال‌های کدنویسی پایتون – نوشتهٔ فرحان حسین چودهری (۲۰۲۳، پایتون)  

---

### پابرگ جدول

- شامل یک ردیف خلاصه برای نمایش **تعداد کل کتاب‌ها**  
- این ردیف کل ستون‌ها را پوشش می‌دهد تا از نظر بصری هماهنگ باشد  
- تعداد کل کتاب‌ها: **۵**

---

## نحوهٔ استفاده

- فایل صفحه را در هر مرورگر وب باز کنید  
- فهرست کامل کتاب‌ها و جزئیات آن‌ها را مشاهده کنید  
- با استفاده از عنوان ستون‌ها، مفهوم هر ستون را درک کنید  
- از پابرگ جدول برای مشاهدهٔ تعداد کل کتاب‌ها استفاده کنید  

---

## فناوری‌های استفاده‌شده

- اچ‌تی‌ام‌ال نسخهٔ پنج  
- ساختار معنایی جدول شامل:
  - جدول  
  - سر جدول  
  - بدنهٔ جدول  
  - پابرگ جدول  
  - ردیف‌ها و سلول‌ها  
- تراز کردن متن عنوان‌ها برای بهبود خوانایی  

---

## نکات

- جدول به‌صورت معنایی طراحی شده تا برای کاربران و ابزارهای کمکی قابل فهم باشد  
- ردیف عنوان باعث بهبود خوانایی و پشتیبانی بهتر از صفحه‌خوان‌ها می‌شود  
- پابرگ جدول یک خلاصهٔ سریع از محتوای فهرست ارائه می‌دهد  
- این ساختار به‌راحتی قابل گسترش برای داده‌های بزرگ‌تر یا پویا است  

---

## وظایف پیشنهادی چالش

- افزودن یک ستون جدید برای شمارهٔ شابک کتاب‌ها  
- اضافه‌کردن پیوند به وب‌سایت رسمی یا مستندات هر کتاب  
- اعمال سبک‌دهی برای ردیف‌های زوج و فرد جهت خوانایی بهتر  
- افزودن امکان جستجو یا فیلتر بر اساس ژانر یا نویسنده  

</div>

