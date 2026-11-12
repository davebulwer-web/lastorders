# Last Orders

Pub games, played on one button. An `index.html` plus PNGs in `art/`: serve the folder (or open the file) in a browser, no build step.

- **Shell**: games room, 480×270 pixel playfield scaled nearest-neighbour, fixed 120Hz clock, scorecard.
- **Games** are modules that honour one contract: `init`, `update`, `render`, `press`, `settled`, `result` (plus `hud`, `prompt`, `action`).
- **Art** is made with PixelLab and drawn 1:1. Both games and the room backdrop have real art. Missing art falls back to the blocks.

## Publishing

Lives at `https://airetrogames.co.uk/games/last-orders/`. Upload `index.html`, `icon.png`, `apple-touch-icon.png`, `social.png` and the whole `art/` folder into that folder; every path is relative except the canonical and social-preview URLs in the `<head>`, which name that address (change them if the folder moves). `README.md` does not need uploading.
