---
published: true
title: Now EXPORT from CAD to Google Earth, Shapefiles, etc.
date: 2015-03-15T11:30:58+00:00
author: admin
layout: old-post
permalink: /now-export-from-cad-to-google-earth-shapefiles-etc/
image: /images/blog/2015/03/SPM-Export-85.png
categories:
  - Announcement
  - CAD L1 (Basic)
tags:
  - Edition
  - Export
---
The new &#8216;Professional&#8217; Edition of Spatial Manager™ for AutoCAD and Spatial Manager™ for BricsCAD adds the expected functionality of Export from basic AutoCAD or BricsCAD to geo-spatial files or databases<!--more-->

## What is new in the &#8216;Professional&#8217; edition (AutoCAD/BricsCAD)

Basically the new edition adds to the existing editions (Basic and Standard), and their importing functionality, **the possibility of exporting from AutoCAD or BricsCAD drawings** to Google Earth (KML or KMZ), Shapefiles (SHP), Points (many formats), MapInfo, PostGIS, SQL Server, SQLite, and many more geospatial targets (<a title="Spatial Manager Data Providers" href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Providers" target="_blank" rel="nofollow">see here the full data provider list</a>)

The new function exports objects **from the drawing to spatial files or databases**, and saves their Extended Entity Data (EED/XDATA) as data tables using a wizard, which shares some of the steps with the import wizard. In the same way, the user can choose or select the export parameters to define all the target data among a large number of possibilities

There are options for filtering the objects when exporting, and all the geometric operations required to fit the target data format are automatically performed

Moreover this edition adds **more possibilities of manipulating databases directly from the application**, such as creating new schemas or tables, deleting or renaming schemas and tables, etc.

<a href="/images/blog/2015/03/Now-EXPORT-from-CAD-to-Google-Earth-Shapefiles-etc..png" target="_blank" rel="nofollow"><img src="/images/blog/2015/03/Now-EXPORT-from-CAD-to-Google-Earth-Shapefiles-etc..png" alt="Now EXPORT from CAD to Google Earth, Shapefiles, etc." width="625" height="434" srcset="/images/blog/2015/03/Now-EXPORT-from-CAD-to-Google-Earth-Shapefiles-etc..png 950w, /images/blog/2015/03/Now-EXPORT-from-CAD-to-Google-Earth-Shapefiles-etc.-300x208.png 300w, /images/blog/2015/03/Now-EXPORT-from-CAD-to-Google-Earth-Shapefiles-etc.-624x432.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a>

_Click on the image to expand it and review some new functions on this edition_

## Transformation of coordinates

The application will calculate geometric transformations of the objects in line with the export processes, which will depend on the chosen Coordinate System (CRS) for the source (drawing) and target data

As in the import processes, the user can choose the appropriate CRSs from a complete CRS catalog or from a list which includes the most recent used CRSs

## Data providers

The application uses its own data providers in the export processes (as in the import processes) and offers the user a wide range of settings to fit the best configuration for the outgoing data

<p>
  <a href="/images/blog/2015/03/Export-from-DWG-to-KML.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/03/Export-from-DWG-to-KML.png" alt="Export from DWG to KML" width="567" height="574" srcset="/images/blog/2015/03/Export-from-DWG-to-KML.png 567w, /images/blog/2015/03/Export-from-DWG-to-KML-296x300.png 296w" sizes="(max-width: 567px) 100vw, 567px" /></a>
</p>

_Sample: Google Earth KML/KMZ data provider outgoing parameters_

## Export function features

**· Select the objects to be exported:** choose between exporting the selected objects, the objects in a layer or the whole drawing
  
**· Automatic complex geometric operations:** review and editing of the selected objects in order to export geometries accommodated to the target format, such as the polygonal segmentation on curves if required
  
**· Option to treat the closed polylines as polygons:** most of the time the closed polylines represent polygonal elements on the target data format and this conversion can be automatic
  
**· Filtering of incompatible objects:** there are a few object types not supported by the export processes (such as complex 3D objects), which are automatically filtered. The filter result is displayed before exporting

## Some Export function video samples:

**· Directly to Google Earth (KML) from your drawing**
  
** AutoCAD: <a href="http://youtu.be/d61V8wQLYaI?rel=0" target="_blank" rel="nofollow">Video 1</a>
  
** BricsCAD: <a href="http://youtu.be/MCsdcmdNo1M?rel=0" target="_blank" rel="nofollow">Video 1</a>
  
**· Coordinates to Excel from your drawing
  
** ** AutoCAD: <a href="http://youtu.be/a8a-XZKxcXU?rel=0" target="_blank" rel="nofollow">Video 2</a>
  
** BricsCAD: <a href="http://youtu.be/O6PoducEeKA?rel=0" target="_blank" rel="nofollow">Video 2</a>
  
**· Import a Shapefile and export it as 3D Google Earth
  
** ** AutoCAD: <a href="http://youtu.be/DAGgwmAtoPg?rel=0" target="_blank" rel="nofollow">Video 3</a>
  
** BricsCAD: <a href="http://youtu.be/KpJqHzl5WOM?rel=0" target="_blank" rel="nofollow">Video 3</a>
  
**· OpenStreetMap data. Edit and export to Google Earth
  
** ** AutoCAD: <a href="http://youtu.be/VEFhEfN8LZw?rel=0" target="_blank" rel="nofollow">Video 4</a>
  
** BricsCAD: <a href="http://youtu.be/n-NN2X9Ix7k?rel=0" target="_blank" rel="nofollow">Video 4</a>
  
**· Import a Shapefile. Edit & export as Shapefile
  
** ** AutoCAD: <a href="http://youtu.be/4o8w3V3UY1w?rel=0" target="_blank" rel="nofollow">Video 5</a>
  
** BricsCAD: <a href="http://youtu.be/2Sj_fkYJaMs?rel=0" target="_blank" rel="nofollow">Video 5</a>

### Related links:

**· Product pages:** <a title="Spatial Manager for AutoCAD product page" href="/spm-forautocad/" target="_blank" rel="nofollow">AutoCAD</a> / <a title="Spatial Manager for BricsCAD product page" href="/spm-forbricscad/" target="_blank" rel="nofollow">BricsCAD</a>**
  
** **· Download:** <a title="Spatial Manager for AutoCAD Download" href="/download/spatial-manager-autocad/" target="_blank" rel="nofollow">AutoCAD</a> / <a title="Spatial Manager for BricsCAD Download" href="/download/spatial-manager-bricscad/" target="_blank" rel="nofollow">BricsCAD</a>
  
**· Prices and editions:** <a title="Spatial Manager for AutoCAD prices page" href="/spm-forautocad-prices/" target="_blank" rel="nofollow">AutoCAD</a> / <a title="Spatial Manager for BricsCAD prices page" href="/spm-forbricscad-prices/" target="_blank" rel="nofollow">BricsCAD</a>
  
**· Technical Wiki:** <a title="Spatial Manager for AutoCAD Wiki Introduction" href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD" target="_blank" rel="nofollow">AutoCAD</a> / <a title="Spatial Manager for BricsCAD Wiki Introduction" href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD" target="_blank" rel="nofollow">BricsCAD</a>
  
**· Contact Information**
  
** Web: <a title="Spatial Manager Web" href="/" target="_blank" rel="nofollow">/<br /> </a>** LinkedIn: <a title="Spatial Manager on LinkedIn" href="https://www.linkedin.com/company/5386123" target="_blank" rel="nofollow">https://www.linkedin.com/company/5386123</a>
  
** Twitter: <a title="Spatial Manager on Twitter" href="http://twitter.com/SpatialManager" target="_blank" rel="nofollow">http://twitter.com/SpatialManager</a>
  
** Facebook: <a title="Spatial Manager on Facebook" href="http://www.facebook.com/SpatialManager" target="_blank" rel="nofollow">http://www.facebook.com/SpatialManager</a>
  
** YouTube channel: <a title="Spatial Manager YouTube channel" href="http://www.youtube.com/user/SpatialManager" target="_blank" rel="nofollow">http://www.youtube.com/user/SpatialManager</a>
  
** Wiki: <a title="Spatial Manager Wiki" href="http://wiki.spatialmanager.com/index.php/Main_Page" target="_blank" rel="nofollow">http://wiki.spatialmanager.com/index.php/Main_Page</a>
  
** Email addresses:
  
&#8211; Issues regarding technical questions, feedback and input: <a title="Spatial Manager Support" href="mailto:support@spatialmanager.com" target="_blank" rel="nofollow">support@spatialmanager.com</a>
  
&#8211; Issues regarding commercial and other questions: <a title="Spatial Manager Info" href="mailto:info@spatialmanager.com" target="_blank" rel="nofollow">info@spatialmanager.com</a>