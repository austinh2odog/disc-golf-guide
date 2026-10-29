# Disc Golf Guide - GitHub Pages deployment

## Included
- `index.html` loads the global library from `data/courses.csv`
- `data/courses.csv` contains 24 layouts and 387 hole rows
- Global course data is read-only in the app
- Personal layouts, rounds, scores, throws, and statistics remain in browser localStorage
- `manifest.webmanifest`, `sw.js`, and the HTML preserve the `dog-logo.png` icon path

## Required dog icon
Copy your existing `dog-logo.png` into the repository root beside `index.html`. The original app already references this filename.

## GitHub Pages
Upload all files and folders to the repository root. In Settings > Pages, publish from `main` and `/ (root)`.
