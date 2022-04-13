# Mapping-Buildings-in-3D
In this project, I have shown how any under construction site can be visualized in 3d and can also be extruded floor and concept wise. This project involved QGIS for creating GeoJSON data of buildings, Geoserver for publishing of data and Cesium mapping library for fetching published data and extruding it on the fly and visualizing it in a real time scenario using different base maps
### Technologies Used
•	QGIS
•	Geoserver
•	Cesium Mappin Library

### Import all the necessary CSS files and JS files to your main file (index.html)
#### In this project, I have used a local server (Wampserver64) to fetch files from it and then imported them into my main file.
##### Files to be imported are (can be downloaded from the repository) –
•	Cesium.js
•	Sandcastle-header.js
•	CesiumSandcastle.css
•	bucket.css

### Follow the comments in the main code for an explanation
GEOJSON files have to be hosted on geoserver and then has to be imported into the code.
“http://localhost:8081/geoserver/yourworkspacename/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=Teknobuilt%3ABuildings2&outputFormat=application%2Fjson"

## Follow the code for all the other functionalities


