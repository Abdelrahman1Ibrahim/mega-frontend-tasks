# HTML Task – "Al-Sham Restaurant" Menu Page

**Prepared by:** Abdelrahman Maarouf
**Level:** Beginner
**Course:** Learn HTML in Arabic 2021 – Lessons #01 to #18
**Tools:** HTML only (no CSS, no JavaScript)

---

## Brief

The owner of **Al-Sham Restaurant** needs a simple web page that presents his menu, introduces the restaurant, and explains how to order. No styling is required. The content must be well structured and complete.

Build the page using only what you learned in lessons #01 to #18.

---

## Lessons Covered

| Skill | Lessons |
|---|---|
| HTML basics, elements, tags | #01 – #03 |
| Page structure (`DOCTYPE`, `html`, `head`, `body`) | #04 – #06 |
| Headings, paragraphs, text formatting | #07 – #09 |
| Attributes | #10 – #11 |
| Links and images | #12 – #13 |
| Lists and tables | #14 – #15 |
| `span`, `br`, `hr`, `div`, entities | #16 – #18 |

---

## Requirements

### Stage 1 – Setup
- [ ] File named `index.html`
- [ ] `<!DOCTYPE html>` at the top
- [ ] `<html lang="en">`
- [ ] Inside `<head>`: `<meta charset="UTF-8">` and a `<title>`
- [ ] At least one HTML comment

### Stage 2 – Header and Introduction
- [ ] Exactly one `<h1>` with the restaurant name
- [ ] A logo using `<img>` with a proper `alt`
- [ ] An introduction paragraph `<p>`
- [ ] Use `<strong>`, `<em>`, and `<mark>` inside the text
- [ ] Use `<br>` at least once

### Stage 3 – Menu
- [ ] An `<h2>` for each section: **Grills, Appetizers, Drinks**
- [ ] A **table** for Grills with `<caption>`, `<thead>`, and `<tbody>`
  - Columns: Item | Description | Price
  - At least 4 items
- [ ] An **unordered list** `<ul>` for Appetizers (at least 3 items)
- [ ] A **description list** `<dl>` for Drinks (name + description)
- [ ] At least one entity in the prices (e.g. `&nbsp;`)

### Stage 4 – Ordering and Contact
- [ ] An `<h2>` titled **"How to Order"**
- [ ] An **ordered list** `<ol>` with 3 steps
- [ ] An external link that opens in a new tab (`target="_blank"`)
- [ ] An internal link that jumps to the menu section (using `id` and `#`)
- [ ] A link with the `download` attribute (for example, to the logo image)

### Stage 5 – Layout and Footer
- [ ] Group each section with a `<div>` that has an `id` or `class`
- [ ] Use `<hr>` between sections
- [ ] Use `<span>` to mark a word inside a sentence
- [ ] A footer with `&copy;`, the year, and your name
- [ ] Use the `&rarr;` entity at least once
- [ ] Use the `title` attribute on at least two elements

---

## Project Structure

```
restaurant-menu/
│
├── index.html
└── images/
    ├── logo.png
    └── grill.jpg
```

---

## Scoring (100 points)

| Criteria | Points |
|---|:---:|
| Correct page structure (DOCTYPE, head, body, lang) | 15 |
| Headings, paragraphs, and text formatting | 15 |
| Table with all required elements | 20 |
| The three lists (ul, ol, dl) | 15 |
| Links and images (correct paths, alt text) | 15 |
| `div`, `span`, `hr`, `br`, entities | 10 |
| Clean code (indentation, comments) | 10 |
| **Total** | **100** |

---

## Bonus (Optional)

- [ ] Add a second table for **opening hours** using `colspan` or `rowspan`
- [ ] Add a **table of contents** at the top with internal links
- [ ] Validate the page with the **W3C Validator** with zero errors



© 2026 – Abdelrahman Maarouf
