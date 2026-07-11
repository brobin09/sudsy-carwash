# Sudsy's Car Wash — Fixed Build

A drive-through car wash game for very young players.

## Fixes in this build

- Automatic mode now recognizes completion immediately after the dryer.
- The conveyor automatically rolls the vehicle out, so releasing GAS cannot leave the game stuck.
- A celebration appears, then the game returns to the Home Screen automatically after about four seconds.
- The Home button remains available during play, and the celebration includes a **Home now** button.
- The service-worker cache was bumped to v3 so installed PWA copies do not keep serving the older bugged game.

## Visual improvements

- Deeper wet-pavement reflections and stable puddles
- Drain grates and wash-bay floor detail
- Industrial wall panels, darker baseboards, ceiling lights, and reflected tunnel lighting
- Existing water, foam, mist, brush, wax, and vehicle-reflection effects retained

## Files

- `index.html` — the game
- `manifest.webmanifest` — PWA manifest
- `sw.js` — offline caching and update behavior
- `icon-180.png`, `icon-192.png`, `icon-512.png` — app icons
