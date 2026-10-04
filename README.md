# Hello Neighbor: The dark secrets

Playable browser game.

Game URL:
https://alextube50.github.io/Hello-neighbor/

## Controls
- Click PLAY
- WASD — move
- Mouse — look
- Shift — sprint
- Space — jump
- E — open/close the front door
- R — restart after being caught

## Current game structure
The game has a self-contained browser renderer with no required external 3D libraries. The renderer now uses high-resolution ray columns and a deterministic startup check. This keeps the game playable even if optional imported models are unavailable.

The player starts on the grass behind the house, opposite the road.

Every push to main automatically deploys through GitHub Pages.


## Recent visual update

The imported house model is no longer loaded by the browser game. The lawn uses layered procedural shading and dense grass-blade rendering for a more realistic appearance.
