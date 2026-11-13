# AURA ONE — 3D Earbuds Website

Complete static website source for Muzammil.

## Run

Run `python -m http.server 8000` in this folder, then open http://localhost:8000.
Use an HTTP server, not a file:// URL, because app.js imports an ES module.

## Deploy

Upload all files to the repository root. This static website has no build step or backend.
For Vercel, import the repository, select Other, leave the build command empty and serve the root directory.

## Files

- index.html: page layout
- style.css: responsive styling
- app.js: 3D geometry, materials, animations and controls
- three.module.js: bundled Three.js r170
- THIRD_PARTY_LICENSES.txt: Three.js license

## Features

Real 3D earbuds and case; scroll-driven rotation; exploded view; drag rotation; color selection; auto-rotation control; responsive mobile layouts; reduced-motion preference; software 3D compatibility renderer when WebGL is unavailable.

## Limits

Fictional product demo. Internals are illustrative geometry. No payments, audio processing, or actual noise cancellation. Google Fonts uses an external connection with system-font fallbacks. The test browser disabled WebGL, so compatibility rendering and controls were verified, but WebGL lighting remains visually unverified.
