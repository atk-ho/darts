# 🎯 DARTHS — Darts Scoreboard

**DARTHS** is a mobile-friendly, installable darts scoring web app (PWA), built with HTML, CSS and JavaScript. It is designed for casual matches, multiplayer games and team play.

**Play online:** https://atk-ho.github.io/DARTHS/  
**Source code:** https://github.com/atk-ho/DARTHS

## Features

- Starting scores from 101 to 1001; configurable sets and legs
- Straight, Double or Master check-in and checkout
- Free-for-all games and teams of 2–5 players
- Single scoring by default; tap **Double** or **Triple** to apply it to the next dart only
- Live scoreboard showing each player's remaining score, last three darts, turn total, darts thrown and average
- Green indicator for the active player; red dart boxes on a bust
- Automatic turn rotation, bust detection and a single Undo button
- Player management, match history, statistics, spoken score announcements and optional sounds
- Bottom navigation and offline support after the app's files have been cached
- Local storage for players, match progress and history; no account required

## Install on Android

1. Open https://atk-ho.github.io/DARTHS/ in **Google Chrome**.
2. Tap **⋮ → Install app** (or **Add to Home screen**, if offered).
3. Confirm and launch DARTHS from your home screen.

The app must be served over HTTPS for its PWA features to work. Opening `index.html` directly from phone storage does not install it as a PWA.

## Publish with GitHub Pages

1. Upload `index.html`, `manifest.webmanifest`, `sw.js` and the `icons/` folder to the **root** of your `DARTHS` repository.
2. In GitHub, open **Settings → Pages**.
3. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then save.
4. Wait for the deployment to finish and open the live link above.

## Project structure

```text
DARTHS/
├── index.html
├── manifest.webmanifest
├── sw.js
├── README.md
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Technology

HTML5 · CSS3 · Vanilla JavaScript · localStorage · Web App Manifest · Service Worker · GitHub Pages

## Data and updates

Game data is stored on your device, not in your GitHub repository. Clearing the app/browser's site data may delete saved games and players. Use **Settings → Export data** to keep a JSON backup. Replacing files on GitHub Pages may take a few minutes to deploy; an installed app may need to reconnect and reload to fetch the new version.

## Developer

**Arthur Reguindin Jr.**  
GitHub: [@atk-ho](https://github.com/atk-ho)

## License

Copyright © 2026 Arthur Reguindin Jr. All rights reserved unless a separate license is provided.

---

*DARTHS — Score Every Dart. Track Every Win.*
