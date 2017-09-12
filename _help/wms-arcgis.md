---
title: CUGIR WMS from ArcGIS
tags:
  - Web Services
  - WMS
  - ArcGIS
status: draft
---
## Accessing CUGIR WMS (Web Map Services) using ArcGIS
[ArcGIS](http://www.esri.com/arcgis/) is a Geospatial Information System offering advanced capabilities, including the ability to import and display various web services such as [WMS](wms.md) layers. CUGIR WMS layers can be accessed in ArcGIS a number of ways. Adding CUGIR as a new WMS Server connection within ArcCatalog (illustrated below) will make those available as accessible layers each time you create a new map in ArcMap. 
<img align="center" src="images/ArcCatalog10.5_Add_WMS.png"></br>
First double click the *Add WMS Server* icon in the Catalog Tree, then enter the CUGIR WMS server URL*: http://cugir.library.cornell.edu/geoserver/cugir/wms. Then click *Get Layers* to display all the WMS layers available from CUGIR (some downloadable data may be unavailable as a web service). Click OK to close the dialogue box. 

<img align="left" src="images/ArcMap10.5_Add_WMS.png">Now from within ArcMap, click the Add Data icon and select GIS Servers. Double click the *GeoServer Web Map Service on CUGIR* layer several times until you see a list of individual layers. Select the one(s) you would like to add to your map, then click Add. 

*NOTE: Though each data description page on the CUGIR web site provides a *Web Services* link within its respective Tools menu, the URL for accessing those is the same for all CUGIR WMS layers.
