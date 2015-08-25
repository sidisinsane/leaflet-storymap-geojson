# leaflet-map-story
creating a Leaflet storymap template with slides to add text, geojson, and tile layers

## Demo
http://jackdougherty.github.io/leaflet-map-story

## To Do
- Use new method to replace L.mapbox.featurelayer (and MapBox account token) with L.geoJson and global controlLayers variable
- Remove Leaflet-Omnivore
- Display "Back" and "Next" buttons as CSS, and place at bottom of sidebar, for easier and more consistent user interface; compare with Andrew's Dunkin Donuts model
- add round button on top of slide title to show number of slides and allow clickable (see Odyssey.js)
- Variation: replace full sidebar with a floating info-box, ideally with automatic length adjustment, and place in bottom-right corner; test across different devices
- Possible to display multiple spatial layers on same slide (e.g. a geoJson and a tile layer)? If not, would need to create add them on two consecutive slides and perhaps skip forward to second slide.


## Code credits
A great deal of this code is adapted from the creative folks at EdBuild.org:
- http://maps.edbuild.org/DividingLines.html

### Additional ideas from:
- https://github.com/andrewbtran/dunkin_starbucks -- see https://www.bostonglobe.com/business/2014/08/25/dunkin-expands-into-california-market-dominated-starbucks/Q1cdxOhAVlOXsJXWuF5F6H/igraphic.html
- http://github.com/CartoDB/Odyssey.js
- https://github.com/clhenrick/BushwickCommunityMap
