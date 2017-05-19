% OpenStreetMap
% ![](http://www.openstreetmap.org/assets/osm_logo-bfdfd8749f46ea7c92950a82eeb425045cddfc0725e8281799d0efdde45c425d.svg)
% Simon Bilsky-Rollins


# Outline

* What is OpenStreetMap?
* What can you use OpenStreetMap for?
* Extracting data from OpenStreetMap
* Working with OpenStreetMap data
* Problems and limitations


# What is OpenStreetMap?

* A collaborative mapping platform
* A great source of open data


# What can you use OpenStreetMap for?

* Getting a free and open global dataset of geographic features
	* Points of interest, roads, buildings, parks, political borders, etc.
* Getting a free and open [basemap](http://www.openstreetmap.org/#map=15/44.4588/-93.1620) for web applications
	* One rule: <img src="http://www.openstreetmap.org/assets/attribution_example-937610fe671db6f42d3666d91fd7a1b1035d0df26066b890e4c007a314fc2da3.png" style="width: 193px; height: 69px;">
* Contributing to the collaborative mapping community!


# Extracting data from OpenStreetMap

Step 1: identify the specific map features you're interested in

* [OSM Wiki: master list of features](http://wiki.openstreetmap.org/wiki/Map_Features)
* [TagInfo: interactive feature database](https://taginfo.openstreetmap.org/)
* [TagFinder: search based on the TagInfo database](http://tagfinder.herokuapp.com/)


# Extracting data from OpenStreetMap

Step 2: identify the scope of your query (local, state, national, international)

* Small queries: [Overpass](http://overpass-turbo.eu/)*
* Large queries: [Osm2Shp](http://osm2shp.ru/)

\* Use Osm2Shp if you care about other attributes of the features you're extracting

[Sample Overpass query](http://overpass-turbo.eu/s/p8Y)


# Importing data into ArcGIS

* Points and polygons come in separate layers
* Be ready to deal with missing data!

# Problems and limitations

* OpenStreetMap contributors tend to come from wealthy Western countries, and the data reflects that
* Missing data
* Inconsistencies in feature tagging
