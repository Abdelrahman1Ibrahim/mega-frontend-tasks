# JavaScript Basics Challenge – Smart Receipt Generator

**Prepared by:** Abdelrahman Maarouf
**Level:** Mid-Level
**Course:** Learn JavaScript in Arabic 2021 – Lessons #001 to #018

---

## Description

This challenge tests your **full understanding** of **"Learn JavaScript in Arabic 2021"** lessons **#001 to #018**.

You will build a **Smart Receipt Generator** for a cafe. The program calculates an order, applies a discount, tax, and service charge, splits the bill between friends, and prints a formatted receipt using clean JavaScript code.

---

## Concepts Covered

- Setup and Tools (#001–#004)
- Code placement: inline, internal, external (#005)
- Comments and bad practices (#006)
- Output: `alert`, `console.log`, `document.write` (#007)
- Console methods and `%c` styling (#008)
- ECMAScript and `typeof` (#009–#010)
- Variables, naming rules, `var / let / const` (#011–#013)
- Strings and escape sequences (#014)
- Concatenation and Template Literals (#015–#017)
- Arithmetic operators: `+ - * / % **` (#018)

---

## Project Structure

```
/JavaScript-Receipt-Challenge
│
├─ index.html
├─ js/
│   └─ main.js
└─ README.md
```

---

## Starter Files

### `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smart Receipt Generator</title>
</head>
<body>
  <h1>Smart Receipt Generator</h1>

  <!-- TODO: Add an inline script that shows an alert -->
  <!-- TODO: Add an internal script that uses document.write -->
  <!-- TODO: Add the external script (js/main.js) -->
</body>
</html>
```

### `js/main.js`

```js
// Start of program - DO NOT DELETE
/*
  This project covers lessons #001 to #018
  of "Learn JavaScript in Arabic 2021"
*/

// ===== Part 1: Console Styling =====
// TODO #1: Print the cafe name using console.log with %c (at least 2 styles)
// TODO #2: Use console.warn and console.error with a custom message each
// TODO #3: Use console.table to show the project info (name, level, lessons)

// ===== Part 2: Variables =====
// TODO #4: Declare constants: cafeName, taxRate, serviceRate, discountRate
// TODO #5: Declare variables: customerName, tableNumber, numberOfFriends
// TODO #6: Declare item prices and quantities (at least 4 items)
//          Example: coffeePrice, coffeeQty, ...
// TODO #7: Add a comment explaining why you did not use var
// TODO #8: Add commented examples of 3 invalid variable names and why they are invalid

// ===== Part 3: Data Types =====
// TODO #9: Use typeof to log the type of every variable you declared
// TODO #10: Log the result of typeof for: "10" and 10, and explain the difference in a comment

// ===== Part 4: Calculations =====
// TODO #11: Calculate each item total (price * quantity)
// TODO #12: Calculate subtotal
// TODO #13: Calculate discount amount and subtotal after discount
// TODO #14: Calculate tax amount and service amount (both on the discounted subtotal)
// TODO #15: Calculate the final total
// TODO #16: Split the total between friends using /
// TODO #17: Use % to find the remainder when the total (in whole units) is split between friends
// TODO #18: Use ** to calculate the total after 2 years of a 5% yearly price increase
//           (use the final total as the base)

// ===== Part 5: Strings =====
// TODO #19: Build a receipt header using a string with \n and \t
// TODO #20: Use escape sequences to print a string that contains both ' and "
// TODO #21: Use an escaped backslash \\ in a string (for example, a file path)

// ===== Part 6: Building the Receipt =====
// TODO #22: Build the full receipt using + (concatenation)
// TODO #23: Build the same receipt using template literals
// TODO #24: Print both receipts with console.log and compare them
// TODO #25: Print the final receipt on the page using document.write
// TODO #26: Show the final total and the per-friend amount using alert
```

---

## Task Instructions

### 1. Setup (#001–#004)
- Create the folder and files
- Open the project in **VS Code**
- Run it with **Live Server**
- Open **Chrome DevTools** (`F12`)

### 2. Complete `index.html`
- Add an **inline script** that shows an `alert`
- Add an **internal script** that uses `document.write`
- Add the **external script** `main.js`

### 3. Complete `main.js`
Finish all 26 TODOs in order. Every part of the receipt must be calculated from variables, with no hard-coded final results.

### 4. Testing
- Change the quantities and rates, then confirm every value updates correctly
- Change `numberOfFriends` and confirm the split and the remainder are correct
- Confirm there are no red errors in the DevTools Console

### 5. README.md
Add the following:
- Your name
- 2–3 sentences: **"What is the difference between concatenation and template literals?"**
- A screenshot of the **Console tab** showing the styled output
- A screenshot of the final receipt on the page

---

## Evaluation (100 Points)

| Points | Criteria |
|:---:|---|
| 10 | Setup, Live Server, and DevTools screenshot |
| 10 | Code placement: inline, internal, external |
| 10 | Clean comments and no bad practices |
| 15 | Console methods and `%c` styling |
| 15 | Variables: `let / const`, naming rules, no `var` |
| 10 | `typeof` usage and explanation |
| 15 | Strings, escape sequences, concatenation, template literals |
| 15 | Correct calculations using `+ - * / % **` |
| +Bonus | Clean receipt formatting, extra items, extra calculations |



## Author
- Abdelrahman Maarouf
