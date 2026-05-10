# Skyline Zero

Skyline Zero is a stylish browser game built to deploy cleanly on GitHub and Vercel.

You dodge hunter drones in a neon skyline, chain spark pickups into combos, and chase a better run every time. The project is intentionally static-first, so wrzucenie go na GitHuba albo Vercela jest bezproblemowe.

## Why this fits Vercel

- no backend required,
- no database required,
- instant static deploy,
- easy GitHub import,
- fast loading and mobile-friendly layout.

## Features

- canvas arcade gameplay with keyboard controls,
- dash, shield, and slow-time mechanics,
- local leaderboard saved in `localStorage`,
- share-ready end screen with replay loop,
- bold cyber-arcade visual style.

## Controls

- `A` / `D` or left / right arrows to move
- `Space` to dash
- collect sparks for combo
- collect shield and slow-time capsules to survive longer

## Deploy to Vercel

1. Push the repo to GitHub.
2. Import the repo into Vercel.
3. Deploy as a static site.

No environment variables or build step are needed.

## GitHub ready

Repo jest przygotowane jako zwykły statyczny projekt:

- `index.html`
- `app.js`
- `styles.css`
- `vercel.json`

To oznacza, że możesz:

1. wrzucić cały folder jako repo na GitHubie,
2. podpiąć repo do Vercela bez build stepu,
3. albo odpalić to nawet przez GitHub Pages po lekkim dostosowaniu ścieżek, jeśli kiedyś zechcesz.

## Project layout

```text
index.html
app.js
styles.css
vercel.json
```
