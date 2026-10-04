# Hello Neighbor: The Murder

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
