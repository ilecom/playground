# Pocket Snake

A classic Snake game in one HTML file (no build step, no dependencies). It works in Safari on Mac and iPhone.

## Play

- **Mac:** open `index.html` in Safari or Chrome. Use the arrow keys or WASD to steer, Space to pause, M to turn music on or off, Enter to restart.
- **iPhone:** host the file anywhere (GitHub Pages works), open it in Safari, then tap Share → **Add to Home Screen**. It then opens full screen like an app. Keep your thumb on the big steering pad and slide it toward a direction to turn, or swipe on the game screen.

## Features

- 20×20 board; walls wrap around, so only running into yourself ends the game
- Starts slow and speeds up a little with every piece of food
- Every 10 points: new level, new handset colors, confetti, a level-up jingle and faster music
- Chiptune background music and sound effects, made in the browser (no audio files)
- Keyboard, swipe and a large thumb steering pad; queued turns so quick double-turns register
- Best score is saved on the device
- Pauses on its own when you switch apps or tabs
- Respects iPhone safe areas (notch / home indicator) and blocks accidental zoom

## Hosting on GitHub Pages

Repository Settings → Pages → deploy from this branch, root folder. The game will be at `https://<user>.github.io/<repo>/`.
