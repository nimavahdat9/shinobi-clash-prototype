# SHINOBI CLASH: THE LEGENDS OF CHAKRA
## Browser Prototype — Milestone 1 / early Milestone 2

An original, small 3D browser prototype set in Ashenroot. This is not the full 5v5 MOBA and does not contain online multiplayer.

### Play
1. Open `index.html` through a local web server, or publish this repository with GitHub Pages.
2. The game imports Three.js from jsDelivr, so an internet connection is required.
3. Use:
   - `W A S D`: move
   - Mouse: aim / face direction
   - Left click or `Space`: basic blade strike
   - `Q`: Storm Step (dash; costs chakra)
   - `E`: Ember Bolt (projectile; costs chakra)
   - `R`: Sundering Burst (area ultimate; costs chakra)

### Included in this prototype
- Procedurally built 3D arena and central Chakra Well.
- Original placeholder Kagetsura-inspired hero.
- Four training guardians with simple approach/contact-damage AI.
- Health, chakra regeneration, cooldown display, basic attack, dash, projectile and area ultimate.
- Defeated-enemy counter and restart after defeat.

### Known limitations
- Placeholder geometry only; no original production models, animation, or audio yet.
- Single-player only. Enemy behavior is local training AI, not networked players.
- No lanes, minions, towers, item shop, matchmaking, accounts, persistence, anti-cheat, or ranked mode.
- Combat values are prototype tuning values, not balance-tested.
- Three.js is loaded from a CDN; the first load requires internet access.
- No automated test suite or cross-browser performance test has been run in this package.

### Publish on GitHub Pages
1. Create a repository named `shinobi-clash-prototype`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the deployment and open the URL shown in the Pages section.

### Project direction
The long-term target in the master prompt is Unity/C# and Windows PC. This browser build is a fast playable experiment, not a direct substitute for a Unity production project. If the project moves to Unity, treat this prototype as a gameplay reference and preserve the Ashenroot lore and design decisions.
