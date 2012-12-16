Primary Colors
==============

The following code displays Israeli local government transparency scores as collected by [Shvil](http://www.ti-israel.org/).

The working application can be viewed at: http://niryariv.github.com/primary_colors/

The main rendering code is in /index.html and uses [Leaflet.js](http://leafletjs.com/) for mapping.

Data is stored in JSON format, accessible under https://github.com/niryariv/primary_colors/tree/master/data and organized in the following files:

* data/index.js: Index of all the local authorities by ID, including Hebrew name, centeral coordinates and overall transparency score
* data/attrs.js: Detailed results of various transparency parameteres, in key/value pair indexed by authority ID
* data/coords.js: Coordinates for each authority's boundary lines, indexed by authority ID (TODO: export to GeoJSON)