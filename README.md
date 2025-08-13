<p align="center">
  <img src="img/cat-logo.jpg" alt="Admin Dashboard Banner" width="160" />
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

- [Requirements](#requirements)
- [Live URL](#live-url)
- [Quick start (local)](#quick-start-local)
- [Features](#features)
- [Tech stack](#tech-stack)
- [Project structure](#project-structure)
- [Notes](#notes)
- [Attributions](#attributions)
- [Reference](#reference)

---

## Requirements

- Any modern browser
- No build tools required

## Live URL

- GitHub Pages: replace with your deployment URL (e.g.,
  `https://<username>.github.io/admin-dashboard/`)

---

## Quick start (local)

```bash
# Option 1: open the file directly
open index.html  # or double‑click in your file explorer

# Option 2: serve locally (Python 3)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

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
- Manifest and favicon paths are relative for GitHub Pages compatibility

---

## Attributions

- Icons: Material Design Icons
- Photos and credits (also referenced in `css/style.css`):
  - Orange Tabby Kitten on Green Plant — Chris Clark:
    https://www.pexels.com/photo/orange-tabby-kitten-on-green-plant-12109413/
  - Rémi Rémino: https://unsplash.com/@remino
  - Cédric VT: https://unsplash.com/@cedric_photography
  - Melanie Andersen: https://unsplash.com/@frolleinandersen
  - The Lucky Neko: https://unsplash.com/@theluckyneko

---

## Reference

- The Odin Project assignment:
  https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard
