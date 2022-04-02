# 13_Mapping_Earthquakes_Challenge
Challenge for Module 13 Mapping Earthquakes with JS and APIs

For this challenge we were asked to modify the Earthquake map with three deliverables

### Deliverable 1 - Add Tectonic Plate Data

- [x] The tectonic plate data is added as a second layer group 
- [x] The tectonic plate data is added to the overlay object 
- [x] The `d3.json()` callback is working and does the following: 
  - [x] The tectonic plate data is passed to the `geoJSON()` layer
  - [x] The `geoJSON() `layer adds color and width to the tectonic plate lines
  - [x] The tectonic layer group variable is added to the map (label `Tectonic Plates` )
- [x] The earthquake data and tectonic plate data displayed on the map when the page loads

### Deliverable 2 - Add Major Earthquake Data

- [x] The major earthquake data is added as a third layer group 
- [x] The major earthquake data is added to the overlay object 
- [x] The `d3.json()` callback is working and does the following: 
  - [x] Sets the color and diameter of each earthquake. 
  - [x] The major earthquake data is passed to the `geoJSON()` layer.
  - [x] The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
  - [x] The major earthquake layer group variable is added to the map
- [x] All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off 

### Deliverable 3 - Add an Additional Map
- [x] A third map tile layer is created - new map tile layer titled `Night Navigation`
- [x] The third map is added to the overlay object 
- [x] All the earthquake data and tectonic plate data are displayed on the all maps of the webpage 
