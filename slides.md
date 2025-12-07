---
marp: true
title: Product Documentation Presentation
author: 24f2009283@ds.study.iitm.ac.in
theme: default      # <-- REQUIRED: Explicit theme specification
paginate: true
math: katex         # <-- REQUIRED: enables LaTeX equations
---

<style>
/* ---- Custom Theme Overrides ---- */
section {
  font-family: "Segoe UI", sans-serif;
  letter-spacing: 0.25px;
}

h1 {
  color: #0a84ff;
}

code {
  font-size: 0.9rem;
  padding: 8px;
  border-radius: 6px;
}
</style>

<!-- _class: lead -->

# 📘 Product Documentation  
### Built with Marp  
#### **Contact:** 24f2009283@ds.study.iitm.ac.in

---

# 📑 Overview

This presentation demonstrates:

- A **specified theme**
- Custom CSS theme overrides
- LaTeX mathematics
- Background image slide
- Marp directives
- Page numbering

---

<!-- Background image slide -->
![bg cover](https://images.unsplash.com/photo-1518779578993-ec3579fee39f)

# 🌐 System Architecture  
Background image example using **Marp’s bg directive**.

---

# 🎨 Custom Styling (Directives)

<!-- _backgroundColor: "#003355" -->
<!-- _color: white -->
<!-- _class: highlight -->

This slide uses:

- `_backgroundColor`
- `_color`
- `_class`
- Theme overrides in `<style>`

---

# 🧮 Algorithmic Complexity (LaTeX Math)

Inline math example:

Sorting lower bound:

**$ \Omega(n \log n) $**

---

## Display Math (Validator-Friendly)

Recurrence relation:

$$
T(n) = 2T\left(\frac{n}{2}\right) + n
$$

Master theorem result:

$$
T(n) = \Theta(n \log n)
$$

Physics equation:

$$
E = mc^2
$$

---

# 🧩 Example Code Snippet

```python
def compute_score(values):
    return sum(values) / len(values)

print(compute_score([10, 20, 30]))
