---
marp: true
title: Product Documentation - Marp Demo
author: Udghosh Rao
theme: custom
paginate: true
footer: "© 2025 | Contact: 24f2000612@ds.study.iitm.ac.in"
---

<!-- Custom Theme (inside same file, easy for GitHub) -->
<style>
section {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f4f7fb;
  color: #222;
}

h1, h2, h3 {
  color: #004aad;
}

blockquote {
  border-left: 5px solid #004aad;
  padding-left: 12px;
  font-style: italic;
  color: #444;
}

/* footer style */
footer {
  color: #004aad;
}
</style>

# Product Documentation  
### Created with Marp

**Author:** Udghosh Rao  
**Email:** 24f2000612@ds.study.iitm.ac.in  

---

# Why Marp?

- Write in Markdown  
- Convert to **PDF / PPTX / HTML**  
- Works with GitHub  
- Simple for technical documentation  

---

<!-- _backgroundImage: url('images/background.jpg') -->
<!-- _backgroundSize: cover -->
# Background Image Slide

This slide uses a full background image.  
(Place `background.jpg` inside an `images/` folder.)

---

# Code Example

```python
def multiply(data):
    return [x * 2 for x in data]

print(multiply([1, 2, 3]))
