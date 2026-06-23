# AI Restaurant Adventure

A single-page Phaser educational RPG for Grade 6 English learners.

## Start

Open `index.html` through a local web server. For example:

```powershell
python -m http.server 8080
```

Then open <http://localhost:8080>.

The game saves mission progress, badges, level and XP in the browser's local storage. Speech practice uses the browser's Web Speech API; Chrome or Edge is recommended.

## Offline engine

The page first loads `vendor/phaser.min.js`. If the local engine file is unavailable, it falls back to the jsDelivr CDN.
