---
id: 824
title: Importing KML files into AutoCAD
date: 2014-03-17T13:16:43+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=824
permalink: /importing-kml-files-autocad/
image: /wp-content/uploads/2014/03/DWG-KML85.png
categories:
  - CAD L1 (Basic)
tags:
  - Google Earth (KML)
  - Import
---
It is becoming increasingly common to find geo-spatial information contained in KML or KMZ files, used by Google Earth, produced by private users or by the administrative authority, and importing such files in AutoCAD has become a necessity<!--more-->

Spatial Manager™ for AutoCAD, whose main function is to import Features from geo-spatial data sources as <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> Objects, includes an interesting data provider to use with <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML/KMZ</a> files. This data provider can read complex <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML/KMZ</a> files (with a complex folder structure), and allows you to **accurately select the information you are importing and distribute it** over <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> Layers according to the folder of the data source in the <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML/KMZ</a> file or following the criteria defined by the value of any data Field of the <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML/KMZ</a> table

In the first part of this example, we will import the entire content of a <a title="Google Earth" href="http://www.google.com/earth/" target="_blank" rel="nofollow">Google Earth KML</a> file in <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a>, without distributing this information in different Layers nor transforming the Coordinate Reference System of the incoming data; files in <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML/KMZ </a>formats are always defined using the <a title="WGS84" href="http://en.wikipedia.org/wiki/WGS84" target="_blank" rel="nofollow">WGS 84 geographic system</a>, whose standard identifier (EPSG) is 4326, and, as you can see in the drawing when the import process is finished, the cursor coordinates indicate values ​​of Latitude and Longitude

In this case, the point type Features are imported as <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> Points, linear type Features as <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> open Polylines and polygon type Features as <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> closed Polylines, adding <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> **Hatches, using the SOLID pattern with a certain level of Transparency**, for those polygons

In the second part, we will import individually two folders from the same <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML</a> file that was used in the first part, into an existing <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> drawing, whose coordinate dimensions are established as the <a title="UTM" href="http://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system" target="_blank" rel="nofollow">UTM30-ED50</a> projected system that, as you can see in the drawing, uses the meter as the unit length. The standard identifier (EPSG) for this system is 23030

The first folder holds point type Features belonging to a network and will be imported as  <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> Block References using an existing **Block Definition in the drawing**. This Block Definition includes two attributes which can be related to any Field from the source table to take their values. As you can see in the example, if the name of a Field matches that of an Attribute, the application selects this **relationship Field-Attribute** as the default relationship. Furthermore, these Blocks References will be distributed into different new or existing Layers of the drawing depending on the values ​​of one of the Fields of the point type Features in the source

The second folder holds linear type Features corresponding to the previous network, and will be imported using <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> open Polylines into the same Layer

Also, in both import processes carried out in this second part of the example, the Coordinates of the imported Objects are transformed from the original system of the <a title="KML file format" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">KML</a> file (<a title="WGS84" href="http://en.wikipedia.org/wiki/WGS84" target="_blank" rel="nofollow">WGS84</a>) to that of the drawing (<a title="UTM" href="http://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system" target="_blank" rel="nofollow">UTM30-ED50</a>)

Please, watch the video: