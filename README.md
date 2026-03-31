# Stinkmap 💨

A social heatmap PWA where you rate how stinky a place is — and see the world's stink map.

## Features

- 🗺️ **Heatmap** — see all stink ratings visualized as a global heatmap
- 💨 **Rate** — pin your current GPS location with a stink intensity (1–5)
- 📍 **Markers** — tap any emoji marker for details
- 📱 **PWA** — installable to home screen (iOS & Android)
- 💾 **Offline** — ratings stored locally in `localStorage`

## Tech

- Leaflet.js + leaflet-heat (CDN, no build step)
- Vanilla HTML/CSS/JS
- Service worker for offline support

## Deploy (GitHub Pages)

```bash
git init && git add . && git commit -m "Initial stinkmap"
gh repo create stinkmap --public --push --source=.
# then enable GitHub Pages → source: /docs branch
```

Live at: `https://<you>.github.io/stinkmap/`
