# OudoFigma

Screen props for the Forsa Saeeda shoot.

## Phone tracking prop (`docs/`)

A self-contained web page that imitates a phone-locating app. It shows the device
"iPhone Jad" leaving Alexandria and driving the Cairo–Alexandria Desert Road toward
Cairo, with a live-updating position, address and distance. No logos or brand marks.

- `docs/index.html` — the page. On an iPhone open it in Safari, then Share → Add to Home Screen
  and launch it from the home screen so it runs full screen with the real status bar.
- `docs/data.js` — map geometry built from OpenStreetMap data (© OpenStreetMap contributors, ODbL).
- Director panel: triple-tap the sheet handle. Controls speed, position, update interval,
  the wife's location, device name, owner name, battery and the fake status bar.

Published with GitHub Pages from the `gh-pages` branch, which holds a copy of `docs/`:
https://oudoo.github.io/OudoFigma/ — to publish an update, copy `docs/` onto `gh-pages` and push.
