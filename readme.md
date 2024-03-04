# ASU Gym Route Map Project

## Introduction
The ASU Gym Route Map is an interactive web map. The map has a route from the Kidd Brewer Football Stadium to the Belk Library with five place markers at landmarks that are gyms in the app game Pokemon Go. 

## Major Functions
- Display a map of ASU campus with clear indication of buildings and walkways
- Display a route from the Kidd Brewer Football Stadium to the Belk Library with gyms and pokestops.
- Show locations of five gyms

## Libraries
This project uses the following libraries:
- [Leaflet](https://leafletjs.com/)
- [jQuery](https://jquery.com/)

## Data Sources
- Map Data: The map data is sourced from ArcGIS Online through the use of the Esri World Topographic Map tile layer.
-Route & Pokestop Data: This data is stored in a GeoJSON format and is loaded from a JavaScript file ('data/route.js').