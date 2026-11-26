# Stacked Deck

A baseball draft game for iPhone browsers, with three modes: Classic, Rip Packs and GM Simulator.

Play: https://themileyfamily.github.io/stacked-deck/

## What's here

| Path | Contents |
| --- | --- |
| `index.html` | The game: home screen, Classic and Rip Packs, plus the GM button and loader |
| `gm.js` | GM Simulator (about 4 MB), loaded the first time the mode opens |
| `cards/` | 958 card images (WebP, 848 x 1264), one per pack player-decade |
| `.nojekyll`, `robots.txt` | Serve files as-is; ask search engines not to index the site |

This repo holds built files only. Sources, build scripts and tests are in the private repo `themileyfamily/stacked-deck-src`.

## Saves

Each player's saves stay in their own browser (localStorage and IndexedDB). The site has no server, login or tracking.

## Updating

Replace the changed files (for example a new `gm.js` from the source repo build), commit and push to `main`. GitHub Pages republishes in a minute or two.

## Data sources

Lahman Baseball Database (CC BY-SA 3.0), Baseball-Reference WAR, Chadwick Baseball Bureau register (ODC-By), and MLB Stats API draft data (individual non-commercial use). Not affiliated with MLB or any team.
