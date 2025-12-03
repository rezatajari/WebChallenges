# Build an Accessible Audio Controller

README – ARIA Labeling & Accessible UI Challenge

## Overview

This document focuses on building accessible audio controls using semantic HTML and ARIA attributes.
The challenge is to understand how interface elements like buttons and sliders become usable for all users, including those who rely on assistive technologies.

---

## What This HTML Document Demonstrates

### 1. Clear Section Title

The content starts with a heading that announces the purpose of the interface.
This helps screen readers and users quickly understand what the controls relate to.

### 2. Basic Interactive Elements

Two interactive buttons are presented:

* Play
* Mute

Each uses a semantic button element, which is automatically keyboard-accessible.

### 3. Grouped Volume Controls

A volume slider is presented inside a container with two descriptive labels:

* One identifies what the control is
* One explains what it does

This shows how visual and non-visual users rely on text-based descriptions.

### 4. Use of ARIA Attributes

The slider uses an attribute that associates multiple descriptive elements with a single control.
This ensures that assistive technologies read out both the label and the purpose.

---

## Learning Goals

### Accessible Control Design

Understand how:

* Semantic buttons improve usability
* Labels and descriptions support screen reader users
* ARIA attributes connect meaningful text to controls
* Range inputs become accessible with proper referencing

### Real-World Application

These techniques apply directly to:

* Media players
* Sliders and knobs
* Control panels
* Any custom UI element requiring accessibility support

---

## Task for the Learner

Analyze this UI and explain:

1. Why the slider needs both a label and a description
2. How ARIA labelling improves accessibility
3. What would happen if the slider were missing its descriptive text

---

<div dir="rtl">

# ساخت یک کنترل‌کنندهٔ صوتی دسترس‌پذیر

## نمای کلی  
این سند بر ساخت کنترل‌های صوتی دسترس‌پذیر با استفاده از HTML معنایی و صفت‌های ARIA تمرکز دارد.  
هدف چالش، درک این موضوع است که چگونه دکمه‌ها و اسلایدرها برای همهٔ کاربران — از جمله کاربران ابزارهای کمکی — قابل استفاده می‌شوند.

---

## این سند HTML چه چیزهایی را نشان می‌دهد؟

### ۱. عنوان مشخص برای بخش  
محتوا با یک عنوان شروع می‌شود که هدف رابط را توضیح می‌دهد.  
این کار باعث می‌شود کاربران و صفحه‌خوان‌ها سریعاً بفهمند کنترل‌ها مربوط به چه چیزی هستند.

### ۲. عناصر تعاملی پایه  
دو دکمهٔ تعاملی ارائه شده است:

• پخش  
• بی‌صدا  

هرکدام از عنصر معنایی «دکمه» استفاده می‌کنند که به‌صورت پیش‌فرض برای صفحه‌کلید قابل‌دسترسی است.

### ۳. کنترل‌های گروه‌بندی‌شدهٔ صدا  
یک اسلایدر حجم صدا داخل یک بخش مخصوص نمایش داده شده است که شامل دو برچسب توضیحی است:

• یکی مشخص می‌کند این کنترل چیست  
• دیگری توضیح می‌دهد چه کاری انجام می‌دهد  

این بخش نشان می‌دهد کاربران دیداری و غیردیداری چگونه به توضیحات متنی وابسته هستند.

### ۴. استفاده از صفت‌های ARIA  
اسلایدر از یک صفت استفاده می‌کند که چند عنصر توضیحی را به یک کنترل مرتبط می‌سازد.  
این کار باعث می‌شود ابزارهای کمکی هم برچسب و هم هدف کنترل را بخوانند.

---

## اهداف یادگیری

### طراحی کنترل دسترس‌پذیر  
در این چالش می‌آموزید که:

• دکمه‌های معنایی چگونه قابلیت استفاده را افزایش می‌دهند  
• برچسب‌ها و توضیحات چگونه به کاربران صفحه‌خوان کمک می‌کنند  
• صفت‌های ARIA چگونه متن‌های معنی‌دار را به کنترل‌ها پیوند می‌دهند  
• اسلایدرها با ارجاع‌دهی صحیح چگونه دسترس‌پذیر می‌شوند  

### کاربرد در دنیای واقعی  
این تکنیک‌ها مستقیماً در موارد زیر استفاده می‌شوند:

• پخش‌کننده‌های رسانه  
• اسلایدرها و دکمه‌های چرخشی  
• پنل‌های کنترل  
• هر رابط کاربری سفارشی که نیاز به پشتیبانی دسترس‌پذیری دارد  

---

## تکلیف برای یادگیرنده

از شما خواسته می‌شود بررسی و توضیح دهید:

۱. چرا اسلایدر نیاز به یک برچسب و یک توضیح دارد؟  
۲. صفت‌های ARIA چگونه دسترس‌پذیری را بهبود می‌دهند؟  
۳. اگر اسلایدر متن توضیحی نداشت چه اتفاقی می‌افتاد؟

</div>

