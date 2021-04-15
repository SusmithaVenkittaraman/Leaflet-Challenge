# Leaflet-Challenge

The first step in the project was to plot the earthquake data from the USGS. The geoJSON for the earthquakes in different regions is provided by the USGS in the link "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson". The data from the geoJSON is plotted on the map as one layer. The visualization has the toggle option which can help you chose the desired base map and the types offered as choices is a street map, dark map and a satellite map. The next step in the challenge was to plot another layer of data of tectonic plates and study if there is any relationship between tectonic plates and earthquakes. The data for tectonic plates is used from the link "https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_plates.json". The visualization also allows the user to select either the earthquakes or tectonic plates data at a time.

# Getting started

1. The index.html has the place for the map to get displayed with all the necessary links for libraries used.
2. Inside static the CSS folder has the different styles that has been used to visualize the map.
3. Please add you API key from the mapBox in config.js in static/js folder for the code to run successfully.
4. The logic.js under static/js folder have the code for both the steps(Earthquake data and tectonic plates data).
