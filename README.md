# Slothdoku — For Haley ❤️

## GitHub Pages
1. Create a public GitHub repository named `slothdoku`.
2. Upload the contents of this folder to the repository root (including `index.html`, `puzzles.js`, icons, manifest, and `sw.js`).
3. In repository Settings → Pages, choose Deploy from a branch → main → /(root) → Save.
4. Visit `https://YOUR-USERNAME.github.io/slothdoku/` once Pages finishes publishing.
5. On iPhone, open that URL in Safari → Share → Add to Home Screen.

No backend, dependencies, build step, or paid hosting needed. Progress is saved on the current browser/device (localStorage). Offline use is supported after the first successful load on HTTPS.

## Gameplay
- One sloth per row, column, and irregular colored region. Sloths cannot touch diagonally.
- Four chances for wrong sloth placements. X marks and undo do not cost chances.
- Tap to place a sloth, double tap to mark X, or select X mode and swipe. Tap an existing X to erase it.
- Correctly marking every square in a row/column/region triggers a clear announcement and points animation; sloths remain in place as required by the puzzle rules.
- Three hints per puzzle. No timer and no speed-based score.
- Two introductory easy puzzles, then random board sizes/difficulty.

## Notes
- All quote cards are original genre-inspired writing; they are not attributed to real books. Add only verified, properly credited short book excerpts if desired.
- Audio uses original generated tones/jingles (Web Audio). The iPhone physical Silent switch cannot be reliably detected from a web app. In-game mute and music/SFX sliders work.
- Profile customization, rewards, progress, and settings persist only on the same device/browser. No cloud account/sync.
- The puzzle bank is finite and cycles after exhaustion; level order is randomized, and repeated puzzles may eventually appear.


V4 visual update: original illustrated 2.5D sloth assets, new app icons, dimensional board and buttons.

## V5 Leaf Garden design
- Unique botanical garden-tray board, with rotated leaf-shaped cells, organic textures and raised edges.
- All gameplay, puzzle data, audio, personalization and save keys retained from V4.
- Service worker cache bumped for the visual refresh.
