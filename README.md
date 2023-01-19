# GeospatialAnalysisProject

## Geospatial Analysis of the Districts of Bulgaria, the Climate in each, and the City of Plovdiv.

A project for the course of Geospatial Analysis and Representation at the University of Trento, academic year 2022/2023.

The project is organized as follows.

The file **GeospatialAnalysisReport.pdf** is a brief summary paper of the analysis and results obtained, with visualizations of maps and diagrams.

In the **Analysis and Exploration** folder is the material about the analysis of climate variables and the one of the city of Plovdiv with Python, containing the /code and /data folders. 

Data is subdivided into the different sources used for different purposes.
- Sentinel 2 are data from the ESA's Copernicus mission (Contains modified Copernicus Sentinel data [2022]).
- DTM are data from Shuttle Radar Topography Mission (SRTM) - U.S. Geological Survey. EarthExplorer https://earthexplorer.usgs.gov/ . Visit the USGS at https://usgs.gov.
- OSM_BBBike has inside the prorocolbuffer file for Plovdiv
- Bulgaria_gdf contains geojson and shapefiles of Bulgaria
- CLimate has some modified WorldCLim data (Under Creative Commons Attribution-ShareAlike 4.0 International License) https://worldclim.org/data/worldclim21.html
- Hydrobasins comes from AQUASTAT (FAO) (under Creative Commons Attribution-NonCommercial-ShareAlike 3.0 IGO) https://data.apps.fao.org/catalog/iso/1849e279-67bd-4e6f-a789-9918925a11a1 

Code contains the executable notebooks representing all the analysis, divided by the function.

In the **Spatial Regression** folder, there is the file with statistical indicators of Bulgaria with data from the National Statistical Institute. The .rmd file instead contains the R analysis of the districts.
