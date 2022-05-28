# Mapping_Earthquakes

## Overview

The purpose of this project was to build insightful data visualizations with interactive features on earthquakes worldwide for the Disaster Reporting Network.  

Making earthquake maps informative and easy to use on desktop and mobile phones. For that purpose, by using the latest eartquick GeoJSON data from the “US Geological Survey Website” a website and a mobile application were developed.  Using the JavaScript and D3 and Leaflet libraries and plotting the data on a Mapbox map through API request, the earthquake data was traversed and retrieved. 

The magnitude and location of each earthquake were shown in the popup marker on the map. The diameter of the markers for each earthquake reflects the magnitude of the earthquake in their size and color. Earthquakes with high magnitudes appear larger and darker in color with legend providing the context of the map data. The relationship between the location and frequency of seismic activity and tectonic plates was illustrated with fault lines on the map. 	


## Result 

Using the JavaScript, Leaflet.js, and geoJSON data, the tectonic plate data was called by using the d3.json() method. The tectonic plate LineString data was added to the map by using the geoJSON() layer set and the chosen color and weight of the string lines made it stand out on the map. The tectonic plate data was added to the overlay object with the earthquake data.

When the python server was started and the “index.html” file launched, the following image was displayed. 

![Image_Deliverable_1.png](https://github.com/duygusimsek/Mapping_Earthquakes/blob/main/Images/Image_Deliverable_1.png)


Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, the major earthquake data was created and added to the map using the d3.json() method. Based on the magnitude of the earthquake, the color and the radius of the circle markers were set. Also, to display the magnitude and location of the earthquake,  popup markers for each earthquake were added to the map by using the GeoJSON layer, geoJSON(). 

All the earthquake data and tectonic plate data were displayed on the map when the page loads. 

![Image_Deliverable_2.png](https://github.com/duygusimsek/Mapping_Earthquakes/blob/main/Images/Image_Deliverable_2.png)


A third map style to the earthquake map was created and added by using JavaScript and Leaflet.js. When the python server was started and the “index.html” file was launched, with all the earthquake data and tectonic plate data the following image was displayed.

![Image_Deliverable_3.png](https://github.com/duygusimsek/Mapping_Earthquakes/blob/main/Images/Image_Deliverable_3.png)


## Sources

* Data Source: geoJSON 
* Software: [Visual Studio Code, 1.65.2](https://visualstudio.microsoft.com/downloads/)
* Language: JavaScript
* HTML, CSS


