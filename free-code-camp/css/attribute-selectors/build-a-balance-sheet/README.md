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
