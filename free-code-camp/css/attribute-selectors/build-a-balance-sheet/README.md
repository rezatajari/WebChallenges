# CSS Pseudo Selectors

**Goal:** Build a financial balance sheet that is both visually appealing and fully accessible to all users, including those using screen readers.

---

## Task

Create a balance sheet page that includes:

* **A header with company name and “Balance Sheet” title**, structured so screen readers announce them in logical order.
* **Year indicators** displayed at the top, hidden from screen readers (`aria-hidden="true"`) and sticky during scrolling.
* **Three separate tables** for Assets, Liabilities, and Net Worth.
* **Row and cell structure** optimized for accessibility:

  * `<th>` for header cells
  * `<td>` for data cells
  * `<tr class="total">` for total rows with numeric values aligned to the right
* **Screen reader-only text (`sr-only`)** for visually hidden year and category labels.
* **Responsive table layout** with fixed minimum and maximum cell widths.
* **CSS styling** for readability, alternating row backgrounds, hover effects, and proper spacing.

---

## Requirements

* Create `index.html` and `styles.css`.
* Use **semantic HTML** (`main`, `section`, `table`, `caption`, `thead`, `tbody`, `th`, `td`).
* Include **screen reader accessibility**: `sr-only` class and `aria-hidden` attributes.
* Style tables so that:

  * Numeric columns are **right-aligned**
  * Total rows are visually distinguished and have a hover highlight
  * Current-year values are italicized
* Ensure the **header text order is reversed visually** with CSS but remains logical for screen readers.
* Sticky years bar remains on top of the tables during scrolling.

---

## Success Checklist

* [ ] Header displays company name and “Balance Sheet” visually reversed but announced correctly by screen readers
* [ ] `#years` bar is sticky, aligned to the right, and hidden from screen readers
* [ ] All tables have `<caption>` and proper `<thead>` / `<tbody>` structure
* [ ] `<th>` and `<td>` are correctly used, with `tr.total` rows right-aligned and highlighted on hover
* [ ] `sr-only` text is used for hidden years and category labels
* [ ] Table cells have fixed widths with `min-width` and `max-width` for consistent layout
* [ ] Alternate row backgrounds and padding improve readability
* [ ] CSS ensures tables are responsive and visually neat across screen sizes

---

<div dir="rtl">

# CSS Pseudo Selectors – ترازنامه مالی

## هدف

ساخت یک صفحه ترازنامه مالی که هم از نظر بصری جذاب باشد و هم از نظر دسترسی‌پذیری (Accessibility) کاملاً استاندارد باشد، به‌طوری که کاربران دارای صفحه‌خوان نیز بتوانند به‌راحتی از آن استفاده کنند.

---

## وظیفه (Task)

یک صفحه ترازنامه ایجاد کنید که شامل موارد زیر باشد.

یک هدر شامل نام شرکت و عنوان «Balance Sheet» که به‌گونه‌ای ساختاردهی شده باشد که صفحه‌خوان‌ها آن‌ها را به ترتیب منطقی اعلام کنند.

نمایش سال‌ها در بالای صفحه که:
برای صفحه‌خوان‌ها مخفی باشند با aria-hidden="true"  
در هنگام اسکرول به‌صورت sticky در بالای صفحه باقی بمانند  

سه جدول جداگانه برای:
Assets  
Liabilities  
Net Worth  

ساختار ردیف‌ها و سلول‌ها بهینه‌شده برای دسترسی‌پذیری:
استفاده از th برای سلول‌های عنوان  
استفاده از td برای داده‌ها  
ردیف‌های جمع کل با tr و کلاس total  
اعداد در ردیف‌های جمع کل به‌صورت راست‌چین  

متن مخصوص صفحه‌خوان (کلاس sr-only) برای:
سال‌ها  
برچسب‌های دسته‌بندی که نباید به‌صورت بصری نمایش داده شوند  

چیدمان ریسپانسیو جدول با:
حداقل عرض (min-width)  
حداکثر عرض (max-width)  
برای سلول‌ها  

استایل‌دهی با CSS برای:
خوانایی بهتر  
رنگ‌بندی متناوب ردیف‌ها  
افکت hover  
فاصله‌گذاری مناسب  

---

## الزامات (Requirements)

ایجاد فایل‌های index.html و styles.css  

استفاده از HTML معنایی:
main  
section  
table  
caption  
thead  
tbody  
th  
td  

در نظر گرفتن دسترسی‌پذیری:
استفاده از کلاس sr-only  
استفاده از aria-hidden  

استایل‌دهی جدول‌ها به‌گونه‌ای که:
ستون‌های عددی راست‌چین باشند  
ردیف‌های جمع کل از نظر بصری متمایز باشند و در hover برجسته شوند  
مقادیر مربوط به سال جاری به‌صورت italic نمایش داده شوند  

نمایش ترتیب بصری معکوس عنوان‌ها با CSS، بدون تغییر ترتیب منطقی برای صفحه‌خوان‌ها  

نوار سال‌ها به‌صورت sticky در بالای جدول‌ها باقی بماند  

---

## چک‌لیست موفقیت (Success Checklist)

هدر شامل نام شرکت و عنوان «Balance Sheet» است که:
به‌صورت بصری معکوس نمایش داده می‌شود  
ولی صفحه‌خوان‌ها آن را به ترتیب صحیح می‌خوانند  

نوار سال‌ها:
sticky است  
در سمت راست تراز شده  
برای صفحه‌خوان‌ها مخفی است  

تمام جدول‌ها دارای caption هستند  
ساختار thead و tbody به‌درستی رعایت شده است  

استفاده صحیح از th و td انجام شده  
ردیف‌های total راست‌چین بوده و در hover برجسته می‌شوند  

متن sr-only برای سال‌ها و برچسب‌های پنهان استفاده شده است  

سلول‌های جدول دارای min-width و max-width برای چیدمان یکنواخت هستند  

پس‌زمینه متناوب ردیف‌ها و padding مناسب باعث افزایش خوانایی شده است  

و CSS باعث می‌شود جدول‌ها در اندازه‌های مختلف صفحه، ریسپانسیو و مرتب باقی بمانند  

</div>
