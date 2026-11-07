# Dunia Ceria – Browser MVP

A phone-friendly 3D educational world prototype for Malaysian children aged 4–6.

## Play
- Open `index.html` in a modern browser while connected to the internet. Three.js is loaded from jsDelivr CDN.
- On a phone, use the on-screen joystick to move. Tap **ZON** to teleport to a learning area, then tap **MISI** or walk close to a mission board.
- On a computer, use WASD or arrow keys.
- Learning stars, completed activities and avatar colour are saved in browser localStorage on that device.
- Tap the parent icon to view the local demonstration report.

## Publish from a phone using GitHub Pages
1. Create a GitHub repository named `dunia-ceria-web`.
2. Upload the contents of this folder (especially `index.html` and `game.js`) to the repository root.
3. In repository **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
4. Wait for the Pages deployment to finish. Open the published `https://YOUR-USERNAME.github.io/dunia-ceria-web/` URL on your phone.

## Current prototype limitations
- This is a browser preview, not the final Android APK.
- Multiplayer, friend approvals, server accounts, and cross-device parent reporting are not connected yet. This preview is single-player and stores progress only on the current browser/device.
- The parent dashboard is a local demonstration view and is not PIN-protected yet. Do not use it to store real child personal information.
- The 3D scene uses generated primitive shapes and placeholder art. Production-ready characters, sound, accessibility testing, child privacy controls and backend integration remain future work.
- Internet is required to load Three.js from the CDN. The project does not require npm or a build step.
