# leaflet-storymap-geojson
Goal: a Leaflet story map template that also displays geojson and tile layers on indiv slides

## Demo
http://jackdougherty.github.io/leaflet-storymap-geojson

## To Do
- Improve interface to resemble my other storymap template (which currently cannot easily display geojson objects that change with each slide) http://github.com/jackdougherty/leaflet-storymap-odyssey
  - in custom.css: FIX: when narrower than 300px, auto-scroll horizontal for wide text
- Find Leaflet substitute for L.mapbox.featurelayer (and MapBox account token), which is currently required to display geoJson internal styling (for history town lines map story); look through https://github.com/mapbox/mapbox.js
- perhaps try creating a geojson with internal styling as a .js with declared variable?
- make geojson feature layer clickable
- set up with standard options for MAGIC 1934 and present day tile layers
- Possible to display multiple spatial layers on same slide (e.g. a geoJson and a tile layer)? If not, would need to create add them on two consecutive slides and perhaps skip forward to second slide.
- Possible to add flyTo feature in Leaflet 1.0 beta? https://groups.google.com/forum/#!msg/leaflet-js/-okp0IPm1mg/SzYsMLX5pa4J

## Credits
A great deal of this code is adapted from the creative folks at EdBuild.org:
- http://maps.edbuild.org/DividingLines.html

### with additional ideas from:
- https://github.com/andrewbtran/dunkin_starbucks -- see https://www.bostonglobe.com/business/2014/08/25/dunkin-expands-into-california-market-dominated-starbucks/Q1cdxOhAVlOXsJXWuF5F6H/igraphic.html
- http://github.com/CartoDB/Odyssey.js
- https://github.com/clhenrick/BushwickCommunityMap
