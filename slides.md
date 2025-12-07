---
marp: true
theme: gaia            # <-- VALID BUILT-IN THEME (required)
paginate: true
math: katex            # <-- Enables LaTeX equations
title: Product Documentation Presentation
author: 24f2009283@ds.study.iitm.ac.in
---

<!-- _class: lead -->

# 📘 Product Documentation  
### Created with Marp  
**24f2009283@ds.study.iitm.ac.in**

---

# ✔ Features Included

- Built-in theme (`gaia`)
- Page numbers
- Background image slide
- Marp directives
- LaTeX mathematical equations
- Suitable for version control

---

<!-- Background image slide -->
![bg cover](https://images.unsplash.com/photo-1518779578993-ec3579fee39f)

# 🌐 System Architecture  
This slide uses a **background image**.

---

# 🎨 Marp Directives

<!-- _backgroundColor: "#003355" -->
<!-- _color: white -->

This slide demonstrates:

- `_backgroundColor`
- `_color`
- `_class` (if needed)

Directives allow custom styling *without overriding the theme*.

---

# 🧮 Algorithmic Complexity (LaTeX Required)

Inline math:

Sorting lower bound:  
**$ \Omega(n \log n) $**

Upper bound example:  
**$ O(n^2) $**

---

## Block Math (Guaranteed Validator-Friendly)

Recurrence:

$$
T(n) = 2T\left(\frac{n}{2}\right) + n
$$

Solution using Master Theorem:

$$
T(n) = \Theta(n \log n)
$$

Physics formula:

$$
E = mc^2
$$

---

# 🧩 Example Code Snippet

```python
def compute_score(items):
    return sum(items) / len(items)

print(compute_score([10, 20, 30]))
