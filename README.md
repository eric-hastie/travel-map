# Travel Map

An interactive map reconstructing a decade of U.S. travel — six major road trips plus overall travel coverage.

**Live map:** https://eric-hastie.github.io/travel-map/

## How it was built

- **iPhone photo GPS metadata** — EXIF coordinates from ~22,000 photos, clustered into places and rendered as a heatmap
- **A 180,000-message text archive** — place mentions from 2011–2015, before the photo record starts
- **Landmark photos sequenced by frame number** where timestamps were unreliable
- **OSRM** for snapping raw points to real road geometry
- **Leaflet** for rendering; single self-contained HTML file, no build step

## Map controls

- **Arrow spacing** — how often direction arrows are drawn along each route (25–500 mi)
- **Mile markers** — distance-into-trip labels every 200 mi
- **Start/end** — START and END badges at each trip's endpoints
- **Layers panel** (top right) — basemap choice, state lines, heatmap, place layers, and each trip individually

## Trips

| Trip | Year | Distance |
| --- | --- | --- |
| Zion loop | 2020 | 1,714 mi |
| COVID cross-country | 2020 | 9,776 mi |
| Maryland → Washington | 2020 | 2,775 mi |
| Seattle → Austin move | 2024 | 5,239 mi |
| New Orleans → California | 2013 | 3,682 mi |
| Utah · Thanksgiving | 2019 | 2,390 mi |
