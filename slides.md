---
marp: true
paginate: true
headingDivider: 2
theme: custom-theme
---

<!--
CUSTOM THEME (inside the same file)
You may also move this to custom.css later.
-->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}

/* Header text */
h1, h2, h3 {
  color: #003366;
}

/* Footer page numbers */
section::after {
  content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 10px;
  right: 20px;
  font-size: 0.7rem;
  color: #444;
}

/* Custom colors */
:root {
  --main-color: #003366;
  --accent-color: #ffbf00;
}
</style>

# Product Documentation  
Prepared by: **24f2004315@ds.study.iitm.ac.in**

---

## Introduction

Welcome to the **Product Documentation Presentation**.

This document is:

- Maintainable in version control  
- Exportable to HTML/PDF/PPTX using **Marp**  
- Styled with a *custom theme*  
- Includes page numbers and math rendering  

---

## Background Image Example

![bg opacity=0.25](https://images.unsplash.com/photo-1518770660439-4636190af475?w=1600)

# System Architecture

This slide demonstrates a **background image** using Marp directives.

---

## Algorithmic Complexity

Example mathematical formulas:

### Binary Search Time Complexity

\[
T(n) = T(n/2) + O(1)
\]

Thus:

\[
T(n) = O(\log n)
\]

---

## Custom Styling Example

This slide uses:

- Custom fonts  
- Custom theme  
- Built-in pagination  
- Custom colors via CSS variables  

Styling is defined directly in the markdown file.

---

# Thank You  
For questions, contact:  
**24f2004315@ds.study.iitm.ac.in**
