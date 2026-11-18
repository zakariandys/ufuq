# Ufuq · أُفُق

A prayer times PWA (Progressive Web App). The background sky changes with the sun's position at your location: dawn, day, dusk and night.

- Prayer times are calculated on the device (no server, no API)
- Muslim World League method: Fajr 18°, Isha 17°, Asr Shafi'i
- Dhuha: sun at 4.5° above the horizon
- Automatic location via GPS, or pick a city / enter coordinates manually
- Installable to the home screen and works offline

## Install on your phone
- **Android (Chrome):** open the site, then menu ⋮ → *Install app*
- **iPhone (Safari):** Share button → *Add to Home Screen*

## Updating
Edit the files, commit and push. If you change the list of app files, bump `VERSION` in `sw.js` so the old cache gets replaced.
