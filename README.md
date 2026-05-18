# 🌲 PNW Wild Explorer

**Interactive GIS web application exploring Pacific Northwest trails, wildlife habitat, salmon streams, and fish passage barriers.**

🔗 **Live Demo:** [https://YOUR_USERNAME.github.io/pnw-wild-explorer](https://YOUR_USERNAME.github.io/pnw-wild-explorer)

![PNW Wild Explorer](https://img.shields.io/badge/GIS-Leaflet.js-green) ![Data](https://img.shields.io/badge/Data-WDFW%20Open%20Data-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

---

## About

PNW Wild Explorer is a GIS portfolio project that combines overlanding/trail exploration with wildlife habitat and ecological data across Washington State. It features three interactive modes:

- **🗺️ Explore** — Interactive map with 6 toggleable data layers, multiple basemaps, and live WDFW data integration
- **📖 Story** — "Kerala to Cascades" narrative connecting two biodiversity hotspots through a personal journey
- **🔬 Compare** — Side-by-side ecosystem comparison between India's Western Ghats and Washington's Cascade Range

## Data Sources

| Layer | Source | Type |
|-------|--------|------|
| Trails & ORV Parks | WA RCO Trails Database, WA DNR | Curated points |
| Campsites | NPS, USFS, WA State Parks | Curated points |
| Salmon Streams | WDFW, NWIFC | Curated points |
| Fish Passage Barriers | [WDFW Fish Passage Inventory](https://geodataservices.wdfw.wa.gov/arcgis/rest/services/ApplicationServices/FP_Sites/MapServer) | Live ArcGIS REST API |
| Wildlife Sightings | WDFW PHS, eBird, iNaturalist | Curated points |
| Basemaps | OpenTopoMap, Esri World Imagery, OpenStreetMap | Tile layers |

## Tech Stack

- **Leaflet.js** — Interactive mapping library
- **WDFW ArcGIS REST API** — Live fish passage barrier data
- **Vanilla HTML/CSS/JS** — No build step required
- **GitHub Pages** — Static hosting

## Features

- 6 toggleable map layers with custom icons
- 3 basemap options (topographic, satellite, street)
- Live data fetch from WDFW ArcGIS REST API (fish passage barriers)
- Saved overlanding routes displayed as polylines
- Kerala-to-Cascades ecosystem comparison with detailed parallel analysis
- Quick-jump navigation to key PNW locations
- Responsive sidebar with collapsible panel
- Custom dark forest-themed UI

## Local Development

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/pnw-wild-explorer.git
cd pnw-wild-explorer

# Open in browser (no build step needed)
open index.html
# or use a local server:
python3 -m http.server 8000
```

## Deployment

This site is deployed to GitHub Pages. To deploy your own:

1. Fork this repository
2. Go to Settings → Pages
3. Set source to "Deploy from a branch" → `main` → `/ (root)`
4. Your site will be live at `https://YOUR_USERNAME.github.io/pnw-wild-explorer`

## Future Enhancements

- [ ] GPX file upload and display (import from OnX Offroad / GAIA GPS)
- [ ] PostGIS backend for spatial queries
- [ ] Satellite imagery overlays (USGS/NASA) for forest health
- [ ] User accounts and trip logging with persistent storage
- [ ] Mobile-optimized field data collection mode
- [ ] Integration with iNaturalist API for live wildlife observations
- [ ] GISP certification portfolio documentation

## About the Author

Built by **Ram** — Engineering Manager transitioning from corporate tech (Amazon) to GIS and environmental science. Currently pursuing an M.S. in Geography & Geospatial Science at Oregon State University.

This project demonstrates the intersection of data engineering skills and geospatial analysis for conservation and natural resource management.

## License

MIT License — see [LICENSE](LICENSE) for details.
