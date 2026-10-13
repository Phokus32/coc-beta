# Children of Chaos: Stormbound Coast Remaster

A mobile-first tactical RPG beta inspired by 16-bit console strategy RPGs, adapted from the user's Children of Chaos / Nævrdön campaign.

## What's new in this remaster
- Full visual overhaul toward a Shining Force / Shining Force II feel.
- Original pixel-style sprites instead of emoji-based figures.
- Cleaner Genesis-inspired UI windows, status panes, and title presentation.
- Pixel town scenes for Nævrdön and Thornwatch.
- Portrait panel and redesigned battle canvas.
- Same first-chapter structure: two towns, three battles, recruitable allies, leveling, items, saving, Iron Soul mode, retro sound effects.

## Publish to GitHub Pages
1. Create a GitHub repository.
2. Upload all files from this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**.
4. Wait for deployment, then open the GitHub Pages URL in Safari on iPhone.
5. Tap **Share → Add to Home Screen**.

## Files
- `index.html` — the full game.
- `manifest.webmanifest` — PWA metadata.
- `sw.js` — offline cache service worker.
- `icon.svg` — app icon.

## Notes
- Saves use localStorage per device/browser. Use export/import to back them up.
- First chapter includes Alabor, Duncan, Gwark, plus recruitable Seren, Kaelen, and Mila.
- This is a beta: it is playable and installable, but not exhaustively tested on physical iPhone hardware.
