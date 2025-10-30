# Fruit Slicer

A small, playful browser-based demo that lets you "slice" fruit images and restart the scene. Built with plain HTML/CSS/JS and Tailwind for quick styling.

## Features
- Click a fruit to show its sliced version.
- Restart button resets all fruits.
- Lightweight, no build step required — just open `index.html`.

## How to run
Option 1 — open locally
- Double-click `index.html` to open it in your browser.

Option 2 — quick local server (recommended for consistent behaviour):

Windows PowerShell:

```powershell
python -m http.server 8000; Start-Process http://localhost:8000
```

## Project structure
- `index.html` — main markup, styles, and JS.
- `script.js` (if present) — optional separate script file.
- Images (apple-full.png.jpg, apple-half.png.jpg, etc.) used by the demo.

## Customization ideas
- Add slicing particle effects using Canvas or SVG.
- Add sound effects for slices and restarts.
- Make the layout responsive for mobile with stacked fruits.

---

