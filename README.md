# Tetris (HTML5)

Classic falling-block puzzle game in a single HTML file with no dependencies. It runs in any modern browser on desktop or mobile.

## Features

- All 7 pieces with SRS rotation and wall kicks, dealt from a 7-bag
- Hold piece, ghost piece, next-3 preview
- Soft drop and hard drop, lock delay
- Levels speed up every 10 lines
- Best score saved in the browser
- On-screen buttons for touch screens

## Controls

| Key | Action |
| --- | --- |
| ← → | Move |
| ↓ | Soft drop |
| ↑ / X | Rotate clockwise |
| Z / Ctrl | Rotate counter-clockwise |
| Space | Hard drop |
| C / Shift | Hold |
| P / Esc | Pause |

## Play locally

Open `index.html` in a browser.

## Deploy

`.github/workflows/pages.yml` publishes the game to GitHub Pages on every push to `main`. In the repo, under **Settings → Pages**, set **Source** to **GitHub Actions**.
