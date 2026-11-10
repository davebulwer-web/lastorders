# Last Orders

Pub games, played on one button. An `index.html` plus PNGs in `art/`: serve the folder (or open the file) in a browser, no build step.

- **Shell**: games room, 480×270 pixel playfield scaled nearest-neighbour, fixed 120Hz clock, scorecard.
- **Games** are modules that honour one contract: `init`, `update`, `render`, `press`, `settled`, `result` (plus `hud`, `prompt`, `action`).
- **Art** is made with PixelLab and drawn 1:1. Bar Skittles and the room backdrop have real art; Shove Ha'penny is still placeholder blocks. Missing art falls back to the blocks.
