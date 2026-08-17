# studio-arc-responsive-ui-decodelab-1# 🏛️ Studio Arc — Responsive Frontend Interface

**Project 1 of the DecodeLabs Full Stack Development Internship (2026 Batch)**

A fully responsive, mobile-first landing page built with **pure HTML5, CSS3, and vanilla JavaScript — no frameworks**. This project demonstrates semantic markup, CSS Grid + Flexbox layout systems, fluid typography, and lightweight interactive state management.

🔗 **Live Demo:** https://\<your-username>.github.io/studio-arc-responsive-ui/

---

## 📸 Preview

| Desktop | Tablet | Mobile |
|---|---|---|
| ![Desktop view](./screenshots/desktop.png) | ![Tablet view](./screenshots/tablet.png) | ![Mobile view](./screenshots/mobile.png) |

---

## ✨ Features

- **Mobile-first responsive layout** with breakpoints at `768px` (tablet) and `1024px` (desktop)
- **Semantic HTML5 landmarks** — `<header>`, `<nav>`, `<main>`, `<article>`, `<footer>` for accessibility and SEO
- **CSS Grid** for macro page structure, **Flexbox** for micro components (nav, buttons, footer)
- **Fluid typography** using `clamp()` — no jarring font-size jumps between breakpoints
- **Dark mode toggle** powered by vanilla JS state + CSS custom properties
- **Animated stat counters** using `IntersectionObserver`
- **Accessible by default** — visible focus states, `aria-*` attributes, reduced-motion support

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Structure | HTML5 (semantic landmarks) |
| Styling | CSS3 (Grid, Flexbox, custom properties, `clamp()`) |
| Interactivity | Vanilla JavaScript (no libraries/frameworks) |

## 📁 Project Structure

```
project1/
├── index.html      # Semantic page structure
├── style.css        # Design tokens, layout, responsive breakpoints
├── script.js        # Nav toggle, theme toggle, stat counters
└── README.md
```

## 🎨 Design System

| Token | Value | Role |
|---|---|---|
| Mocha Mousse | `#A5936F` | Stability / primary accent |
| Ethereal Blue | `#A0D4E0` | Trust / secondary accent |
| Moonlit Grey | `#F2F0EA` | Refinement / background |

**Typography:** Montserrat / Inter (headings) · Roboto / Open Sans (body)

## 🚀 Getting Started

No build step required — this is a static, dependency-free project.

```bash
git clone https://github.com/<your-username>/studio-arc-responsive-ui.git
cd studio-arc-responsive-ui
open index.html   # or just double-click the file
```

## 🌐 Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**, then **Save**.
5. Wait ~1 minute — your live URL will appear at the top of that same page:
   `https://<your-username>.github.io/studio-arc-responsive-ui/`
6. A `.nojekyll` file is included so GitHub Pages serves the raw HTML/CSS/JS without Jekyll processing.

## ✅ Internship Checklist

- [x] HTML, CSS, and basic JavaScript
- [x] Responsive layout across mobile, tablet, and desktop
- [x] Clean, user-friendly, accessible UI
- [x] No external frameworks — fundamentals only

---

Built as part of the **DecodeLabs Internship Program**, Batch 2026.
