# Moonbeams // Cube Puzzle 🌙

A browser-based isometric cube-rolling puzzle game — installable as a PWA.

## Play

Host on GitHub Pages, then visit the URL on your phone and tap **"Add to Home Screen"**.

## How to Enable GitHub Pages

1. Push this folder to a GitHub repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Visit `https://yourusername.github.io/your-repo-name`

## How to Play

- **Arrow keys / WASD** to roll the cube
- **Swipe** on touch devices
- **R** to reset
- Paint every tile, then land on ◎ to win
- Moon-pads ✦ only lock when the cube's gold face rolls down onto them
- Ice tiles ❆ keep the cube sliding until it hits a wall, an edge, or plain floor
- 16 levels in all, from a two-move joke level to a six-mechanic finale
- Works fully offline once installed!

## Files

- `index.html` — the game
- `manifest.json` — PWA metadata
- `sw.js` — service worker (offline support)
- `icon-192.png`, `icon-512.png` — home screen icons
- `icon-192-maskable.png`, `icon-512-maskable.png` — safe-zone padded icons for Android's adaptive icon masks
