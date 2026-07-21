# 🪐 Personal Portfolio Website

A dark, futuristic single-page portfolio showcasing skills, projects, and experience — built with a custom particle-canvas background, neon cyan/purple/pink theme, and scroll-driven animations.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Sections](#sections)
- [Deployment](#deployment)
- [Roadmap](#roadmap)
- [Author](#author)

---

## Overview

This is a single-file HTML/CSS/JS portfolio site built to present a personal profile as a developer — combining a canvas-based particle/grid background, glassmorphism cards, and smooth scroll navigation, all without any external framework dependency.

---

## Features

- 🎨 **Custom Neon Theme** — cyan/purple/pink palette on a deep dark background
- ✨ **Animated Canvas Background** — particle/grid drift effects rendered on `<canvas>`
- 🖱️ **Custom Cursor** — dual-layer cursor with trailing ring effect
- 📱 **Responsive Layout** — CSS Grid hero layout that adapts to mobile
- 🪄 **Scroll Animations** — fade/slide-in transitions as sections enter the viewport
- 💠 **Glassmorphism Stat Cards** — blurred, bordered cards for skills and stats

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Custom CSS (CSS variables, no framework) |
| Fonts | Space Mono, Syne, Inter (Google Fonts) |
| Interactivity | Vanilla JavaScript, Canvas API |
| Hosting | GitHub Pages |

---

## Project Structure

```
Portfolio/
├── index.html      # Entire site — markup, styles, and scripts in one file
└── README.md
```

---

## Prerequisites

None — this is a static site. Any modern browser can render it directly.

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/marwanramiz/Portfolio.git
   cd Portfolio
   ```

2. **Open locally**
   ```bash
   open index.html
   ```
   Or serve it with any static file server:
   ```bash
   npx serve .
   ```

---

## Sections

| Section | ID | Description |
|---|---|---|
| Hero | `#hero` | Name, title, animated intro card with skill pills and stats |
| About | `#about` | Background summary |
| Skills | `#skills` | Technical skill breakdown |
| Projects | `#projects` | Featured project showcase |
| Experience | `#experience` | Internship/experience timeline |
| Contact | `#contact` | Contact links and call-to-action |

---

## Deployment

Hosted using **GitHub Pages**:
👉 [https://marwanramiz.github.io/Portfolio](https://marwanramiz.github.io/Portfolio)

Also deployed via Netlify at `marwanramiz.netlify.app`.

---

## Roadmap

- [ ] Split single-file HTML into modular CSS/JS files for maintainability
- [ ] Add a dedicated projects.html page with expanded case studies
- [ ] Add a blog/writing section
- [ ] Add dark/light theme toggle
- [ ] Optimize canvas animation performance on low-end mobile devices

---

## License

This portfolio is personal and proprietary. Feel free to explore, but reproduction or reuse is not permitted without permission.

---

## Author

**Marwan Ramiz**
[GitHub](https://github.com/marwanramiz) · [LinkedIn](https://linkedin.com/in/marwan-ramiz-m-8584a9326)
