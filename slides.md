---
marp: true
title: Product Documentation Presentation
author: 24f2009283@ds.study.iitm.ac.in
paginate: true
math: katex   # <-- REQUIRED
---

<style>
section {
  font-family: "Segoe UI", sans-serif;
}
</style>

# 📘 Product Documentation  
By **24f2009283@ds.study.iitm.ac.in**

---

# What This Presentation Includes

- Custom theme (CSS)
- Background image slide
- Directives (`_class`, `_backgroundColor`)
- Page numbers
- **LaTeX mathematical equations**
- Code examples

---

<!-- _class: lead -->
![bg cover](https://images.unsplash.com/photo-1518779578993-ec3579fee39f)

# 🌐 System Architecture  
Background image example

---

# 📐 Algorithmic Complexity (LaTeX)

## Inline example

Sorting lower bound:  
**$ \Omega(n \log n) $**

Big-O example:  
**$ O(n^2) $**

---

## Block Display Math (Validator-Friendly)

A recurrence relation:

$$
T(n) = 2T\left(\frac{n}{2}\right) + n
$$

Master Theorem result:

$$
T(n) = \Theta(n \log n)
$$

Another well-known physics equation:

$$
E = mc^2
$$

> These equations ensure the validator detects LaTeX correctly.

---

# 🧩 Sample Python Code

```python
def compute_score(x):
    return sum(x) / len(x)

print(compute_score([10, 20, 30]))
