# Plane Angle Trainer

Interactive 3D geometry trainer: finding the angle between two planes in prisms/pyramids
(name the common line, then the angle; construction tools; hints; score/streak).exported 2026-10-31.

- Single self-contained file: `index.html` (vanilla HTML/CSS/JS, no build step).
- Only external dependency: Google Fonts (IBM Plex Sans / Serif).

## Features
- 11 question types over 4 levels (prisms, pyramids, cuboids, tetrahedra), with randomised numbers each time.
- Construction tools: foot on a line, foot on a plane, extend 2 lines, parallel line.
- Hints (−4 each), a two-tap "Show answer", score, streak, and a best score per round type (saved in the browser).
- Keyboard: type a point's letter to pick it, Backspace to undo a tap, Esc to cancel a tool.

## Run
Open `index.html` in a browser, or serve it:

    python3 -m http.server 8000   # then visit http://localhost:8000

## Hosting
Live: https://nixonchanmath.github.io/plane-angle-trainer/

GitHub Pages: Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`.
