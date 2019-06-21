---
published: true
title: Point coordinates also as data fields
date: 2015-04-21T17:36:19+00:00
author: admin
layout: old-post
permalink: /point-coordinates-also-as-data-fields-2/
image: /images/blog/2015/04/XYZ85.png
categories:
  - CAD L1 (Basic)
  - Desktop L1 (Basic)
tags:
  - Alphanumeric data
  - ASCII
  - Providers
---
There are many situations where it may be interesting to include the values of the geometric coordinates of Points as alphanumeric data, added to some other personal data of the Points. The Spatial Manager™ ASCII Points data provider includes this option in all the applications of the suite

<!--more-->

## The ASCII Points data provider

This data provider is designed to **load, import or export ASCII files** containing geometric information of Points (coordinates) and some additional data (Point number, Point description, etc.)

The system supports the most common file formats as well as the most common file content structures and allows the user to select different ASCII characters as the separators used in each data row and the decimal point of the coordinates

## The coordinates of the Points as information data

But in addition to the above features, in the processes of loading or importing, this data provider allows **the selection of which coordinates (X, Y, Z) will be added as information linked to the Points**, as well as defining their own geometries (_see image below and the Wiki Desktop/AutoCAD/BricsCAD_)

This option allows the user to include the coordinates of the Points in any process in which it is admitted to refer to the values of the data: labeling, queries, thematics, etc.
  
<a href="/images/blog/2015/04/Ascii-provider.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/04/Ascii-provider.png" alt="Ascii provider" width="567" height="610" srcset="/images/blog/2015/04/Ascii-provider.png 567w, /images/blog/2015/04/Ascii-provider-278x300.png 278w" sizes="(max-width: 567px) 100vw, 567px" /></a>

## Practical examples. Please, watch these videos:

Spatial Manager™ for AutoCAD &#8211; Labeling the Z coordinate of the imported Points:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/guwD_0MIltI" allowfullscreen></iframe>
</div>
<br>
Spatial Manager™ for BricsCAD  &#8211; Labeling the Z coordinate of the imported Points:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/1Da81O7X2BI" allowfullscreen></iframe>
</div>
<br />
Spatial Manager Desktop™ &#8211; Querying Points based on their coordinates:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/UzhZUr_ravE" allowfullscreen></iframe>
</div>