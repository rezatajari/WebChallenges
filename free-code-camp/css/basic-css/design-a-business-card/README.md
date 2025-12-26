# Design a Business Card

## Goal
Practice fundamental **HTML structure**, **CSS styling**, and **layout discipline** by building a clean, reusable business card component.  
This challenge focuses on **attention to detail**, **semantic correctness**, and **basic visual design**, which are essential skills for real-world frontend work.

---

## Challenge Overview
In this mini project, you will build a **personal business card UI component** using only **HTML and CSS**.

You are encouraged to:
- Follow the required structure precisely
- Add your own personal visual style
- Treat this as a small, production-ready component

Avoid copying existing examples line by line. Use them only as inspiration.

---

## Task
Build a business card that includes:

- A main card container
- Profile image
- Personal information (name, role, company)
- Contact details
- Portfolio link
- Social media links
- Clean layout and consistent spacing

---

## User Stories (Requirements)

### Structure
- You should have a `div` with a class of `business-card` that contains **all other elements**
- Inside `.business-card`, include:
  - An `img` element with class `profile-image`
    - Use a meaningful `alt` description
    - You may use:  
      `https://cdn.freecodecamp.org/curriculum/labs/flower.jpg`
  - Three `p` elements **after the image**, with classes:
    - `full-name`
    - `designation`
    - `company`
  - The first `p` contains your **name**
  - The second `p` contains your **designation**
  - The third `p` contains your **company name**

---

### Content Flow
- Add an `hr` element **below the company name**
- After the `hr`, include:
  - One `p` element with an **email address**
  - One `p` element with a **phone number**
- Add an `a` element:
  - Class: `portfolio-link`
  - Text: `Portfolio`
  - Link to a valid URL
- Add another `hr` **after** the portfolio link

---

### Social Media Section
- Add a `div` with class `social-media`
- Inside it:
  - An `h2` with text: **Connect with me**
  - Three `a` elements linking to:
    - Twitter
    - LinkedIn
    - GitHub

---

## Styling Requirements

### Global Styles
- Page background color: `rosybrown`
- Font family: `Arial`, fallback to `sans-serif`
- All links should **not be underlined**

---

### Business Card Styles
The `.business-card` selector must:
- Have a width of `300px`
- Use a background color of your choice
- Have `20px` padding on all sides
- Have a top margin of `100px`
- Be horizontally centered using `margin-left: auto` and `margin-right: auto`
- Use center-aligned text
- Use a base font size of `16px`

---

### Image & Text
- `.profile-image` must have:
  - `max-width: 100%`
- All `p` elements must have:
  - `5px` margin on top and bottom

---

## File Requirements
- Create:
  - `index.html`
  - `styles.css`
- Link `styles.css` using a `<link>` tag inside the `<head>` of your HTML file

---

## Success Checklist
Use this checklist to validate your solution:

- Business card layout is centered and visually balanced
- Required HTML structure and class names are correct
- Image scales properly inside the card
- Text spacing is consistent and readable
- Links are styled correctly (no underline)
- Code is clean, readable, and easy to understand

---

## Stretch Ideas (Optional)
If you want to go further:
- Add hover effects to links
- Improve typography hierarchy
- Add subtle borders or shadows
- Make the card reusable as a component

---

## Why This Challenge Matters
This task simulates real-world frontend work where:
- Requirements are strict
- Structure matters as much as appearance
- Small UI components must be clear, reusable, and maintainable

Mastering these basics will make larger projects much easier.
