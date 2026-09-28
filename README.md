# Silhouette Word Cloud Studio

By Danvion Michael Grant.

A single-file browser application that fills built-in shapes, lettering, or uploaded silhouettes with words sized by frequency or explicit weights.

## Run

Open `index.html` in a modern browser. No installation, server, or build step is required. For local serving, run `python -m http.server 8000` in this folder and open http://localhost:8000.

## Features

- Built-in shapes, text masks, uploaded images, threshold detection, inverted masks.
- Free text and weighted word lists; stop-word filtering and case controls.
- Five embedded Tunsicelody fonts, local font imports, and Google Fonts.
- Palettes, frequency gradients, image-derived colors, outlines and transparency.
- Adjustable word angles, density, spacing, size contrast and canvas proportions.
- PNG and SVG exports with the application's existing author and copyright notices.

## Dependencies and limits

The application contains its CSS, JavaScript, procedural shapes and five fonts in one HTML file. Google Fonts requires a connection; embedded and available local fonts can be used offline. SVG exports may refer to remote fonts and include raster layers; they are not guaranteed to be entirely vector artwork. Large exports can exceed browser memory. Settings and uploads are not saved as a persistent project.

See USER_GUIDE.md, ATTRIBUTIONS.md, COPYRIGHT.md, and VALIDATION.md. This package preserves the supplied HTML byte-for-byte under the conventional name `index.html`.

## Rights

Original application notice: © 2026 Danvion Michael Grant — all rights reserved. Embedded third-party font components retain their own licenses in `licenses/`. No open-source license has been added to the application.
