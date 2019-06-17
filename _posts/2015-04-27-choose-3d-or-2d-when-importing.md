---
id: 2410
title: Choose 3D or 2D when importing
date: 2015-04-27T14:42:25+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=2410
permalink: /choose-3d-or-2d-when-importing/
image: /wp-content/uploads/2015/04/Spatial-Manager-for-AutoCAD-Contours-85.png
categories:
  - CAD L1 (Basic)
tags:
  - 2D
  - 3D
  - Import
---
A set of objects imported by applying its coordinate Z=0 leads to a &#8220;flat&#8221; map which allows us often to perform operations that are more &#8220;uncomfortable&#8221; when using 3D maps: 2D references, measurements of distances in the plane, etc.

<!--more-->

## Importing &#8220;2D&#8221; maps

When importing objects into <a title="Spatial Manager™ for AutoCAD product page" href="http://www.spatialmanager.com/spm-forautocad/" target="_blank" rel="nofollow">AutoCAD</a> or <a title="Spatial Manager™ for BricsCAD product page" href="http://www.spatialmanager.com/spm-forbricscad/" target="_blank" rel="nofollow">BricsCAD</a> drawings using Spatial Manager™, you will find an option to ignore their Z coordinates in the Importing parameters window (_see image below and the Wiki <a title="How can I Import spatial Features as AutoCAD Objects?" href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow">AutoCAD</a>/<a title="How can I Import spatial Features as BricsCAD Entities?" href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow">BricsCAD</a>_)

By using this option you can select the importation of Points, Polylines or Polygons including 3D data or 2D data only, causing their **transfer to the XY plane**. Even in the case of 3D polylines whose vertices may be located at different Z coordinates, the importing process will result in a &#8220;projection&#8221; of the polyline to the XY plane

There is a quite common situation in which it is handy to obtain a 2D map from 3D cartography and simultaneously label the Z coordinates of the objects: <a title="Post: Point coordinates also as data fields" href="http://www.spatialmanager.com/?p=2397" target="_blank" rel="nofollow"><em>see &#8220;Point coordinates also as data fields&#8221;</em></a>

<p>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2015/04/Spatial-Manager-for-AutoCAD-Import-2D-Flat.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2015/04/Spatial-Manager-for-AutoCAD-Import-2D-Flat.png" alt="Spatial Manager for AutoCAD Import 2D (Flat)" width="567" height="575" srcset="http://www.spatialmanager.com/wp-content/uploads/2015/04/Spatial-Manager-for-AutoCAD-Import-2D-Flat.png 567w, http://www.spatialmanager.com/wp-content/uploads/2015/04/Spatial-Manager-for-AutoCAD-Import-2D-Flat-295x300.png 295w" sizes="(max-width: 567px) 100vw, 567px" /></a>
</p>

## Please, watch these videos:

### AutoCAD importing



### BricsCAD importing