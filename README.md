# trailmark-tiles

Public map-tile assets for the [Trailmark](https://github.com/johnsoncr34/trailmarkadv) iOS app.

These are **vector map tiles** (PMTiles / MVT) the app downloads on demand to render
its offline vector basemap — no backend, no API keys. Attached to GitHub **Releases**
(not committed to the repo).

## License / attribution

Tiles are derived from **OpenStreetMap** and are licensed **ODbL**.
**© OpenStreetMap contributors** — https://www.openstreetmap.org/copyright

Elevation-derived contours use public-domain terrain data (AWS Terrarium / USGS 3DEP).

## Layout

Each release (`v1`, `v2`, …) carries one or more per-state assets:

- `<state>.pmtiles` — vector basemap tiles (z0–15)
- `<state>-contours.pmtiles` — elevation contour lines (optional)
- `<state>.pack` — OSM routing graph for the app's snap-to-trail router (migrated
  off Apple On-Demand Resources so the ~2.3 GB stays out of the app archive)
