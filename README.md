# Mapping Earthquakes:<br /> Interactive Map and Visualization of GeoJSON earthquake data
## Project Overview
### Purpose
This project uses Leaflet.js, a library in JavaScript, to create an interactive map visualizing the 7-day earthquake data around the world which is retrieved from the U.S. Geological Survey website in a GeoJSON format. The visualization of the earthquake includes magnitude-based circle and color markers representing different earthquakes, popup markers, tectonic plates, as well as three map styles via Mapbox API.

### Resources
+ **Languages:** JavaScript, HTML, CSS
+ **Library:** Leaflet.js
+ **Editor Tool:** Visual Studio Code
+ **API:** Mapbox API
+ **Database:** [USGS URL for earthquake data (7 days)](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
+ **Scripts:** [Earthquake_Challenge](https://github.com/asama-w/Mapping_Earthquakes/tree/main/Earthquake_Challenge)
	+ [index.html](https://github.com/asama-w/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html) 
	+ [challenge_logic.js](https://github.com/asama-w/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js)
	+ [style.css](https://github.com/asama-w/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css)

## Interactive Map Overview
+ The popup marker shows each earthquake's magnitude and location appears when clicked on its circle.
+ The diamater and color of the earthquake's circle represents the degree of its magnitude, from small to large, and green to red (low to high magnitude).
+ The interactive map has three different layers which can be chosen on the top-right corner of the map:
  + **Earthquakes:** shows all earthquakes that happened around the world for the past 7 days.
  + **Tectonic Plates:** shows the tectonic plates.
  + **Major Earthquakes:** shows only earthquakes whose magnitudes are higher than 4.5 Richter for the past 7 days.
The following images show an interactive map before and after the tectonic plates and major earthquake options have been applied

#### Interactive Map when only Earthquakes layer is applied
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/streets-1.png width="80%" height="80%">

#### Interactive Map when Earthquakes and Tectonic Plates layers are applied
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/streets-2.png width="80%" height="80%">

#### Interactive Map when all three layers are applied
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/streets-3.png width="80%" height="80%">

#### Interactive Map when only Tectonic Plates and Major Earthquakes layers are applied
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/major-tectonic-streets.png width="80%" height="80%">



### Map Styles
The interactive map has three styles: Streets, Satellite, Dark, as shown in the following images.

#### Streets Mode
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/streets.png width="80%" height="80%">

#### Satellite Mode
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/satellite.png width="80%" height="80%">

#### Dark Mode
<img src= https://github.com/asama-w/Mapping_Earthquakes/blob/main/Additional_images/dark.png width="80%" height="80%">

