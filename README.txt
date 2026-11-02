SHADOW ZOMBIE — Browser Game
================================

Files:
- index.html: game interface
- style.css: visual design, HUD and responsive layout
- game.js: game logic, flashlight, pistol, laser sight, bullets, zombie AI, health, ammo, batteries, score and timer

Run:
1. Extract the ZIP file.
2. Open the shadow_zombie_game folder in VS Code.
3. Open index.html in your browser, or use the VS Code Live Server extension.
4. Click START SURVIVING.

Controls:
- WASD / Arrow keys: move
- Mouse: move the aim point
- Hold left mouse button: show the red laser sight and fire the pistol
- Space: toggle the brighter flashlight beam on/off
- R: reload the 12-round magazine
- Shift: sprint
- P: pause/resume

Gameplay:
- Hold the left mouse button to show the red laser sight; move the mouse to aim and shoot. The red line and target marker disappear when the button is released.
- Most zombies take two direct hits to defeat. Defeated zombies award score.
- The flashlight remains equipped alongside the pistol. Aim it at zombies to slow them while you line up a shot.
- Collect glowing yellow batteries to recharge the flashlight.
- Collect blue ammo crates to replenish reserve ammunition.
- Reloads take about one second. Keep moving while reloading.
- Survive as long as possible. Your best score is saved in browser localStorage.

The arena has brighter ambient visibility so the player and zombies are easier to see even when the flashlight is off. Press Space to toggle the forward-facing flashlight beam; the beam slows zombies in its path.

This browser game uses original Canvas-drawn graphics and requires no image assets or server.
