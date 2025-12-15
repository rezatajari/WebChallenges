# Debug a Pet Adoption Page

## Objective

Fix HTML syntax and attribute errors in Sally’s pet adoption page so that images and links work correctly.

## Description

Sally, the owner of a pet adoption store, built her first webpage but made several mistakes in her HTML code.
Your task in this challenge was to debug her code by correcting invalid attributes, removing unnecessary tags, and ensuring all elements display and link properly.

## What You Learned

* The correct attributes for HTML elements:

  * `src` for images and links to specify their source or URL
  * `alt` for images to provide descriptive alternative text
* `<img>` elements are **void elements**, meaning they do not have closing tags
* `<a>` elements use the `href` attribute, not `src`, to define links
* How to debug invalid HTML and ensure proper accessibility and functionality

## Fix Summary

1. Replaced the invalid `href` attribute in the `<img>` tag with `src`.
2. Replaced the invalid `att` attribute in the `<img>` tag with `alt`.
3. Removed the incorrect closing `</img>` tag since `<img>` is a void element.
4. Replaced `src` attributes in `<a>` tags with `href` to correctly define links.

## Expected Output

Welcome XYZ Pet Adoption!
Consider adopting a pet today. We have cats, dogs, rabbits, and more.

See our cats!
(Displays the cat image correctly)

Adopt a cat!
Visit cats page → links to `/cats`

Adopt a dog!
Visit dogs page → links to `/dogs`

---

<div dir="rtl">

# اشکال‌زدایی صفحهٔ پذیرش حیوانات خانگی

## هدف

اصلاح خطاهای نحوی و ویژگی‌ها در کد اچ‌تی‌ام‌ال صفحهٔ پذیرش حیوانات خانگی سالی، به‌طوری‌که تصاویر و پیوندها به‌درستی نمایش داده شوند و کار کنند.

---

## توضیح

سالی، صاحب یک فروشگاهٔ پذیرش حیوانات خانگی، اولین صفحهٔ وب خود را طراحی کرده است، اما در کد اچ‌تی‌ام‌ال آن چندین اشتباه وجود دارد.  
وظیفهٔ شما در این چالش این است که با **اشکال‌زدایی کد**، ویژگی‌های نامعتبر را اصلاح کنید، برچسب‌های غیرضروری را حذف کنید و اطمینان حاصل نمایید که تمام عناصر صفحه به‌درستی نمایش داده شده و پیوندها درست عمل می‌کنند.

---

## آنچه یاد می‌گیرید

### ویژگی‌های صحیح عناصر اچ‌تی‌ام‌ال

- استفاده از ویژگی **منبع** برای تصاویر و پیوندها جهت مشخص کردن نشانی فایل یا صفحه  
- استفاده از ویژگی **متن جایگزین** برای تصاویر به‌منظور توضیح محتوای تصویر  
- عناصر تصویری جزو عناصر **خودبسته** هستند و برچسب پایانی ندارند  
- عناصر پیوند برای تعریف لینک از ویژگی **نشانی مقصد** استفاده می‌کنند، نه منبع  

### مهارت‌های اشکال‌زدایی

- شناسایی ویژگی‌های نامعتبر  
- اصلاح ساختار نادرست عناصر  
- اطمینان از دسترس‌پذیری و عملکرد صحیح صفحه  

---

## خلاصهٔ اصلاحات انجام‌شده

- جایگزینی ویژگی نادرست پیوند در عنصر تصویر با ویژگی صحیح منبع  
- جایگزینی ویژگی نامعتبر در عنصر تصویر با ویژگی متن جایگزین  
- حذف برچسب پایانی اشتباه برای عنصر تصویر، زیرا این عنصر خودبسته است  
- جایگزینی ویژگی منبع در عناصر پیوند با ویژگی صحیح نشانی مقصد  

---

## خروجی مورد انتظار

به صفحهٔ پذیرش حیوانات خانگی اکس‌وای‌زد خوش آمدید!  
امروز به پذیرش یک حیوان خانگی فکر کنید. ما گربه، سگ، خرگوش و موارد دیگر داریم.

مشاهدهٔ گربه‌ها  
(تصویر گربه به‌درستی نمایش داده می‌شود)

پذیرش گربه  
بازدید از صفحهٔ گربه‌ها → پیوند به مسیر مربوطه

پذیرش سگ  
بازدید از صفحهٔ سگ‌ها → پیوند به مسیر مربوطه

</div>

