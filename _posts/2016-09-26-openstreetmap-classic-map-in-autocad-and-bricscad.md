---
id: 3429
title: 'OpenStreetMap &#8220;classic look&#8221; in AutoCAD and BricsCAD'
date: 2016-09-26T18:16:24+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=3429
permalink: /openstreetmap-classic-map-in-autocad-and-bricscad/
image: /wp-content/uploads/2016/09/Logo-OSM_SPM85.png
categories:
  - CAD L2 (Medium)
tags:
  - Background Maps
  - OpenStreetMap
---
Although the &#8216;Spatial Manager&#8217; applications include many Background map models that can be chosen directly when you need to display them, you <span>may be interested</span> in access to many others maps available around the world<span>. The “classic look” map of OpenStreetMap cannot be freely distributed within an app but you will see in this example how it can be configured in &#8216;Spatial Manager&#8217;</span>

<!--more-->

<p>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD-1024x576.png" alt="spatial-manager-openstreetmap-classic-in-autocad-and-bricscad" width="625" height="352" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD-1024x576.png 1024w, http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD-300x169.png 300w, http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD-768x432.png 768w, http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD-624x351.png 624w, http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-OpenStreetMap-classic-in-AutoCAD-and-BricsCAD.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
</p>

<h2>
  <strong>Videos: <span><span><a href="https://youtu.be/Cu4V6ln8YvY?rel=0" target="_blank" rel="nofollow">AutoCAD</a> </span>/ <span><a href="https://youtu.be/R1nMbAFqcUs?rel=0" target="_blank" rel="nofollow">BricsCAD</a></span></span></strong>
</h2>

<a href="http://www.spatialmanager.com/spm-forautocad/" target="_blank" rel="nofollow">&#8216;Spatial Manager for AutoCAD&#8217;</a> and <a href="http://www.spatialmanager.com/spm-forbricscad/" target="_blank" rel="nofollow">&#8216;Spatial Manager for BricsCAD&#8217;</a> allow you to set up any **&#8220;User map**&#8221; in a simple and fast way

You only need to know the **appropriate URL** to access the raster &#8220;Tiles&#8221; through any available <a href="https://en.wikipedia.org/wiki/Web_Map_Tile_Service" target="_blank" rel="nofollow">Web Map Tile Service (WMTS)</a>. This URL must include the following **dynamic parameters**:

{level}: _level of zoom_
  
{x}: _horizontal position of tile_
  
{y}: _vertical position of tile_

## 

For example: http://mytileserver.com/mymap/{level}/{x}/{y}.png

## 

In the case at hand, the following is the URL that you need to enter:

**http://a.tile.openstreetmap.org/{level}/{x}/{y}.png**

## 

As you will see in the parameters window, you can also **assign a Name** to the new map and include it into a new or an existing **Group of user maps**

<a href="http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-User-Maps.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-User-Maps.png" alt="spatial-manager-user-maps" width="646" height="557" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-User-Maps.png 646w, http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-User-Maps-300x259.png 300w, http://www.spatialmanager.com/wp-content/uploads/2016/09/Spatial-Manager-User-Maps-624x538.png 624w" sizes="(max-width: 646px) 100vw, 646px" /></a>