---
id: 4284
title: How to import shapefiles into ZWCAD
date: 2017-10-07T19:46:45+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=4284
application: spm_forzwcad
text:
  - The basic need for ZWCAD users who work with ESRI Shapefiles (SHP) is to import these kinds of files into ZWCAD
  - Spatial Manager™ for ZWCAD detects what type of information the shapefile contains to import (points, lines or polygons)
  - For any imported file it is possible to automatically subdivide the imported Entities into various ZWCAD Layers, according to the value of a field in the source data table
---
## 

* * *

## 

<span style="color: #ff0000;"><strong>Please, also take a look at the following updated (MAY18) video</strong>:</span>

## 

<span style="color: #ff0000;"><a style="color: #ff0000;" href="https://youtu.be/i1Q9jVaEbVM?rel=0" target="_blank" rel="nofollow"><strong><span style="text-decoration: underline;"><em>Spatial Manager for ZWCAD</em></span> </strong></a></span>

## 

* * *

## 

Please, watch the video:



Many <a href="https://www.zwsoft.com/zwcad/" target="_blank" rel="nofollow">ZWCAD</a> users who handle geospatial information need to work with ESRI Shapefiles (SHP), by downloading these files from the web or by collaborating with others GIS users, and their basic need is to import these kinds of files into ZWCAD by transforming the Shapefiles features into ZWCAD Entities

A <a title="Shapefile in Wikipedia" href="http://en.wikipedia.org/wiki/Shapefile" target="_blank" rel="nofollow">Shapefile (SHP)</a> is a digital vector storage format for storing geometric location and associated attribute information. Shapefiles (SHP) are simple because they store the primitive geometric data types of points, lines, and polygons. They are of limited use without any attributes to specify what they represent. Therefore, a table of records will store properties/attributes for each primitive shape in the Shapefile. Shapes (points/lines/polygons) together with data attributes can infinitely create many representations about geographic data

## Shapefile to CAD

When converting SHP to CAD files the following considerations have to be taken into account:

· 3D features in the Shapefiles must be converted to 3D CAD Entities (Points, Polylines, etc.) or to pseudo-3D CAD Entities considering the elevation and the thickness of the Entities

· When importing Point features It is very interesting to use complex CAD Entities (such as Block references in ZWCAD) which can include variable text information (such as Attributes in ZWCAD)
  
· We must also consider the importing of complex Polygon features, which may include more than one internal or external ring, and convert them to appropriate CAD Entities (such as Hatches in ZWCAD)
  
· What is also very interesting is the automatic distribution of the Entities across the drawing depending on the values associated to the Shapefile features (using, for example Layers in ZWCAD)
  
· <span class="hps">Finally</span>, we consider some <span class="hps">system</span> <span class="hps">able</span> <span class="hps">to import and</span> <span class="hps">display the features </span><span class="hps">alphanumeric data</span> (such as Extended Entity Data -EED/XDATA- in ZWCAD)

<a href="http://www.spatialmanager.com/wp-content/uploads/2014/09/How-to-import-shapefiles-into-AutoCAD-Associated-data.png" target="_blank" rel="nofollow"><img class="aligncenter wp-image-1767" src="http://www.spatialmanager.com/wp-content/uploads/2014/09/How-to-import-shapefiles-into-AutoCAD-Associated-data.png" alt="How to import Shapefiles into AutoCAD - EED data and EED viewer panel" width="625" height="639" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/09/How-to-import-shapefiles-into-AutoCAD-Associated-data.png 697w, http://www.spatialmanager.com/wp-content/uploads/2014/09/How-to-import-shapefiles-into-AutoCAD-Associated-data-293x300.png 293w, http://www.spatialmanager.com/wp-content/uploads/2014/09/How-to-import-shapefiles-into-AutoCAD-Associated-data-624x638.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a> _Import shapefile into ZWCAD &#8211; Extended Entitiy Data (EED/XDATA) in the Data viewer palette_

## Import Shapefiles to ZWCAD

<a href="http://www.spatialmanager.com/spm-forzwcad" target="_blank" rel="nofollow">Spatial Manager™ for ZWCAD</a> lets you import graphic Entities into ZWCAD from a large number of GIS sources including ESRI shapefile format

The application detects what type of information the shapefile contains to import (points, lines or polygons) and presents to the user only those import options that are valid for that type of Entities. In the case of polygonal Entities, the closed borders can be automatically filled by using ZWCAD Hatches, or import not only the border of the polygons but also their centroids by using Points or ZWCAD Blocks

For any imported table or file, regardless of its format or type, it is possible to automatically subdivide the imported Entities into various ZWCAD Layers, according to the value of a field in the source data table

## How to import shapefiles into ZWCAD

This example shows how to import Shapefiles into ZWCAD using Spatial Manager™ for ZWCAD. In the video you can see how an SHP Parcels file is imported onto a drawing, which already contains other Entities belonging to a city

The import process fills every Parcel using a Solid transparent Hatch, distributes every Parcel into new Layers according to the zones to which each Parcel belongs and applies random colors for every new Layer created. The alphanumeric data of every Parcel is also imported using ZWCAD Extended Entity Data (EED/XDATA)!

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-zwcad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>