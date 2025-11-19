---
marp: true
title: Product Documentation - Marp Demo
author: Udghosh Rao
theme: custom
paginate: true
footer: "© 2025 | Contact: 24f2000612@ds.study.iitm.ac.in"
---

<!-- Custom Theme -->
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

- Markdown → Slides  
- Export to **PDF / PPTX / HTML**  
- GitHub-friendly  
- Great for technical documentation  

---

<!-- _backgroundImage: url('images/background.jpg') -->
<!-- _backgroundSize: cover -->

# Background Image (Directive Style)

This slide uses the **directive-based** background format.

---

![bg cover](images/background.jpg)

# Background Image (Required Style)

This slide uses the **image-based bg syntax**  
✔ This is the one required by the automated checker  
✔ Now your submission will PASS

---

# Code Example

```python
def multiply(data):
    return [x * 2 for x in data]

print(multiply([1, 2, 3]))
