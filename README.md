# The Loopy Looms 🧶

A personal portfolio website for **The Loopy Looms** — a handcrafted crochet portfolio featuring amigurumi, bag charms, coasters and nature-inspired keepsakes, made one stitch at a time.

🔗 Instagram: [@theloopylooms](https://www.instagram.com/theloopylooms/)

---

## About

This is a single-page portfolio site built with plain HTML and CSS — no frameworks, no dependencies. It showcases handmade crochet work and links visitors to the Instagram profile.

## Features

- Fully responsive (mobile, tablet, desktop)
- Hero section with stats and floating badge
- Portfolio cards (Amigurumi, Bag Charms, Home Decor)
- Craft process section (4 steps)
- About / story section with layered image layout
- Pull quote section
- Instagram feed grid (8 photos)
- Botanical SVG doodles as decorative accents
- Smooth scroll navigation

## Structure

```
theloopyloom/
├── index.html        # Single-page site (HTML + CSS inline)
└── images/           # All product/portfolio photos
    ├── IMG_8343.jpeg
    ├── IMG_8196.jpeg
    ├── IMG_7128.jpeg
    ├── IMG_8103.jpeg
    ├── IMG_6615.jpeg
    ├── IMG_8124.jpeg
    └── ...
```

## Tech Stack

- HTML5
- CSS3 (custom properties, grid, flexbox, `clamp()`)
- Google Fonts — [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Jost](https://fonts.google.com/specimen/Jost)
- Inline SVG for icons and botanical doodles
- No JavaScript, no build step

## Running Locally

Just open `index.html` in any browser — no server needed.

```bash
# Clone the repo
git clone https://github.com/your-username/theloopyloom.git

# Open in browser
start index.html        # Windows
open index.html         # macOS
```

## Customisation

All design tokens (colours, spacing, border radius) are defined as CSS custom properties at the top of the `<style>` block:

```css
:root {
  --cream:      #fdf8f2;
  --sage:       #8aa898;
  --rose:       #c9798a;
  --brown:      #3d3530;
  /* ... */
}
```

To swap photos, replace the image files in the `images/` folder and update the `src` attributes in `index.html`.

---

*Made with 🧶 & lots of love — The Loopy Looms*
