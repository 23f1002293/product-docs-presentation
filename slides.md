---
marp: true
title: "Product Documentation Presentation"
paginate: true
theme: product-docs
class: lead
header: "Technical Docs — 2025"
footer: "© 2025 — Janani | 23f1002293@ds.study.iitm.ac.in"
---

<!-- Custom Theme Definition -->
<style>
section {
  font-family: "Inter", Arial, sans-serif;
  letter-spacing: 0.2px;
}

/* Custom heading color */
h1, h2, h3 {
  color: #0057ff;
}

/* Footer styling */
footer {
  color: #444;
  font-size: 0.7rem;
}

/* Page number styling */
section::after {
  font-size: 0.65rem;
  color: #555;
}

/* Code block styling */
code {
  background: #f4f4f4;
  padding: 4px 8px;
  border-radius: 6px;
}
</style>

<!-- Theme registration -->
<style>
/* Marp Theme: product-docs */
:root {
  --color-background: #ffffff;
  --color-foreground: #222;
  --color-highlight: #0057ff;
}
</style>

# Product Documentation  
### Technical Presentation  
**Janani — 23f1002293@ds.study.iitm.ac.in**

---

# Agenda

- Product Overview  
- Architecture Summary  
- Key Features  
- API Documentation  
- Performance & Complexity  
- Deployment Notes  

---

# Product Overview

Our software provides enterprise-grade automation tools for workflow orchestration, event streaming, and analytics.

**Built for:**

- Scalability  
- Maintainability  
- Developer productivity  
- Observability  

---

<!-- Background Image Slide -->
<!-- Replace with your GitHub raw URL if needed -->
![bg](https://images.unsplash.com/photo-1535223289827-42f1e9919769?w=1400)

# System Architecture Overview

A simplified architecture of the product showing clients, API gateway, event processors, and analytics engine.

---

# Example Code Snippet

```python
from product_sdk import Client

client = Client(api_key="secret-key")

response = client.get_metrics()
print(response)
