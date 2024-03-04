# Mapping-Earthquakes
Use Leaflet.js API to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

## Completed Tasks:
Added Tectonic Plate data:
- As a second layer group and to the overlay object
- Used GeoJSON() layer to addscolor and width to the tectonic plate lines
- Data displays on the map when the page loads

Added Major Earthquake Data:
- As a third layer group and to the overlay object
- Used GeoJSON() to create a circle for each major earthquake, and add a popup to each circle to display magnitude and location of earthquakes

Displayed all the earthquake data and tectonic plate data on the map when page loads and datasets can be toggled on or off.
Added an additional map to tile layer and overlay object.
