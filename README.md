# leaflet-storymap
a Leaflet storymap template with slides that add text, geojson, and tile layers

## Demo
http://jackdougherty.github.io/leaflet-storymap

## To Do
- Currently requires L.mapbox.featurelayer (and MapBox account token) to display geojson, even when these files are stored on local directory
- Try to replace with L.geoJson or Leaflet-Omnivore (https://github.com/mapbox/leaflet-omnivore), which can process many types of spatial data (geojson, kml, polyline, etc.)
- Try to rewrite code to display multiple spatial layers on same slide (e.g. a geoJson and a tile layer)
- Future option: try to rewrite code to display a floating infobox, rather than full sidebar, and change placement

## Code credits
Adapted from and inspired by
- http://maps.edbuild.org/DividingLines.html
- https://github.com/andrewbtran/dunkin_starbucks
- http://github.com/CartoDB/Odyssey.js
- https://github.com/clhenrick/BushwickCommunityMap
