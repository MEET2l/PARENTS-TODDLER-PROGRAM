# SPAXEECE — Parents Toddler Program Landing Page

A fully responsive, production-ready landing page for the **SPAXEECE Parents Toddler Program** — designed for children aged **1.5 to 3.5 years**, focusing on parent-child bonding, play-based learning, and holistic early development.

---

## 🚀 Live Preview

Open `index.html` in any modern browser — no build step required.

---

## 📁 Project Structure

```
parents-toddler-program/
├── index.html              # Main HTML file (semantic HTML5)
├── css/
│   └── style.css           # Full stylesheet (commented, mobile-first)
├── images/
│   ├── spaxeece_logo.jpg   # Brand logo (place your file here)
│   ├── hero.jpg            # (Optional) Local hero image
│   ├── activity1.jpg       # (Optional) Local activity image
│   ├── activity2.jpg       # (Optional) Local activity image
│   └── activity3.jpg       # (Optional) Local activity image
└── README.md
```

> **Note:** The landing page uses Unsplash CDN images as placeholders. Replace the `src` URLs in `index.html` with your local `/images/` paths for production deployment.

---

## 🎨 Brand Colors

| Token | Value | Usage |
|-------|-------|-------|
| `--color-black` | `#000000` | Header, text, dark sections |
| `--color-golden` | `#F4A300` | CTA buttons, highlights, accents |
| `--color-warm-white` | `#FFFDF5` | Page background |
| `--color-cream` | `#FEF8E7` | Alternate section backgrounds |

---

## 📄 Page Sections

1. **Sticky Header** — Logo + Navigation + Enroll CTA
2. **Hero Section** — "Building Bright Beginnings Together" + stats + CTA
3. **About the Program** — Image mosaic + feature list
4. **Why Choose Us** — 4 feature cards with icons
5. **Program Highlights** — 2×2 bento grid (parent participation, safe space, expert mentors, play-based learning)
6. **Daily Activities** — 6 activity cards with images
7. **Testimonials** — 3 parent reviews (featured center card in dark)
8. **Gallery** — CSS masonry-style photo grid
9. **Enrollment Form** — Name, child age, phone, email, message
10. **Footer** — Contact info, social links, quick links, copyright

---

## ⚙️ Technical Details

- **HTML5** semantic markup (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- **CSS Custom Properties** (variables) for theming
- **Mobile-first** responsive design with breakpoints at 400px, 640px, and 900px
- **CSS Grid & Flexbox** for all layouts
- **Intersection Observer API** for scroll-triggered reveal animations
- **No external CSS libraries** — pure vanilla CSS
- **Google Fonts** — Poppins + Playfair Display (loaded via CDN)
- **ARIA labels** and semantic roles for accessibility
- **Smooth scroll** navigation with active link highlighting
- **Form validation** (HTML5 native + JS feedback)

---

## 🧭 Getting Started

1. Clone or download the repository
2. Place `spaxeece_logo.jpg` in the `/images/` folder
3. Open `index.html` in a browser
4. For production: replace Unsplash image URLs with local image paths

---

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| IE 11 | ❌ Not supported |

---

## 📦 Deployment

This is a **static site** — deploy to any static hosting:

- **Netlify**: Drag & drop the folder
- **Vercel**: `vercel deploy`
- **GitHub Pages**: Push to `gh-pages` branch
- **Apache/Nginx**: Copy files to web root

---

## ✍️ License

© 2025 SPAXEECE. All rights reserved.

---

*Made with 💛 for little learners and the parents who walk alongside them.*
