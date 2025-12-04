---
marp: true
theme: custom-iitm
paginate: true
math: katex
---

```css
/* @theme custom-iitm */

/* Base Theme */
section {
  background: #0e0e1a;
  color: #ffffff;
  font-family: "Inter", sans-serif;
  padding: 2rem;
}

/* Headings */
h1, h2, h3 {
  color: #ffd84d;
}

/* Page numbers */
section::after {
  content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  position: absolute;
  right: 20px;
  bottom: 12px;
  font-size: 0.8rem;
  opacity: 0.75;
}

/* Custom classes */
.hero {
  text-align: center;
  padding-top: 4rem;
}

.bg-box {
  background: rgba(0,0,0,0.45);
  padding: 1rem 2rem;
  border-radius: 12px;
}
```

<!-- _class: hero -->
# Marp Presentation Demo  
### With Custom Theme + Math + Background  
**Email:** 22f3001170@ds.study.iitm.ac.in

---

## What This Deck Shows

- Custom theme  
- Page numbering  
- Background image slide  
- Custom Marp styling  
- Math equations  
- Markdown formatting  
- Your email included  

---

_backgroundImage: "https://images.pexels.com/photos/1181675/pexels-photo-1181675.jpeg"
_backgroundSize: cover
_class: bg-box

# Background Image Slide

This slide uses:  
`_backgroundImage`, `_backgroundSize`, and a custom `.bg-box` style.

**Email:** 22f3001170@ds.study.iitm.ac.in

---

## Math Example — Algorithmic Complexity

Inline math:  
`O(n \log n)` → $O(n \log n)$

Block math:

$$
T(n) = 2T(n/2) + O(n)
$$

Solution:

$$
T(n) = O(n \log n)
$$

---

## End Slide

Thanks for viewing!  
**Email:** 22f3001170@ds.study.iitm.ac.in
