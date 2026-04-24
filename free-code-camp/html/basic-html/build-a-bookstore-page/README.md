# Build a Bookstore Page

## Objective
Create a simple **bookstore webpage** showcasing a collection of books using **card-style layout**. The page allows users to browse books, view details, and proceed to purchase through interactive buttons.

---

## Features

### Header Section
- Main heading (`<h1>`) displaying **“XYZ Bookstore”**.  
- A short introductory paragraph encouraging users to browse the collection:  
  *“Browse our collection of amazing books!”*

---

### Book Cards
- Books are presented as **cards** using `<div class="card">` elements inside a **container** (`<div class="card-container">`).  
- Each card includes:
  - **Title** (`<h2>`)
  - **Description** (`<p>`) summarizing the story or content  
  - **Buy Now button** (`<button class="btn">`) for purchasing

Example cards:
1. **Sally's SciFi Adventure**  
   - Story of Sally and her dog Rex exploring other worlds.
   - Button: Buy Now
2. **Dave's Cooking Adventure**  
   - Story of Dave learning to cook a variety of recipes.
   - Button: Buy Now

---

### Footer Section
- Paragraph reminding users to review selections before proceeding to checkout.  
- Button container (`<div class="btn-container">`) with two action buttons:
  - **View Cart** (`<button id="view-cart-btn" class="btn">`)  
  - **Checkout** (`<button id="checkout-btn" class="btn">`)

---

## How to Use
1. Open the HTML file in a web browser.  
2. Browse the book collection in the **card layout**.  
3. Click **Buy Now** on individual cards to add books to the cart.  
4. Use **View Cart** to review selected items.  
5. Click **Checkout** to proceed with purchase.

---

## Technologies
- **HTML5**
- Structural elements:
  - `<h1>`, `<h2>`, `<p>`, `<div>`, `<button>`
- **CSS classes** (assumed external or internal styles):
  - `.card-container`, `.card`, `.btn`, `.btn-container`

---

## Notes
- Each book is organized as a **semantic card** for clarity and visual separation.  
- Buttons are interactive elements for user actions.  
- The layout is **extensible**, allowing additional cards or features like filtering or sorting.

---

## Challenge Tasks
- Add images to each book card.  
- Implement a **shopping cart counter** that updates when users click “Buy Now”.  
- Apply CSS styling for hover effects on cards and buttons.  
- Add a **search or filter feature** to find books by genre or author.
