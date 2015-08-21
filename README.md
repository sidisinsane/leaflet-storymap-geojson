# leaflet-storymap
creating a skeleton Leaflet storymap with slides that add new text, geojson, and tile layers

## Demo
http://jackdougherty.github.io/leaflet-storymap

Dependency:
- Leaflet-Omnivore (https://github.com/mapbox/leaflet-omnivore) stored in local directory to easily process many spatial data file types

```
var map = L.mapbox.map('map', 'mapbox.streets')
    .setView([38, -102.0], 5);

omnivore.csv('a.csv').addTo(map);
omnivore.gpx('a.gpx').addTo(map);
omnivore.kml('a.kml').addTo(map);
omnivore.wkt('a.wkt').addTo(map);
omnivore.topojson('a.topojson').addTo(map);
omnivore.geojson('a.geojson').addTo(map);
omnivore.polyline('a.txt').addTo(map);
```
Add custom styles to a geojson layer, which processes other types (eg kml)
```
var customLayer = L.geoJson(null, {
    // http://leafletjs.com/reference.html#geojson-style
    style: function(feature) {
        return { color: '#f00' };
    }
});
// this can be any kind of omnivore layer
var runLayer = omnivore.kml('line.kml', null, customLayer)
```

## Code credits
Adapted from
- http://maps.edbuild.org/DividingLines.html
- https://github.com/andrewbtran/dunkin_starbucks
- https://github.com/clhenrick/BushwickCommunityMap
