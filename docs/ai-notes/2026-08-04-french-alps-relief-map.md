# French Alps relief map

The Alps challenge uses one MapLibre GL JS map driven directly by `savoieData` in `index.html`. Search, completion filters, selected-col state, and the checklist all share that same 113-col dataset.

- OpenFreeMap provides the base style.
- Mapterhorn provides terrain and hillshade tiles.
- Map selection is deep-linked as `#col-ID`.
- The checklist remains the keyboard-accessible alternative to clicking canvas markers; each col name focuses that col on the map.
- If MapLibre, WebGL, or the remote style cannot initialize, the view falls back to the existing Leaflet/OpenTopoMap renderer.
- The Ligne Bleue challenge remains on Leaflet and was intentionally left unchanged.

When editing Alps records, update only `savoieData`; do not create a separate map-only col list.
