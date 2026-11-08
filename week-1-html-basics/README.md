# Week 1 – HTML Basics Practice Questions

This directory contains solutions for the **Week 1 HTML Basics** module of the Web Development Internship.

## Covered Topics
- **Structure of an HTML Page** (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, semantic tags)
- **Tags, Elements, and Attributes** (`id`, `class`, `src`, `alt`, `href`, `scope`, `colspan`, `required`, `pattern`)
- **Lists, Links, Tables, Forms**
- **Multi-Page Site Navigation**

---

## Practice Questions & Solutions

### 1. Heading, Paragraph & Image (`index.html`)
- Structured hierarchical headings (`<h1>`, `<h2>`, `<h3>`, `<h4>`)
- Descriptive paragraph blocks (`<p>`)
- Responsive image element (`<img>`) with `alt`, `width`, `height`, and lazy loading
- Ordered (`<ol>`) and unordered (`<ul>`) lists

### 2. Student Records & Marks Table (`table.html`)
- Semantic table elements: `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`
- Student data containing **Student Names**, **Roll Numbers**, subject marks (Web Dev, Data Structures, AI/ML), **Total Marks**, **Percentages**, and Grade badges
- Class aggregate summary in table footer (`<tfoot>`) with `colspan`

### 3. Registration Form (`form.html`)
- Full interactive registration form with `<form>`
- Varied input types: `type="text"`, `type="email"`, `type="tel"`, `type="date"`
- `<select>` dropdown menus for Department and Year of Study
- Radio button groups for Gender selection
- Multi-select Checkboxes for technical interests
- Multiline `<textarea>` for Statement of Purpose
- `<button type="submit">` and `<button type="reset">`

### 4. Navigation Links Between 3 Web Pages
- Unified persistent `<nav>` header on all three pages:
  - `index.html` (Page 1: Overview & Media)
  - `table.html` (Page 2: Student Records Table)
  - `form.html` (Page 3: Registration Form)
- Active page indicator and bottom transition pill buttons on each page.

---

## How to Run Locally

Open any of the HTML files directly in your web browser, or launch a local server:

```bash
cd week-1-html-basics
python3 -m http.server 8080
```
Then visit `http://localhost:8080`.
