---
marp: true
title: Product Documentation with Marp
author: Anand S
theme: default
paginate: true
# Use a custom theme below with <style>
---

<style>
/* Custom Marp theme and slide styling */
section {
  background-color: #fafdff;
  color: #263238;
  font-family: 'Segoe UI', Arial, sans-serif;
}
h1, h2, h3 {
  color: #2274A5;
}
a {
  color: #35a839;
  text-decoration: underline;
}
table th {
  background: #dfefff;
  color: #3c5674;
}
footer {
  font-size: 0.7em;
  color: #807e7e;
}
img[alt~="icon"] {
  border-radius: 16px;
  border: 1px solid #d5d5d5;
  box-shadow: 1px 2px 12px #e0eaff90;
}
</style>

<!-- _header: Product Documentation -->

# Product Documentation with Marp

Welcome!  
This presentation demonstrates Marp features for technical documentation:

- Version control friendly
- Custom themes and styles
- Code, math, and diagrams
- Conversion to HTML/PDF/PPTX

---

## Maintainer Contact

For queries:  
**Anand S**  
📧 **23f3000137@ds.study.iitm.ac.in**  

---

<!-- _class: lead -->
# Why Marp for Docs?

- Write once in **Markdown**
- Preview and export in **multiple formats**
- Track changes with **Git version control**
- Add diagrams, code, and math
- Easy custom theming

---

<!-- _backgroundImage: url('images/background.jpg') -->
<!-- _backgroundSize: cover -->
<!-- _color: white -->
<!-- _footer: Sample background slide -->

# Slide With Background

This slide features a background image.

- Set backgrounds per-slide
- Overlay content legibly with color styles

---

## Algorithm Example

**Consider time complexity:**

```python
def sum_n(n):
    s = 0
    for i in range(n):
        s += i
    return s
