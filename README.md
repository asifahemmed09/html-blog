# BrightByte Blog — Semantic HTML Demo

## 📄 Overview

**BrightByte Blog** is a small demonstration project that showcases how to build a **fully semantic, accessible blog page using plain HTML only**.

The goal of this project is **not styling** or interactivity, but **correct document structure**, **clear content hierarchy**, and **industry-standard semantic HTML usage**.

---

## ✅ Key Features

- Pure **HTML5** (no CSS, no JavaScript)
- Correct use of **semantic elements**
- Screen-reader friendly structure
- SEO-ready metadata
- Clear separation of concerns between:
  - Site-wide content
  - Article-level content
  - Supporting content
  - User interaction (comments)

---

## 🧠 Semantic Structure Breakdown

### 1. Site Header
- Blog title and tagline
- Primary navigation
- **Secondary site-wide metadata row**
  - Latest site update (`<time>`)
  - Authors directory link

**Elements used:**
- `<header>`
- `<nav>`
- `<time>`

---

### 2. Main Content Area
The main document content lives inside `<main>`.

---

### 3. Blog Article

Represents the primary content of the page.

Includes:
- Article title
- Author information
- Publication date
- Reading time
- Tags
- Featured image with caption
- Structured sections and sub-sections
- Blockquotes and lists

**Elements used:**
- `<article>`
- `<section>`
- `<header>`
- `<figure>`
- `<figcaption>`
- `<time>`
- Headings (`<h2>`–`<h4>`)

---

### 4. Aside Content

Secondary supporting information related to the article:
- Author biography
- Related articles

**Elements used:**
- `<aside>`
- `<section>`

---

### 5. Comments Section

Represents user-generated discussion related to the article.

Includes:
- Comment list
- Individual comments as standalone content blocks

**Elements used:**
- `<section>`
- `<article>`
- `<header>`
- `<time>`

---

### 6. Comment Form

Accessible form for submitting comments.

Features:
- Proper labels
- Required fields
- Semantic form controls

**Elements used:**
- `<form>`
- `<label>`
- `<input>`
- `<textarea>`
- `<button>`

---

### 7. Footer

Contains legal information and secondary navigation.

**Elements used:**
- `<footer>`
- `<nav>`

---

## ♿ Accessibility Considerations

- Logical heading hierarchy
- ARIA labels for navigation landmarks
- Machine-readable dates using `<time datetime="">`
- Clear and persistent form labels (no placeholder-only inputs)
- Meaningful `alt` text for images

---

## 🔍 SEO Considerations

- Single `<h1>` representing site identity
- Clear article heading structure
- Semantic landmarks help search engines understand layout
- `<time datetime="">` enables structured data extraction

---

## 🚫 What This Project Does NOT Include

- CSS or visual styling
- JavaScript interactivity
- Frameworks (React, Vue, etc.)
- Build tools or bundlers

This is a **structure-first** project.

---

## 📜 License

This project is provided for educational purposes and is free to use, modify, and share.

---

## 🙌 Acknowledgements

Inspired by best practices from:
- MDN Web Docs
- W3C HTML and Accessibility Guidelines
