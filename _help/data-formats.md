---
title: CUGIR Data Formats
tags:
  - data format
category: Help
status: draft
---

# CUGIR Data Formats
CUGIR [data packages](https://github.com/cul-it/cugir-help/blob/master/_help/CUGIR_data.md) contain spatial data files in the following formats. Most require specialized software in order to use/view, including GIS (Geographic Information Systems) software. [This Wikipedia page](https://en.wikipedia.org/wiki/List_of_geographic_information_systems_software) lists several GIS applications, some which are free. [This Wikipedia page](https://en.wikipedia.org/wiki/Comparison_of_geographic_information_systems_software) provides a useful comparison of several applications, including the formats they are able to work with.

## .dwg Computer Aided Design (CAD) ##
CUGIR offers a small number of data files (e.g. municipal tax parcel datasets for Tompkins County) in computer-aided design (CAD) format for use in AutoCAD and other compatible software (including some GIS programs).

## .geojson GeoJSON ##
[GeoJSON](https://en.wikipedia.org/wiki/GeoJSON) is an open standard format designed for representing simple geographical features (points, lines and polygons), along with their non-spatial attributes. It is supported by numerous mapping and GIS software applications.

## .kmz Keyhole Markup language Zipped ##
KMZ files are zipped/compressed KML files with a .kmz extension. [KML](https://en.wikipedia.org/wiki/Keyhole_Markup_Language) is a file format used to display geographic data in applications such as Google Earth, as well as some GIS software. KML uses a tag-based structure with nested elements and attributes and is based on the XML standard.

## .pdf PDF ##
Electronic versions of some technical documentation and data are posted in CUGIR in Adobe's Portable Document Format (PDF). PDF files maintain the format and look of print documents and are easily accessible to people using various computer platforms. PDF documents require the Adobe Acrobat Reader or similar application for viewing and printing.

## .shp Shapefile ##
A proprietary ESRI format commonly used for storing vector data, including geographic features and their attributes. Compatible with ArcView, ArcExplorer, ArcInfo or ArcGIS, this format can also be used and/or converted by most popular GIS software applications. In CUGIR, shapefiles have been packaged and compressed. When decompressed, shapefiles contain three or more necessary files to complete a data set, each with the same name but different extension file types. These files must be kept together in the same subdirectory. All are necessary parts of the data theme when used with GIS software. In some cases projection information may be included in an accessory .prj file that allows GIS software to properly draw and place the data layer. If this file is missing users will need to "define " the projection before importing into a GIS.

## .tif TIFF or GeoTIFF ##
TIFF is an image format which may or may not have georeferencing information associated with it. GeoTIFF is a TIFF format with additional georeferencing information included in the header of each file and/or in an accessory tiff world file (.tfw). This information allows the map images to be properly drawn within GIS software.

The Digital Raster Graphic (DRG) topographic map images in CUGIR are in GeoTIFF format. These are useful for locating and identifying landscape features and landmarks, and as base layers in mapping projects. Originally published by the USGS by 7.5-minute quadrangle map, CUGIR DRGs are edited and updated by the NYS DEC. Map collars and legends found on print versions which these are derived from have been removed. In some cases areas outside New York state may be cropped out as well. 

## Web Services (WMS & WFS) ##
CUGIR also provides direct online access to select data sets via "web services", [Web Map Services (WMS)](wms.md) and [Web Feature Services (WFS)](wfs.md). Those pages provide details about those and how to access them.

## .zip Zip File ##
CUGIR files are [packaged](https://github.com/cul-it/cugir-help/blob/master/_help/CUGIR_data.md) and compressed into .zip formt to reduce file size and download time. Zip files need to be uncompressed before they can be viewed or imported into a GIS. You will need a file archiver application to do that. If your computer does not already have one installed [this Wikipedia page](https://en.wikipedia.org/wiki/Comparison_of_file_archivers) lists several, including a number of free ones.

