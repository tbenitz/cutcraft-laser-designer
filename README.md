# CutCraft — Laser SVG Designer

Browser-based laser design studio. Draw shapes, generate outlined text, trace images, add holding bridges, preview material fallout, and export a millimeter-accurate SVG for laser software such as LaserPecker Design Space.

**Repo:** https://github.com/tbenitz/cutcraft-laser-designer

## Run it

The designer is a single HTML file. Open `CutCraft_Laser_Designer.html` in Chrome, Edge, or Firefox. No server or build step is required. Projects autosave in the browser.

If that file is not in the repo yet, add it from the GitHub UI:

1. **Add file → Upload files**
2. Drop `CutCraft_Laser_Designer.html`
3. Commit to `main`

## GitHub Pages

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root
4. After the HTML app is in the repo, point Pages at that file or rename it to `index.html`

Live URL once Pages is on: https://tbenitz.github.io/cutcraft-laser-designer/

## Features

- Vector drawing tools (select, nodes, rect, ellipse, line, path, star, polygon)
- Outlined laser text with optional auto-stencil bridges for letter counters
- Image-to-vector tracing (silhouette, sketch, cartoon, halftone)
- Uncut holding bridges and tabs
- Material preview that shows loose pieces after cut fallout
- Preflight checks and color-separated SVG export (black engrave, blue score, red cut)
- 30 starting templates (coasters, tags, signs, ornaments, and more)

Export uses an SVG `viewBox` in millimeters and inline geometry. Import the file into your laser software as vector format and confirm material settings before cutting.
