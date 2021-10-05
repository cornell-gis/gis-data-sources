Compiled by Keith Jenkins <kgj2@cornell.edu>, GIS Librarian at Mann Library.

 
# New York State

## NYS GIS Clearinghouse
<http://gis.ny.gov/>  
Includes geospatial data created by state, county, and local governments across New York.  (Some datasets require login -- contact kgj2@cornell.edu for access.)

## Data.ny.gov
<https://data.ny.gov/>  
New York's main site for open government data.  When searching the site, trying limiting the results to "Maps" (under "view types" on the left), which will limit the results to geospatial datasets that can be directly used with GIS software.  When downloading a dataset, click the "Export" button and look for a "shapefile", "KML", "GeoJSON", or other GIS data format.  For many point datasets, you'll need to download as CSV, which is a tabular format that contains longitude and latitude coordinates.  Most of the other datasets on the site will be non-spatial tabular datasets (spreadsheets), but some of these datasets contain placenames or standard identifiers that can be used to join the data to GIS polygon layers (for example, county-based statistics).

## CUGIR
<https://cugir.library.cornell.edu/>  
The Cornell University Geospatial Information Repository.  Includes New York data from a variety of federal, state, and local government sources, as well as Cornell research projects.

## Discover GIS Data NY
<https://orthos.dhses.ny.gov/>  
Provides access to elevation data from a variety of statewide and local sources, LiDAR pointcloud data from various surveys, and aerial imagery for specific years (1990s to the present) from the NYS statewide orthoimagery program.  To get to the previews and downloads, see the "tools" icon in the top right of the map.

For the aerial imagery, it is also possible to link to a web service rather than downloading specific image tiles.  In QGIS, open the Data Source Manager > WMS/WMTS > New, then enter a name and the following URL:  
https://orthos.its.ny.gov/ArcGIS/services/wms/Latest/MapServer/WMSServer

Then click "Connect" and select a layer to add.  For more details, including access to older imagery, see the NYS Orthoimagery Web Services webpage at <http://gis.ny.gov/gateway/mg/webserv/webserv.html>

## Historical Aerial Photographs of New York
<https://digital.library.cornell.edu/collections/aerialny>  
Aerial photos dating back to 1936.  Only Cayuga, Cortland, Onondaga, Seneca, Tompkins, and Wayne counties are currently available online, but Cornell IRIS is in the middle of a project to scan the original photographs for other counties across NY.

----

# United States

## Census TIGER/Line Shapefiles
<https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html>  
Spatial data for boundaries of legal and statistical areas such as states, counties, census tracts, block-groups, blocks, zipcode tabulation areas, legislative boundaries, school districts, etc.  (Also includes roads and water features, although probably not as detailed or current as other sources.)

Demographic data can be downloaded from:
* [data.census.gov](https://data.census.gov/) (official source)
* [censusreporter.org](https://censusreporter.org/) (latest American Community Survey only)
* [nhgis.org](https://www.nhgis.org/) (historical data back to 1790)

## SimplyAnalytics
<http://resolver.library.cornell.edu/misc/6168667>  
Formerly known as SimplyMap, this is a website that the Cornell Library subscribes to.  It offers thematic maps and reports of demographic, business, and marketing data for the United States.  Some of the marketing data is incredibly specific, such as "# Households buying car wax and polish in last 12 months" or "% Households engaged in marathon/triathon training and events".  To export shapefiles of the data, click the ☰ menu.

## The National Map
<https://apps.nationalmap.gov/downloader/#/>  
Download a variety of data layers for any arbitrary region.  Includes NED (National Elevation Dataset),  NHD (National Hydrography Dataset), orthoimagery, and more.

## National Land Cover Database
<https://www.mrlc.gov/data>  
The Multi-Resolution Land Characteristics Consortium publishes the National Land Cover Database (NLCD), a 30-meter-resolution raster dataset of the United States that includes landcover, tree canopy, urban imperviousness, and more.

## U.S. Interagency Elevation Inventory
<https://coast.noaa.gov/inventory/>  
Catalog of high-resolution elevation surveys across the US, with links to data download sites where available.

----

# International

## Natural Earth
<https://www.naturalearthdata.com/>  
Public domain map data at 1:10m, 1:50m, and 1:110 million scales for global or regional maps.

## geoBoundaries
<https://www.geoboundaries.org/>  
Global database of political administrative boundaries (state and county equivalents for each country, and sometimes even smaller units), produced by the College of William & Mary and shared under an open license.

## GADM
<https://gadm.org/download_country_v3.html>  
Global administrative boundaries, often down to the 3rd or 4th level for each country.

## OpenStreetMap (OSM)
<https://www.openstreetmap.org/>  
A free, collaborative, editable map of the world.  The current map can be viewed at the link above -- check your area of interest to see what level of detail is available.  To download as data, click “Export” for various options, or go directly to these sites for easy-to-use shapefiles:
  * <http://download.geofabrik.de/>	(daily data extracts by country)
  * <https://export.hotosm.org/>	(custom extracts by user-selected area)

**QuickOSM** is a QGIS plugin that allows you to search an area for specific OSM tags and import the data directly into QGIS.  It works well for city-sized areas, but will time out if the search result data is too large (in which case it is better to use the Geofabrik site above).  For help finding the right OSM tags, see "Map Features" on the OSM wiki: <https://wiki.openstreetmap.org/wiki/Map_features>

----

# Finding other data sources

## [Geolode.org](http://geolode.org/)
Geolode is a worldwide catalog of over 800 open geospatial data websites, including all the major US state GIS websites.  This project started at Cornell, and is maintained by GIS librarians at several universities.

## Google, etc.
When searching the web, try using a country/province/city name and terms like "GIS data", "shp", "shapefile", etc.  Try variants using the local language, like `Colombia SIG datos`.  Local governments and NGOs may share geospatial data, although availability varies from place to place.  Even if data is not readily downloadable from an organization's website, it might be possible to find a contact name and e-mail address.  When making a request by e-mail, be explicit about what data you are looking for, and be sure to mention that you will be using the data for an academic course project.

