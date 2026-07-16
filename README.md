# california-transit-housing-cuts-map


Interactive map of transit and housing projects to be cut by California Air Resources Board 

[[Vote by California regulators puts at risk billions in public transit and affordable housing funding.](https://www.seamlessbayarea.org/blog/2026/6/4/vote-by-california-regulators-puts-at-risk-billions-in-public-transit-and-affordable-housing-funding_)]

## Specifications
Here is an [example map](https://experience.arcgis.com/experience/1c8d389306234114b4db2e13e2b1ddf1) that we'd like to emulate, in some form.

Putting todo list and outline of required work in `TODO.md`

## Datasets

- TODO (Non-technical, can be done by anyone): Find specific geometries for each project to make it easier for the coders.
  - City boundaries
  - BART lines
  - Bus lines,
  - Transit agency boundaries, etc)
  - Can add to this list of datasets

### Geometries
- California County boundaries: [[GIS Dataset](https://gis.data.ca.gov/datasets/California::california-county-boundaries-and-identifiers/explore?location=38.119192%2C-122.153370%2C9)]
- California city and county boundaries: [[CaliforniaNature dataset](https://www.californianature.ca.gov/datasets/city-and-county-boundaries/explore?location=37.666379%2C-122.233851%2C9)]
- Transit route geometries: [[GIS Dataset](https://gis.data.ca.gov/datasets/dd7cb74665a14859a59b8c31d3bc5a3e_0/explore?location=37.337916%2C-121.163233%2C8)]

## Libraries
Useful TS libraries

### MapLibre
Rendering library for map components

https://maplibre.org/projects/gl-js/

### GeoJSON
Format for encoding geographic data structures

https://geojson.org/
