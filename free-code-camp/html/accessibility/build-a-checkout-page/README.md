
# Build a Checkout Page

## Goal

Build a functional checkout page that satisfies a strict set of structural, semantic, and accessibility-related user stories. The project must pass all automated tests defined in the challenge.

---

## User Stories to Satisfy

### Page Structure

1. The page must contain exactly one top-level heading containing the text "Checkout".
2. Immediately after that heading, there must be **two section elements**.

### First Section: Cart Summary

3. The first section must contain a second-level heading with the text "Your Cart".
4. The first section must contain at least one image with descriptive alternate text.

### Second Section: Payment Form

5. The second section must contain a second-level heading with the text "Payment Information".
6. A form element must appear inside this second section.

### Required Form Fields

Inside the form, the following must exist:

7. An input for the cardholder name

   * Must have **id="card-name"** and **name="card-name"**
   * Must be of type **text**
   * Must have a label correctly associated with it

8. An input for the card number

   * Must have **id="card-number"** and **name="card-number"**
   * Must be of type **text**
   * Must have a label correctly associated with it

9. At least **two input elements must include the required attribute**.

10. Each required input's label must contain:

    * A visually-displayed star symbol
    * That star must be wrapped inside a span
    * The span must have **aria-hidden="true"**

### Card Number Help Text

11. A help paragraph with:

    * **id="card-number-help"**
    * Non-empty text explaining the required card-number format
    * Must appear *immediately after* the card number input
    * The card-number input must reference it using **aria-describedby**

---

## Common Mistakes to Avoid

* Forgetting the **form** element entirely.
* Not matching the required **id** and **name** attributes exactly.
* Using `type="number"` for card numbers (tests expect **text**).
* Putting the star (*) outside the label instead of inside it.
* Forgeting `aria-hidden="true"` on star spans.
* Adding help text in the wrong position (it must be directly after the card number input).
* Using labels that reference the wrong `for` IDs.
* Omitting required attributes on at least two inputs.

---

## Summary of What You Need to Fix in Your Version

Your current implementation must be adjusted to meet these requirements:

* The payment inputs must be inside a **form**.
* The cardholder name input must use `card-name` as both id and name.
* The card number input must use `card-number` as both id and name and use `type="text"`.
* All required inputs must include a star inside a span with `aria-hidden="true"`.
* The `<p>` describing card number format must have the id `card-number-help`.
* The card-number input needs `aria-describedby="card-number-help"`.

Once these corrections are applied, the tests will pass.
