# leaflet-map-story
creating a Leaflet storymap template with slides to add text, geojson, and tile layers

## Demo
http://jackdougherty.github.io/leaflet-map-story

## To Do
- Find Leaflet substitute for L.mapbox.featurelayer (and MapBox account token), which is currently required to display geoJson internal styling (for history town lines map story); look through https://github.com/mapbox/mapbox.js
- perhaps try creating a geojson with internal styling as a .js with declared variable?
- set up with standard options for MAGIC 1934 and present day tile layers
- set up option for flickr photo layer if desired
- Display "Back" and "Next" buttons as CSS, and place at bottom of sidebar, for easier and more consistent user interface; compare with Andrew's Dunkin Donuts model
- add round button on top of slide title to show number of slides and allow clickable (see Odyssey.js)
- Variation: replace full sidebar with a floating info-box, ideally with automatic length adjustment, and place in bottom-right corner; test across different devices
- Possible to display multiple spatial layers on same slide (e.g. a geoJson and a tile layer)? If not, would need to create add them on two consecutive slides and perhaps skip forward to second slide.
- Possible to add flyTo feature in Leaflet 1.0 beta? https://groups.google.com/forum/#!msg/leaflet-js/-okp0IPm1mg/SzYsMLX5pa4J


## Code credits
A great deal of this code is adapted from the creative folks at EdBuild.org:
- http://maps.edbuild.org/DividingLines.html

### Additional ideas from:
- https://github.com/andrewbtran/dunkin_starbucks -- see https://www.bostonglobe.com/business/2014/08/25/dunkin-expands-into-california-market-dominated-starbucks/Q1cdxOhAVlOXsJXWuF5F6H/igraphic.html
- http://github.com/CartoDB/Odyssey.js
- https://github.com/clhenrick/BushwickCommunityMap
