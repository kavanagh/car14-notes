### Maps with leaflet and mapbox

1. Get data from Texas open data site. Add FIPS number

2. Open shapefile in qgis

3. For all of your columns tell qgis your relevant columns are strings then save as a csvt - save in same folder:

		eg. "String","String","String","String","String","String","String","Real","String","String","String"

4. Joins: Join shapefile and data on FIPS number. Now attribute table should show both

5. Save as geojson

**All session notes and example files can be found here:**
<https://github.com/brickaa/mapbox-leaflet-demo>

* Possible to style geojson files with leaflet, but it works really well with Mapbox
* example1.html
* On the command line, navigate to your folder
* One line of Python to show in browser
* example2.html - added styles and div for legend, set zoom level etc
* Add grid layers to show interactive elements
* example.html - added marker 


