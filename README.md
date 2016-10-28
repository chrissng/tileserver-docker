# Tileserver-docker

Get a vector tile server up and running quickly with Singapore data and custom styling from Mapbox Studio

## Generate vector tiles from OSM

- Download the Singapore OSM extract from https://s3.amazonaws.com/metro-extracts.mapzen.com/singapore.osm.pbf
- Generate vector tiles using OSM2VectorTiles https://github.com/osm2vectortiles/osm2vectortiles/blob/master/USAGE.md
- Place generated MBTiles file in `export`

## Deploy

- `docker-compose -p ts up -d`

## Mapbox style specification URL (to be used in Mapbox GL JS)

- Dark style at http://localhost:8080/styles/dark.json
