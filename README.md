# Last Orders

Pub games, played on one button. A single self-contained `index.html`: open it in a browser, no build step.

- **Shell**: games room, 240×160 pixel playfield scaled nearest-neighbour, fixed 120Hz clock, scorecard.
- **Games** are modules that honour one contract: `init`, `update`, `render`, `press`, `settled`, `result` (plus `hud`, `prompt`, `action`).
- All art is placeholder blocks drawn at final sprite sizes.
