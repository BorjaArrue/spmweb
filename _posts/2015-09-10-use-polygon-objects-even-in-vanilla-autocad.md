---
published: true
title: Use Polygon Objects even in vanilla AutoCAD
date: 2015-09-10T13:50:35+00:00
author: admin
layout: old-post
permalink: /use-polygon-objects-even-in-vanilla-autocad/
image: /images/blog/2015/09/Spatial-Manager-Use-Polygon-Objects-even-in-vanilla-AutoCAD-logo-85.png
categories:
  - CAD L2 (Medium)
  - for AutoCAD
tags:
  - Data loading
  - Properties
  - Styles
---
When you import Polygon-type features into AutoCAD using Spatial Manager™ you can choose to convert these features in AutoCAD Polylines or in AutoCAD MPolygons objects, depending on the result you want to obtain in your drawing

<!--more-->

## Please, watch this video and read below:

## 

## What are MPolygons?

The Polylines are well-known objects to any AutoCAD user but, **what about the MPolygons?** The MPolygons are custom objects which serve primarily for representing **multi-part polygons** (e.g. imported from GIS files). So, an MPoygon can define multiple filled or empty (holes) rings

They are custom objects which can be created in AutoCAD Map 3D or AutoCAD Civil 3D, but are also available in vanilla (plain, basic, etc.) AutoCAD using certain applications, such as <a href="http://www.spatialmanager.com/spm-forautocad/" target="_blank" rel="nofollow">Spatial Manager™ for AutoCAD</a>

These objects also have the **&#8220;Fill&#8221; property**. You can set the type and color of the interior &#8220;Fill&#8221; independently to the MPolygon outline/border color, using the AutoCAD &#8220;Properties&#8221; window (Pattern section)

<p>
  <a href="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Parameters-Pols.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Parameters-Pols.png" alt="Spatial Manager for AutoCAD Parameters Pols" width="553" height="587" srcset="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Parameters-Pols.png 553w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Parameters-Pols-283x300.png 283w" sizes="(max-width: 553px) 100vw, 553px" /></a>
</p>

_Polygons options in the importing parameter Windows_

Please, review the &#8220;Properties&#8221; palette data content on the next three samples:

<a href="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-ANSI31.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-ANSI31-1024x577.png" alt="Spatial Manager for AutoCAD Borders ANSI31" width="625" height="352" srcset="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-ANSI31-1024x577.png 1024w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-ANSI31-300x169.png 300w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-ANSI31-624x351.png 624w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-ANSI31.png 1266w" sizes="(max-width: 625px) 100vw, 625px" /></a>

_Case 1: Selecting Polylines and Hatches &#8211; 2 objects for each imported polygon feature_

<a href="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-SOLID.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-SOLID-1024x577.png" alt="Spatial Manager for AutoCAD Borders SOLID" width="625" height="352" srcset="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-SOLID-1024x577.png 1024w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-SOLID-300x169.png 300w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-SOLID-624x351.png 624w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Borders-SOLID.png 1266w" sizes="(max-width: 625px) 100vw, 625px" /></a>

_Case 2: Selecting Polylines and Solid Hatches (Transparent) &#8211; 2 objects for each imported polygon feature_

<a href="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Polygons-SOLID.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Polygons-SOLID-1024x577.png" alt="Spatial Manager for AutoCAD Polygons SOLID" width="625" height="352" srcset="/images/blog/2015/09/Spatial-Manager-for-AutoCAD-Polygons-SOLID-1024x577.png 1024w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Polygons-SOLID-300x169.png 300w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Polygons-SOLID-624x351.png 624w, /images/blog/2015/09/Spatial-Manager-for-AutoCAD-Polygons-SOLID.png 1266w" sizes="(max-width: 625px) 100vw, 625px" /></a>

_Case 3: Selecting MPolygons (Transparent) &#8211; 1 object for each imported polygon feature_