---
published: true
title: Advanced methods for selecting Features in a Map
date: 2014-01-05T15:15:07+00:00
author: admin
layout: old-post
permalink: /advanced-selection-methods-using-spatial-manager-desktop/
image: /images/blog/2014/01/Selection-85.png
categories:
  - Desktop L3 (Advanced)
tags:
  - DXF
  - 'Queries &amp; Filters'
  - Selection
---
Spatial Manager Desktop™ includes multiple, simple or advanced methods to select Features: graphical selections, Data grid selections, queries over Layers, restrict the selection to a Layer, add/remove Features to/from a selection, spatial queries and more<!--more-->

Using some of these methods, we can solve the next case: **we need to locate, in a Map of a city, those buildings** that, being located at an elevation of 1500 to 2000 feet, are found in two areas of the city, one polygonal and another circular defined by its radius and its center. Furthermore, **we need to incorporate these buildings** into another simplified map of the city that we have **in AutoCAD format**

The steps to follow are:

• We perform a **query selection** over the buildings Layer, by defining a complex query for those Features that satisfy the condition of their elevation ranging between 1500 and 2000 feet
  
• We **make a new Layer** (buildings2) including the current selected Features
  
• We define a **primary selection** for the polygonal area and, holding down the CTRL key, we now define the circular area by locating its center and its radius on the screen
  
• We **restrict the current selection to the new Layer** (buildings2)
  
• Finally, **we export the current selection to a DXF** file that we can insert into another AutoCAD drawing

Please, watch the video:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/T-f4Xdk1_4I" allowfullscreen></iframe>
</div>