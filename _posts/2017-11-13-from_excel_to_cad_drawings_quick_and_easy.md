---
published: true
title: 'From Excel to CAD drawings: quick and easy'
date: 2017-11-13T18:46:33+00:00
author: admin
layout: old-post
permalink: /from_excel_to_cad_drawings_quick_and_easy/
image: /images/blog/2017/11/Excel-to-CAD-logo-85.jpg
categories:
  - CAD L1 (Basic)
tags:
  - ASCII
  - Excel
  - Import
---
<p>
  Many CAD users often need to import MS Excel spreadsheets that include spatial data tables (coordinates and other data), as Point or Block objects. From the beginning, &#8216;Spatial Manager&#8217; software includes the ability to do it through ODBC connections, but from the version 4 you will find a quicker and easier method<!--more-->
</p>

<h2>
  Related videos: <span><a href="https://youtu.be/4Pe-rdmoYqI?rel=0" target="_blank" rel="nofollow">AutoCAD</a></span> / <span><a href="https://youtu.be/g4ZqOL_QMk0?rel=0" target="_blank" rel="nofollow">BricsCAD</a></span> / <span><a href="https://youtu.be/d5xB_4GHqJY?rel=0" target="_blank" rel="nofollow">ZWCAD</a></span>
</h2>

* * *

<div>
  <a href="/images/blog/2017/11/Excel-to-CAD.jpg" target="_blank" rel="nofollow"><img src="/images/blog/2017/11/Excel-to-CAD-1024x442.jpg" alt="From Excel to CAD" width="625" height="270" srcset="/images/blog/2017/11/Excel-to-CAD-1024x442.jpg 1024w, /images/blog/2017/11/Excel-to-CAD-300x129.jpg 300w, /images/blog/2017/11/Excel-to-CAD-768x331.jpg 768w, /images/blog/2017/11/Excel-to-CAD-624x269.jpg 624w, /images/blog/2017/11/Excel-to-CAD.jpg 1147w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    From Excel to CAD
  </p>
</div>

<h2>
</h2>

<p>
  As said in the header of this post, although you can access Excel or Access files in ‘Spatial Manager’ by connecting through the Windows <a href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> standard (Open Database Connectivity), it is usually faster to export from Excel to a CSV file and take advantage of the <a href="/enhanced_ascii_data_provider_v4/" target="_blank" rel="nofollow">Enhanced ASCII data provider</a>
</p>

<p>
  All products in the &#8216;Spatial Manager&#8217; suite include, among many other tools, a powerful ASCII data provider to read and write plain text files (CSV, ASC, XYZ, etc.), which allows you to access Excel tables that contain point type Features
</p>

<h2>
  The example in the above videos
</h2>

<p>
  It is about importing into an existing CAD drawing of a city located in the Florida state, a set of plants (trees and shrubs) from an Excel spreadsheet, which includes the coordinates of these plants defined in a GPS Latitude/Longitude system (<a href="https://en.wikipedia.org/wiki/Spatial_reference_system" target="_blank" rel="nofollow">CRS</a>: <a href="http://en.wikipedia.org/wiki/WGS84" target="_blank" rel="nofollow">WGS84 / EPSG: 4326</a>), and the related trees and shrubs data
</p>

<p>
  Although &#8216;Spatial Manager&#8217; can import the plants as Point objects, and we will get all related data as Extended Entity Data (EED/XDATA), we can also use one or more Block definitions in the drawing to import them. In this example, the Block definition includes some Attribute definitions whose values will also be imported from their corresponding data in Excel
</p>

<p>
  The target drawing has been defined using the CRS <a href="http://spatialreference.org/ref/epsg/2777/" target="_blank" rel="nofollow">&#8216;NAD83(HARN) / Florida East&#8217; (EPSG: 2777)</a> so the coordinates of the plants will be transformed from EPSG 4326 to this CRS inside the import process
</p>

<h2>
</h2>

* * *

<p>
  Please, go to the technical Wikis if you want to learn more about importing spatial data in CAD drawings:
</p>

<p>
  <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow">· Spatial Manager for AutoCAD</a></em><br /> <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow"><em>· Spatial Manager for BricsCAD<br /> </em></a><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Import" target="_blank" rel="nofollow">· Spatial Manager for ZWCAD</a></em>
</p>