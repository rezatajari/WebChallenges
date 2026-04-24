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
