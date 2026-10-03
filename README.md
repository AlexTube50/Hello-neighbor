# Hello Neighbor — Act 1

This repository contains a playable browser game prototype.

## Controls

- Click PLAY
- WASD = move
- Mouse = look
- Shift = sprint
- Space = jump
- E = open/close the front door
- R = restart after being caught

## Play it online

The repository includes a GitHub Actions workflow at
`.github/workflows/pages.yml` that deploys the game to GitHub Pages
when `main` changes.

After GitHub Pages is enabled for the repository, the deployed site uses
the repository's `index.html` as the game.

## Run locally

You can also serve the repository with any simple static web server and
open `index.html`.

The game loads Three.js from jsDelivr, so an internet connection is
needed for the 3D engine.

## Project structure

- `index.html` — game
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment
