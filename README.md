# Pocket Snake

A classic Snake game in one HTML file (no build step, no dependencies). It works in Safari on Mac and iPhone.

## Play

- **Mac:** open `index.html` in Safari or Chrome. Use the arrow keys or WASD to steer, Space to pause, Enter to restart.
- **iPhone:** host the file anywhere (GitHub Pages works), open it in Safari, then tap Share → **Add to Home Screen**. It then opens full screen like an app. Swipe on the screen or use the on-screen pad to steer.

## Features

- 20×20 board that grows faster as you score
- Keyboard, swipe and d-pad controls; queued turns so quick double-turns register
- Best score is saved on the device
- Pauses on its own when you switch apps or tabs
- Respects iPhone safe areas (notch / home indicator) and blocks accidental zoom

## Hosting on GitHub Pages

Repository Settings → Pages → deploy from this branch, root folder. The game will be at `https://<user>.github.io/<repo>/`.
