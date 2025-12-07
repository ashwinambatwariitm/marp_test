---
marp: true
title: Product Documentation Presentation
author: 24f2009283@ds.study.iitm.ac.in
paginate: true
math: katex       # <-- IMPORTANT: Enables LaTeX equations
---

<style>
/* ---- Custom Theme ---- */

section {
  font-family: "Segoe UI", sans-serif;
  letter-spacing: 0.2px;
}

section.lead h1 {
  font-size: 2.8rem;
  color: #0a84ff;
}

pre code {
  font-size: 1rem;
  padding: 10px;
  border-radius: 8px;
}
</style>

<!-- _class: lead -->

# 📘 Product Documentation  
### Powered by Marp  
#### 24f2009283@ds.study.iitm.ac.in

---

# 📑 Introduction

This presentation demonstrates:

- Custom themes  
- Background images  
- KaTeX mathematical equations  
- Marp directives  
- Version-controlled slides  

---

<!-- _backgroundColor: '#001f33' -->
<!-- _color: white -->

# 🔧 Why Use Marp?

- Write documentation in **Markdown**  
- Export to **HTML, PDF, PPTX**  
- Fully compatible with **Git** workflows  

---

<!-- Background image slide -->

![bg cover](https://images.unsplash.com/photo-1518779578993-ec3579fee39f)

# 🌐 System Architecture Diagram

Background images enhance visual presentations.

---

# 🎨 Styling with Directives

<!-- _backgroundColor: '#f4f4f4' -->
<!-- _color: '#222' -->
<!-- _class: highlight -->

Custom styles using:

- `_backgroundColor`
- `_color`
- `_class`
- inline `<style>` theme

---

# 🧮 Algorithmic Complexity (LaTeX Math)

Inline math example:  
Sorting complexity = $O(n \log n)$

Block math:

$$
T(n) = 2T\left(\frac{n}{2}\right) + n
$$

Using Master Theorem:

$$
T(n) = O(n \log n)
$$

---

# 🧩 Example Code Snippet

```python
def compute_score(data):
    total = sum(data)
    return total / len(data)

print(compute_score([10, 20, 30]))
