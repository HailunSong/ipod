# Darcie 床头屏 · iPod touch 5

An old iPod touch 5 (iOS 9) turned into a bedside screen: clock, Edmonton weather and what to wear,
a French word of the day, and Darcie the little black dog travelling the world and sending postcards.

- Page: https://hailunsong.github.io/ipod/
- `index.html` — the whole screen (plain ES5 + old-WebKit CSS so iOS 9 Safari can run it)
- `screen.appcache` — offline cache; **bump the version number after every change to index.html**
- `weather.json` — written by `.github/workflows/pages.yml` every 30 minutes (Open-Meteo)
- `photos/<n>.jpg` — one photo per stop (n = position in TRIP), `photos/thumbs/` for the album,
  `photos/credits.json` — Wikimedia Commons author and licence for each photo
