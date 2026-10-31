# 🌸 PERFUMY — Luxury Artisanal Fragrance E-Commerce

<p align="center">
  <img src="./images/perfume.png" alt="PERFUMY Logo" width="130" />
</p>

<p align="center">
  <strong>An elegant, mobile-first luxury e-commerce fragrance boutique showcasing artisanal perfumes, bespoke scent matching, and modern web aesthetics.</strong>
</p>

<p align="center">
  <a href="https://github.com/Harrykalsi24/Perfume-E-Comm/stargazers"><img src="https://img.shields.io/github/stars/Harrykalsi24/Perfume-E-Comm?style=for-the-badge&color=9f7aea" alt="Stars"></a>
  <a href="https://github.com/Harrykalsi24/Perfume-E-Comm/network/members"><img src="https://img.shields.io/github/forks/Harrykalsi24/Perfume-E-Comm?style=for-the-badge&color=d6bcfa" alt="Forks"></a>
  <a href="https://github.com/Harrykalsi24/Perfume-E-Comm/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-black.svg?style=for-the-badge" alt="License"></a>
  <a href="https://harrykalsi24.github.io/Perfume-E-Comm/"><img src="https://img.shields.io/badge/Live_Demo-GitHub_Pages-2ea44f?style=for-the-badge&logo=github" alt="Live Demo"></a>
</p>

---

## 🌟 Live Demo

Experience the live application here:  
👉 **[Launch PERFUMY Live](https://harrykalsi24.github.io/Perfume-E-Comm/)**

---

## 📖 Project Overview

**PERFUMY** is a luxury digital storefront and sensory showcase designed to replicate the bespoke experience of a Mayfair, London haute parfumerie. 

Built using clean, semantic **HTML5**, **Tailwind CSS**, and **Vanilla JavaScript**, the platform demonstrates high-performance web engineering, fluid typography, smooth scrolling, micro-interactions, and accessible UI components without the heavy overhead of large frameworks.

---

## ✨ Key Features

- 📱 **Mobile-First Responsive Design:** Seamlessly adapts across smartphones, tablets, laptops, and ultra-wide screens.
- 🎨 **Artisanal Haute Parfumerie Aesthetics:** Curated color palette (`#9f7aea`, `#d6bcfa`, `#111827`), elegant Google Fonts (*Pacifico*, *Playfair Display*, *Poppins*), and crisp vector icons from Remix Icon.
- 🌿 **Dedicated Brand Story & About Section:** Detailed breakdown of artisanal distillation, Extrait de Parfum concentrations (12+ hour wear), sustainable botanical sourcing, and London heritage.
- 🛍️ **Signature Product Showcase:** Interactive product catalog featuring signature blends (*Rosewood Bliss*, *Woodland Walk*, *Lexus London*) with hover zoom effects, status tags (*Best Seller*, *Trending*), and pricing tiers.
- 🛒 **Interactive Micro-Interactions:** Custom toast notification system for instant visual feedback on "Add to Cart" and newsletter submissions.
- 💬 **Dynamic Customer Testimonial Slider:** Auto-cycling review carousel highlighting verified client feedback with smooth transitions.
- 🔍 **SEO & Social Sharing Ready:** Full Open Graph (`og:`) and Twitter Card metadata for rich previews when shared across social channels.
- 🚀 **Zero Dependencies & Fast Load Times:** Standalone, dependency-free architecture powered by Tailwind CDN and modern browser APIs.

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure, accessibility (`aria-*`), and Open Graph metadata |
| **Tailwind CSS 3.4** | Utility-first responsive styling and theme extension |
| **Vanilla JavaScript (ES6+)** | Mobile drawer navigation, testimonial rotation, and toast feedback |
| **Remix Icon 4.6** | Lightweight, scalable vector iconography |
| **Google Fonts** | *Playfair Display* (Editorial headings), *Poppins* (Body), *Pacifico* (Script logo) |

---

## 📂 Project Structure

```bash
Perfume-E-Comm/
│
├── .github/
│   ├── workflows/
│   │   └── deploy.yml          # Automated GitHub Pages deployment
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md       # Standardized bug reporting template
│   │   └── feature_request.md  # Standardized feature proposal template
│   └── pull_request_template.md # PR guidelines and checklist
│
├── images/
│   ├── bg1.jpg                 # Hero banner background photography
│   ├── perfume.png             # Logo flacon artwork & favicon
│   ├── pr1.jpg                 # Product 1: Rosewood Bliss
│   ├── pr2.jpg                 # Product 2: Woodland Walk
│   └── pr3.jpg                 # Product 3: Lexus London
│
├── .gitignore                  # Git ignore rules for clean repository state
├── index.html                  # Main application & landing page
├── LICENSE                     # MIT License
└── README.md                   # Comprehensive repository documentation
```

---

## 🚀 Quick Start & Local Preview

You don't need complicated build tools or Node.js to run this project!

### Option 1: Direct Browser
Simply double-click `index.html` or open it directly in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: VS Code Live Server
1. Open the project folder in **VS Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and click **"Open with Live Server"**.

### Option 3: Python Local Server
Run in PowerShell / Terminal:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

---

## 🎨 Customization Guide

### Changing Theme Colors
In `index.html`, locate the Tailwind configuration script in the `<head>`:
```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: '#9f7aea',    // Primary accent (Lavender Purple)
        secondary: '#d6bcfa'   // Soft pastel accent
      }
    }
  }
}
```

### Adding New Products
Add a new product card into the `<section id="products">` grid:
```html
<div class="bg-white p-6 rounded-xl shadow-sm flex flex-col ...">
  <img src="./images/your-image.jpg" alt="Your Fragrance Name" ...>
  <h3 class="text-2xl font-bold mb-2">Your Fragrance Name</h3>
  <p class="text-gray-600 mb-4 text-sm">Scent description and notes...</p>
  <button onclick="handleAddToCart('Your Fragrance Name')">Add to Cart</button>
</div>
```

---

## 🤝 Contributing

Contributions, issues, and feature suggestions are welcome!

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'feat: add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for full details.

---

## 👤 Author

**Harry Kalsi**
- GitHub: [@Harrykalsi24](https://github.com/Harrykalsi24)
- Repository: [Perfume-E-Comm](https://github.com/Harrykalsi24/Perfume-E-Comm)

⭐ If you find this project inspiring or helpful, please consider giving it a star on GitHub!
