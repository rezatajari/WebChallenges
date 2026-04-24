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
