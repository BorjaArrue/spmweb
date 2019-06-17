---
id: 2533
title: Export Blocks and External References to Google Earth
date: 2015-06-02T13:47:04+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=2533
permalink: /export-blocks-and-external-references-to-google-earth/
image: /wp-content/uploads/2015/06/Spatial-Manager-Export-Blocks-and-XRef85.png
categories:
  - CAD L2 (Medium)
tags:
  - Export
  - Google Earth (KML)
---
This post examines the available options when exporting Blocks and External References (Xref) from AutoCAD and BricsCAD a geospatial Table

<!--more-->

## Export Blocks and External References

By default Spatial Manager™ will export the Blocks and Xrefs as **point features**, regardless of the selected data provider for the target. The coordinates of the exported Point features correspond to the coordinates of the Insertion points for each Block or Xref

<a href="http://www.spatialmanager.com/wp-content/uploads/2015/06/Export-Blocks-and-External-References-to-Google-Earth-3.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2015/06/Export-Blocks-and-External-References-to-Google-Earth-3.png" alt="Export Blocks and External References to Google Earth 3" width="625" height="278" srcset="http://www.spatialmanager.com/wp-content/uploads/2015/06/Export-Blocks-and-External-References-to-Google-Earth-3.png 805w, http://www.spatialmanager.com/wp-content/uploads/2015/06/Export-Blocks-and-External-References-to-Google-Earth-3-300x133.png 300w, http://www.spatialmanager.com/wp-content/uploads/2015/06/Export-Blocks-and-External-References-to-Google-Earth-3-624x277.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a>

The data of the features will be preserved over the exporting process, and the graphical representation of these features on the system which will manage the exported results will depend on the point stylization options in the system. Anyway, the symbols corresponding to the Blocks or Xrefs will not be kept in the export processes

If you want to export the graphic elements which define one or more Blocks or Xrefs, first of all you need to **&#8220;Explode&#8221;** them in AutoCAD or BricsCAD to get the basic graphic objects that they are composed of (Lines, polylines, Arcs, etc.)

The following example shows you what the difference is when exporting an &#8220;Exploding&#8221; and &#8220;Un-Exploding&#8221; set of Blocks into a KML file, which is then loaded using Google Earth

## Please, watch the videos:

### AutoCAD sample



### BricsCAD sample