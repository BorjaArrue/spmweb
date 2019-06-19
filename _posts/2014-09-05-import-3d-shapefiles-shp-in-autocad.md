---
id: 1674
title: Import 3D Shapefiles (SHP) in AutoCAD
date: 2014-09-05T06:11:47+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=1674
permalink: /import-3d-shapefiles-shp-in-autocad/
image: /images/blog/2014/08/SHP-DWG3D-85.png
categories:
  - CAD L1 (Basic)
tags:
  - 3D
  - Import
  - Shapefiles (SHP)
---
<span>Some</span> <span>2D</span> Shapefiles (<span>SHP)</span><span> may include 3D</span> <span>information</span> <span>inside</span> <span>its associated</span> <span>alphanumeric data table.</span> For example, i<span>t is quite</span> <span>common to find</span> <span>the values ​​of</span> the <span>elevation and</span> height <span>of</span> <span>the polygon features</span> inside some <span>fields of</span> <span>the data table</span><!--more-->

## 3D and pseudo-3D Shapefiles (SHP)

<span>There are many</span> <a title="Shapefiles (SHP) in Wikipedia" href="http://en.wikipedia.org/wiki/Shapefile" target="_blank" rel="nofollow">Shapefiles (</a><span>SHP)</span> <span>containing</span> complete 3D <span>information inside</span> <span>their</span> own <span>geometry data</span>, <span>as</span> in <span>the PointZ</span>, <span>PolygonZ</span>, etc. SHP files, <span>and even</span> <span>the</span> <span>3D</span> <span>information can be included</span> <span>as </span><span>&#8220;M&#8221;</span> data <span>in</span> <span>the</span> file types <span>PointM</span>, <span>PolygonM</span>, etc. <span>But we can find</span> <span>many cases</span> <span>in which the &#8220;3D&#8221;</span> <span>information that applies to</span> <span>the</span> <span>&#8220;Extrusion</span>&#8221; of <span>flat</span> <span>polygons</span> <span>is found</span> <span>as values</span> <span>​​of some fields in</span> <span>the data table</span> <a href="/images/blog/2014/08/Import-3D-Shapefiles-in-AutoCAD-SHP-Data.png" target="_blank" rel="nofollow"><img src="/images/blog/2014/08/Import-3D-Shapefiles-in-AutoCAD-SHP-Data.png" alt="Import 3D Shapefiles (SHP) in AutoCAD - Data on EED viewer panel" width="625" height="489" srcset="/images/blog/2014/08/Import-3D-Shapefiles-in-AutoCAD-SHP-Data.png 741w, /images/blog/2014/08/Import-3D-Shapefiles-in-AutoCAD-SHP-Data-300x234.png 300w, /images/blog/2014/08/Import-3D-Shapefiles-in-AutoCAD-SHP-Data-624x488.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a> _Import 3D Shapefiles (SHP) in AutoCAD &#8211; Elevation (gnd) and Thickness (height) data_

## Import 3D Shapefiles (SHP) in AutoCAD

The Shapefile (SHP) data provider included in <a title="Spatial Manager for AutoCAD product page" href="http://www.spatialmanager.com/spm-forautocad/" target="_blank" rel="nofollow">Spatial Manager<span>™ </span>for AutoCAD</a> allows you to import all the 3D SHP files as &#8220;real&#8221; <a title="AutoCAD product page" href="http://www.autodesk.com/products/autocad/overview" target="_blank" rel="nofollow">AutoCAD </a>3D objects, <span>but</span> also <span>allows you to assign</span> some objects properties<span> ​​when</span> <span>pseudo</span>-3D <span>polygons</span> <span>are imported</span>

<span>T</span><span>he import process is designed <span>to catch</span> <span>the most relevant</span> properties of the AutoCAD <span>objects from the</span> <span>field values</span> in <span>​​the alphanumeric</span> <span>data</span> <span>tables</span></span>, regardless <span>of the data provider</span> <span>used in the process. <span>Thus</span>, not only <span>can be captured</span> <span>the</span> parameters<span> relating to</span> <span>blocks,</span> <span>block</span> <span>attributes</span> <span>or layers,</span> <span>but</span> <span>you can also automatically</span> <span>assign elevations</span> <span>and thicknesses</span> to the<span> imported AutoCAD objects</span></span>

## Example: Importing 3D buildings in AutoCAD from a pseudo-3D Shapefile (SHP)

In the example shown in this video, we need to import in AutoCAD the buildings information that belongs to an old project in an area of a city which is stored in a Shapefile, in order to compare the buildings in the project and the current status of the area

The associated alphanumeric data table of the Shapefile includes the Elevation value and the Thickness value of the buildings. We will import the file selecting the appropriate fields in the table for these values

Now, in AutoCAD we can set the geographic location for the city and to get the image of the current area status as a map background in order to compare the buildings in the project and their current image

As we have imported the buildings using a pseudo-3D technique the comparison may also be carried out using 3D views

Please, watch the video: