# Hello Neighbor: The dark secrets

Playable browser prototype deployed from `main`.

Game URL:
https://alextube50.github.io/Hello-neighbor/

Controls:
- WASD: move
- Mouse: look
- Shift: sprint
- Space: jump
- E: open/close door
- R: restart after being caught

Every push to `main` automatically triggers the GitHub Pages workflow. After an update deploys, use Ctrl+Shift+R on the game URL to force-refresh the newest version.

The built-in scene is guaranteed to render without the optional FBX asset. If `assets/House_Hello_Neighbor_Act1.fbx` and its texture folder are present, the browser will try to load the imported house after startup.


## Imported assets

Upload the house model to:
`assets/house/House_Hello_Neighbor_Act1.fbx`

Upload its textures to:
`assets/house-textures/`

Upload the road model to:
`assets/road/road01.dae`

The game attempts to load both assets automatically and keeps the built-in scene as a fallback. The player spawns behind the house, opposite the road/front side.


## Main menu Neighbor

Upload these two files from the Secret Neighbor package:

`assets/menu-neighbor/SN Neighbor.fbx`
`assets/menu-neighbor/Texture.png`

The game loads the Neighbor model into the black main menu and rotates it slowly. Clicking **PLAY** switches to the game scene and starts the player on the grass behind the house.
