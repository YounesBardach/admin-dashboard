<p align="center">
  <img src="https://i.postimg.cc/FF8St1kV/Chat-GPT-Image-Aug-13-2025-02-52-24-AM.png" alt="Blog API Banner" width="900" />
</p>

<div align="center">

# Admin Dashboard (CSS Grid)

Practice project to build a full dashboard layout using modern CSS Grid. Part of
The Odin Project — Intermediate HTML & CSS.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![CSS Grid](https://img.shields.io/badge/CSS-Grid-2965f1?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS/CSS_grid_layout)
[![Normalize.css](https://img.shields.io/badge/Normalize.css-8.0.1-4B5563)](https://necolas.github.io/normalize.css/)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222?logo=github&logoColor=white)](https://pages.github.com/)

</div>

---

## Table of Contents

- [Live URL](#live-url)
- [Quick start (local)](#quick-start-local)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Project structure](#project-structure)
- [Notes](#notes)

---

## Live URL

- GitHub Pages: https://younesbardach.github.io/admin-dashboard/

---

## Quick start (local)

```bash
# Navigate into the project folder
cd admin-dashboard
```

Then open `index.html` with Live Server (e.g., in VS Code: right‑click
`index.html` → Open with Live Server).

---

## Features

- Full‑page layout built with CSS Grid
- Nested grids for sidebar, header, and main content
- Responsive project card grid using `repeat(auto-fit, minmax(200px, 1fr))`
- Accessible focus styles and sensible defaults via Normalize.css

---

## Tech stack

- HTML5
- CSS3
  - CSS Grid
  - Normalize.css

---

## Project structure

```
admin-dashboard/
  index.html
  css/
    normalize.css
    style.css
  img/
    cat-*.jpg
  favicon files and site.webmanifest
```

Key regions are organized with grid:

- Sidebar navigation (`.sidebar`)
- Header with search/user/actions (`.actions`)
- Main content (`.content`) split into projects and a right sidebar
- Cards grid (`.cardboard`) using `auto-fit` + `minmax`

---

## Notes

- Uses a system font stack and rem‑based sizing
- Layout is fluid; card grid adapts to available width
---
