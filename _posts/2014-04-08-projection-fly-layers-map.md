---
id: 912
title: Projecting Maps on the fly
date: 2014-04-08T11:10:25+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=912
permalink: /projection-fly-layers-map/
image: /wp-content/uploads/2014/03/image-85.png
categories:
  - Desktop L2 (Medium)
tags:
  - CRS
  - Geo-reference
  - Layers
  - Maps
---
Spatial Manager Desktop™ considers the coordinate systems of the Layers in a Map to get a real view of their Features which will be projected according to the coordinate system of the Map <!--more-->

When working with an application that includes the representation of Maps that can be composed by Layers defined using different coordinate systems (CRS), it is desirable that the Features in these Layers are projected on the fly by carrying out a transformation to the CRS of the Map

For example, if a Map is defined using the geographic CRS &#8220;WGS84&#8221; (<a title="EPSG Geodetic Parameter Dataset" href="http://www.epsg-registry.org/" target="_blank" rel="nofollow">EPSG</a>: 4326) and the CRS used for a Layer in the Map is the projected CRS &#8220;WGS84-UTM zone 32N&#8221; (<a title="EPSG Geodetic Parameter Dataset" href="http://www.epsg-registry.org/" target="_blank" rel="nofollow">EPSG</a>: 32632), for a correct visualization of the Features of this Layer in the Map a coordinate transformation on the fly will be required between these systems (Origin = 32632, Destination = 4326)

Because the application works with Layers defined using different CRSs,  in addition to the proper display of the graphics in the Map, **this technology should consider several aspects** such as the correct selection of Features, the spatial queries between Layers, the Map Layers which can be included in the Map without defined CRS, etc.

In the example shown in this video, we analyze a typical case of **combining Layers defined using different CRSs** and the tools which Spatial Manager Desktop™ provides to work in the Maps

Please, watch the video: