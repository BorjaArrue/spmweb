---
published: true
title: Managing Multi-Polygons in AutoCAD, BricsCAD or ZWCAD
date: 2018-10-31T16:04:20+00:00
author: admin
layout: old-post
permalink: /managing-multi-polygons-in-autocad-bricscad-zwcad/
image: /images/blog/2018/10/MPolSPM85.png
categories:
  - CAD L2 (Medium)
tags:
  - Fills
  - Import
  - Shapefiles (SHP)
  - Tricks and Tools
---
<p>
  A problem that the spatial information users face when working in CAD applications is importing and handling Polygons that contain multiple rings and/or holes (Multi-Polygons or MPolygons). But these applications include a very standard object type (HATCH) that will behave like a Multi-Polygon in graphical rendering, geometric edition and other aspects
</p>

<p>
  <!--more-->
</p>

<h2>
  Related videos: <a href="https://youtu.be/GlGIohjhGZ0?rel=0" target="_blank" rel="nofollow"><span><span>AutoCAD</span></span></a> / <a href="https://youtu.be/JWMSVQMqgYE?rel=0" target="_blank" rel="nofollow"><span><span>BricsCAD</span></span></a> / <a href="https://youtu.be/Q8GwjrwzH6Q?rel=0" target="_blank" rel="nofollow"><span><span>ZWCAD</span></span></a>
</h2>

<h2>
</h2>

<div>
  <a href="/images/blog/2018/10/SPM_Hatch_MPol.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/10/SPM_Hatch_MPol.png" alt="'Spatial Manager' and Multi Polygons" width="1280" height="650" srcset="/images/blog/2018/10/SPM_Hatch_MPol.png 1280w, /images/blog/2018/10/SPM_Hatch_MPol-300x152.png 300w, /images/blog/2018/10/SPM_Hatch_MPol-768x390.png 768w, /images/blog/2018/10/SPM_Hatch_MPol-1024x520.png 1024w, /images/blog/2018/10/SPM_Hatch_MPol-624x317.png 624w" sizes="(max-width: 1280px) 100vw, 1280px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; and Multi Polygons
  </p>
</div>

<h2>
</h2>

<p>
  Users of CAD applications that need to deal with geospatial information, GIS or maps are interested in handling <strong>unitary polygonal elements as a single object</strong> in their drawing, not only to obtain a unitary graphical representation but also to assign one data record to a single object and not to multiple objects. Think for example of a <strong>building unit</strong> that includes several buildings blocks and/or interior courtyards, or a <strong>cadastral parcel unit</strong> consisting of several non-adjacent parcels
</p>

<h2>
</h2>

<p>
  Although the most widely used CAD applications have always pursued the option of managing MPolygons, an object defined as native in AutoCAD Map, in most cases <strong>these objects cause problems in multiple processes</strong> such as printing, vertices or segments editing, and others
</p>

<h2></h2>
<p>
  &#8216;Spatial Manager&#8217; software includes the <strong>option to fill Polygonal or Multi-Polygonal</strong> features with a single Hatch object<em> (*)</em> when importing from a data source containing polygons
</p>

<h2>
</h2>

<div>
  <a href="/images/blog/2018/10/FillSPMOptions.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/10/FillSPMOptions.png" alt="Fill options in 'Spatial Manager'" width="855" height="438" srcset="/images/blog/2018/10/FillSPMOptions.png 855w, /images/blog/2018/10/FillSPMOptions-300x154.png 300w, /images/blog/2018/10/FillSPMOptions-768x393.png 768w, /images/blog/2018/10/FillSPMOptions-624x320.png 624w" sizes="(max-width: 855px) 100vw, 855px" /></a>
  
  <p>
    Fill options in &#8216;Spatial Manager&#8217;
  </p>
</div>

<h2></h2>
In the above videos you can see the complete import process and learn how to comfortably select the Polylines that shape the Polygons or Multi-Polygons borders in order to **erase them, or simply Detach them** from the Data Table so that **only the Hatch remains Attached** to the Table

<h2></h2>
_(*) Note: &#8216;Spatial Manager for AutoCAD&#8217; also includes the option to use MPolygons when importing, as AutoCAD allows to programmatically create this type of objects_

<h2></h2>


<h2></h2>
<p>
  Learn more about how to<strong> import and customize spatial objects</strong> and data into your drawings:
</p>

<h2>
</h2>

<ul>
  <li>
    <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow"><em><span>Spatial Manager for AutoCAD</span></em></a>
  </li>
  <li>
    <em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span></em>
  </li>
  <li>
    <em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span></em>
  </li>
</ul>