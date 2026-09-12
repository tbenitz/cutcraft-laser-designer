# CutCraft — Laser SVG Designer

Browser-based laser design studio. Draw shapes, generate outlined text, trace images, add holding bridges, preview material fallout, and export a millimeter-accurate SVG for laser software such as LaserPecker Design Space.

## Use it

Open `index.html` in a modern browser. No build step and no server are required. Work stays local; projects autosave in the browser.

To run it on GitHub Pages:

1. Repo **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root
4. Save, then visit `https://tbenitz.github.io/cutcraft-laser-designer/`

## Features

- Vector drawing tools (select, nodes, rect, ellipse, line, path, star, polygon)
- Outlined laser text with optional auto-stencil bridges for letter counters
- Image-to-vector tracing (silhouette, sketch, cartoon, halftone)
- Uncut holding bridges and tabs
- Material preview that shows loose pieces after cut fallout
- Preflight checks and color-separated SVG export (black engrave, blue score, red cut)
- 30 starting templates (coasters, tags, signs, ornaments, and more)

## Files

- `index.html` — full CutCraft app (HTML, CSS, and JavaScript in one file)

Export uses an SVG `viewBox` in millimeters and inline geometry. Import the file into your laser software as vector format and confirm material settings before cutting.
