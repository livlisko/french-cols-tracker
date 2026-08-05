# French Cols Tracker

Interactive tracker for two French cycling col challenges:

- **Cent(ish) Cols des Alpes françaises** — 113 cols across Savoie & Haute-Savoie (Chablais, Salève, Aravis, Mont Blanc, Beaufortain, Bauges, Avant-Pays, Chartreuse, Maurienne)
- **Challenge de la Ligne Bleue** — the official 41 cols along the historic 1871–1918 Franco-German border in the Vosges ([Club des Cent Cols](https://centcols.org/challenge-de-la-ligne-bleue/))

**Use it here → https://livlisko.github.io/french-cols-tracker/**

## How it works

- Explore all 113 Alps cols on an interactive 3D relief map, with searchable and filterable challenge markers
- Browse the Ligne Bleue challenge on its existing OpenTopoMap view
- Check off cols as you climb them — the date is stamped automatically (and editable)
- Paste a Strava activity link on any col to keep a record of the ride
- Progress is saved in your browser (localStorage) — nothing leaves your device
- **Export / Import Progress** buttons let you back up or move your tracker between devices

Want your own tracker? Just open the link — each visitor gets their own private progress.

## Data quality

All 154 col coordinates and elevations were verified against OpenStreetMap, the IGN Géoplateforme gazetteer, and IGN RGE ALTI ground elevations (every pin's terrain elevation matches its stated col elevation within 100 m). Ligne Bleue elevations follow the official Club des Cent Cols codes.

Built with [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/), [OpenFreeMap](https://openfreemap.org/), [Mapterhorn](https://mapterhorn.com/), and [Leaflet](https://leafletjs.com/). The Alps view falls back to OpenTopoMap when WebGL relief is unavailable. Single self-contained HTML file — no build, no backend.
