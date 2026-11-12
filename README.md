# drop ski data

Ski areas, runs, lifts and terrain heightmaps used by the drop app. Built with `tools/skidata/build.py` in the app repository.

- `index.json`: every downhill ski area in the world, with bounding box and stats.
- `areas/<id>.json`: runs and lifts of one ski area.
- `terrain/<id>.u16.gz`: terrain heightmap of one ski area (gzip of little-endian uint16, see the `terrain` field of the area file).

## Licence and credits

Ski areas, runs and lifts: © OpenStreetMap contributors, processed by [OpenSkiMap](https://openskimap.org). This database is made available under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).

Terrain: [Terrain Tiles](https://registry.opendata.aws/terrain-tiles/) on AWS Open Data (Mapzen), from SRTM, EU-DEM and other sources.
