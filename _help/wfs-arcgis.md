---
title: CUGIR WFS from ArcGIS
tags:
  - Web Services
  - WFS
  - ArcGIS
status: draft
---
## Accessing CUGIR WFS (Web Feature Services) using ArcGIS
[ArcGIS](http://www.esri.com/arcgis/) is a Geospatial Information System from ESRI offering advanced capabilities, including the ability to import and display various web services such as [WFS](wfs.md) layers. Similar to [WMS](wms-arcgis.md), CUGIR WFS layers can be accessed within the ArcGIS desktop mapping application ArcMap. But before being able to do so, if not already done you will need to [install the Data Interoperability extension](http://desktop.arcgis.com/en/arcmap/latest/extensions/data-interoperability/installing-the-data-interoperability-extension.htm) then [add an Interoperability Connection](http://desktop.arcgis.com/en/arcmap/latest/map/working-with-arcmap/creating-an-interoperability-connection.htm) to CUGIRs WFS service (licensing the ESRI Data Interoperability extension is not required to enable this functionality). 

Adding CUGIR layers as new WFS Server connections within ArcCatalog (illustrated below) will make those available each time you create a new map in ArcMap.</br> 
<img align="center" src="images/ArcCatalog10.5_Add_WFS.png"></br>
First click/open the *Interoperability Connections* option in the Catalog Tree, then double click *Add Interoperability Connection*. From the dropdown Format menu, if needed select *More formats...*, WFS, and OK. The enter the CUGIR WFS server URL* in the *Dataset* field: http://cugir.library.cornell.edu/geoserver/cugir/wfs. Then click *Parameters...* from the Interoperability Connection dialogue box. 

In the *WFS Parameters* dialogue box, click the elipsis next to the *Feature Types* Constraints option. Check the boxes for layers desired from the *Select Feature Types*  dialogue box.</br>
<img align="center" src="images/ArcCatalog10.5_Add_WFS_Parameters.png"></br>
__PLEASE NOTE: do not *Select all* to make all CUGIR WFS layers available, as you will experience significant delays and performance issues when trying to add all these layers at once to ArcMap later.__ If your data layer(s) have many individual features (points, lines, polygons) you may need to also adjust the *Max Features* Constraint in order to display all of those in ArcMap. Click OK to close the dialogue box when done.</br>

You can now add these WFS layers to ArcMap (more details [here](http://desktop.arcgis.com/en/arcmap/latest/map/web-maps-and-services/adding-a-wfs-service-to-arcmap.htm)). Click the Add Data icon and select Interoperability Connections. Select the WFS layer(s) desired [note: you may need to (re)label those within ArcCatalog to make them more identifiable], then click Add. Unlike WMS, once displayed WFS layers can be converted into locally stored feature data sets (e.g. shapefiles). To do this, right click the layer from the Table of Contents and select *Data > Export Data*.</br>

*Though each data description page on the CUGIR web site provides a *Web Services* link within its respective Tools menu, the URL for accessing those is the same for all CUGIR WFS layers.
