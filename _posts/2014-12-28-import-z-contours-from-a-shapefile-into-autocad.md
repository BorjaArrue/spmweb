---
published: true
title: Import Z-Contours from a Shapefile into AutoCAD
date: 2014-12-28T12:10:21+00:00
author: admin
layout: old-post
permalink: /import-z-contours-from-a-shapefile-into-autocad/
image: /images/blog/2014/12/Contour85.png
categories:
  - CAD L2 (Medium)
tags:
  - 3D
  - Import
  - Shapefiles (SHP)
---
When reading Shapefiles (SHP) which include terrain Contour lines, it is very common to find that the Z coordinate of each Contour is set as being a numerical data in a Field of the associated data table<!--more-->

## Object Elevations in AutoCAD

The change of the Elevation of 2D Objects in <a title="AutoCAD Product page" href="http://www.autodesk.com/products/autocad/overview" target="_blank" rel="nofollow">AutoCAD</a> allows you to place them in a given Z position. When this value is other than zero, the Objects are moved from the XY base plane to a parallel plane located on another Z position

The result is the same as a vertical displacement for the Objects

<a href="/images/blog/2014/12/Layers.png" target="_blank" rel="nofollow"><img src="/images/blog/2014/12/Layers-1024x576.png" alt="Import Z-Contours from a Shapefile into AutoCAD" width="625" height="351" srcset="/images/blog/2014/12/Layers-1024x576.png 1024w, /images/blog/2014/12/Layers-300x168.png 300w, /images/blog/2014/12/Layers-624x351.png 624w, /images/blog/2014/12/Layers.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>

## Import Z-Contours from a Shapefile

Contour lines are one of several common methods used to denote elevation or altitude and depth on maps. From these contours, a sense of the general terrain can be determined. They are used in a variety of scales, from large-scale engineering drawings and architectural plans, through topographic maps and bathymetric charts, up to continental-scale maps

By applying different Elevations to the flat Polylines which define the altimetry Contour lines of a terrain, you can get a pseudo-3D drawing of the terrain that allows you to display it from different points of view in AutoCAD

In addition, there are multiple applications for AutoCAD that allow you to get a <a title="DTM Wiki page" href="http://en.wikipedia.org/wiki/Digital_elevation_model" target="_blank" rel="nofollow">digital terrain model (DTM)</a>, as well as many other interesting information results for landscaping, civil engineering or urban design, starting from the Contour lines placed on their Z-coordinate

<a title="Spatial Manager™ for AutoCAD Product page" href="/spm-forautocad/" target="_blank" rel="nofollow">Spatial Manager™ for AutoCAD</a> allows you to set many parameters when importing objects from <a title="Shapefile Wiki page" href="http://en.wikipedia.org/wiki/Shapefile" target="_blank" rel="nofollow">Shapefiles</a>, or from many other types of spatial files and data sources. One of these parameters defines the Elevations of the imported Objects by reading them from the numeric value in a Field of the associated data table

Please, watch this video to learn how to import Z-Contours from a Shapefile into AutoCAD:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/kLxSshsM2cA" allowfullscreen></iframe>
</div>