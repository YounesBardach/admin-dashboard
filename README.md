<p align="center">
  <img src="https://i.postimg.cc/FF8St1kV/Chat-GPT-Image-Aug-13-2025-02-52-24-AM.png" alt="Blog API Banner" width="900" />
</p>

# Admin Dashboard (CSS Grid)

A simple admin dashboard built to practice modern CSS Grid layout techniques.
This project is based on the Intermediate HTML & CSS assignment from The Odin
Project.

Assignment link:
[Project: Admin Dashboard — The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard)

## Learning goals

- Practice building full‑page layouts with CSS Grid
- Nest grids for complex regions (sidebar, header, main content)
- Use `fr` units, `auto-fit/auto-fill`, and `minmax()` for responsive card grids
- Apply accessible focus styles and sensible defaults via Normalize.css

## Tech stack

- HTML5
- CSS3
  - CSS Grid
  - Normalize.css

## Project structure

```
admin-dashboard/
  index.html
  css/
    normalize.css
    style.css
  img/
    cat-*.jpg
  favicon.* and manifest files
```

Key regions are organized with grid:

- Sidebar navigation (`.sidebar`)
- Header with search/user/actions (`.actions`)
- Main content (`.content`) split into projects and a right sidebar
- Project cards grid (`.cardboard`) using `repeat(auto-fit, minmax(200px, 1fr))`

## Getting started

1. Clone or download this repository

2. Open `index.html` directly in a browser, or serve it locally:

```bash
# Using Python 3
python3 -m http.server 8000
# Then visit http://localhost:8000
```

No build step is required.

## Notes

- Styles use a system font stack and rem‑based sizing
- Focus-visible styles are enabled for keyboard navigation
- Layout aims to be fluid but is not strictly responsive beyond the card grid

## Attributions

- Icons: Material Design Icons
- Photos and credits (as referenced in `css/style.css`):
  - Orange Tabby Kitten on Green Plant — Chris Clark:
    https://www.pexels.com/photo/orange-tabby-kitten-on-green-plant-12109413/
  - Rémi Rémino: https://unsplash.com/@remino
  - Cédric VT: https://unsplash.com/@cedric_photography
  - Melanie Andersen: https://unsplash.com/@frolleinandersen
  - The Lucky Neko: https://unsplash.com/@theluckyneko

## Reference

- The Odin Project assignment:
  https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard
