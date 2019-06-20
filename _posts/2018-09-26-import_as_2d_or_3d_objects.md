---
published: true
title: Import as 2D or 3D objects
date: 2018-09-26T11:59:30+00:00
author: admin
layout: old-post
permalink: /import_as_2d_or_3d_objects/
image: /images/blog/2018/09/SPM2D-3D85.png
categories:
  - CAD L2 (Medium)
tags:
  - 3D
  - Import
  - Tricks and Tools
---
<p>
  &#8216;Spatial Manager&#8217; includes an option to manage the Z coordinate when importing spatial data (Shapefiles, Google Earth KML, ASCII, Excel, LiDAR, etc.) into AutoCAD, BricsCAD or ZWCAD drawings. It is a configuration little known by many of the application users and it may hide some features that need to be properly understood to optimize the results of the import process
</p>

<p>
  <!--more-->
</p>

<div>
  <a href="/images/blog/2018/09/SPM_Importas2D.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/09/SPM_Importas2D-1024x576.png" alt="'Spatial Manager' - Import as 2D option" width="625" height="352" srcset="/images/blog/2018/09/SPM_Importas2D-1024x576.png 1024w, /images/blog/2018/09/SPM_Importas2D-300x169.png 300w, /images/blog/2018/09/SPM_Importas2D-768x432.png 768w, /images/blog/2018/09/SPM_Importas2D-624x351.png 624w, /images/blog/2018/09/SPM_Importas2D.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; &#8211; Import as 2D option
  </p>
</div>

<h2>
</h2>

<p>
  When the option <em>&#8220;Import as 2D objects&#8230;&#8221;</em> is checked in the application Import parameters, the Z coordinate of the elements being imported is ignored, and <strong>only the values of the XY coordinates are considered</strong> for the Points, Polylines, Polygons, etc. coming from the selected data source
</p>

<h2>
</h2>

<p>
  In this way, you can get <strong>&#8220;flat&#8221; objects</strong> on the XY plane even when the imported source includes three-dimensional information, something that is very handy when working on 2D drawings. It is important to know that if you have configured the import process (in the same parameter window) to use the values in a field in order to define the objects Elevation, this <strong>XY plane will be placed in the Elevation corresponding</strong> to each object
</p>

<h2>
</h2>

<p>
  It is also important to note that this option provides a set of preconfigured conditions depending on the type of data to be imported:
</p>

<h2>
</h2>

<ol>
  <li>
    Data sources including necessary or <strong>relevant Z coordinate</strong>: The option is <strong>unchecked by default</strong> in order to import in 3D, but you can check it if only want to import the XY coordinates <ul>
      <li>
        Some examples would be: <a href="http://www.spatialmanager.com/importing-lidar-data/" target="_blank" rel="nofollow"><span><em>LiDAR</em></span></a>, PointZ type Shapefiles, ASCII files XYZ, PNEZD, PENZD, XYZDesc, UPT, or Custom with a field defining the Z-coordinate, etc.
      </li>
    </ul>
  </li>
  
  <li>
    Data sources that <strong>do not include information about the Z Coordinate</strong>: The option is <strong>checked and disabled</strong> (it is not possible to uncheck it) as only 2D information can be imported <ul>
      <li>
        Some examples would be: MultiPoint, MultipointM, NullShape, Point, PointM, Polygon, PolygonM, Polyline or PolylineM Shapefiles, <a href="http://www.spatialmanager.com/importing-geo-referenced-raster-images/" target="_blank" rel="nofollow"><span><em>Raster files</em></span></a>, ASCII files CodeXY, CodeYX, XYDesc, or Custom without  afield defining the Z-coordinate, etc.
      </li>
    </ul>
  </li>
  
  <li>
    Data sources in which it is a priori <strong>unknown whether or not they include Z-coordinate</strong> information: The option is <strong>checked by default</strong> in order to import in 2D, but you can uncheck it if you want to import Z-coordinates
  </li>
</ol>

<h2>
</h2>

<h2>
</h2>

<p>
  To learn more about <b>how to import spatial geometries and data into your CAD drawings</b>, take a look at the following articles in the products technical Wikis:
</p>

<h2>
</h2>

<ul>
  <li>
    <span><em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import#How_can_I_Import_spatial_Features_as_AutoCAD_Objects.3F" target="_blank" rel="nofollow">Spatial Manager for AutoCAD</a></span></em></span>
  </li>
  <li>
    <span><em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import#How_can_I_Import_spatial_Features_as_BricsCAD_Entities.3F" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span></em></span>
  </li>
  <li>
    <span><em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Import#How_can_I_Import_spatial_Features_as_ZWCAD_Entities.3F" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span></em></span>
  </li>
</ul>