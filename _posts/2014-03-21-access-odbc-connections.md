---
published: true
title: How to access ODBC connections
date: 2014-03-21T20:57:51+00:00
author: admin
layout: old-post
permalink: /access-odbc-connections/
image: /images/blog/2014/03/gis_layers-85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - ODBC
---
The connections through the Windows ODBC standard (Open Database Connectivity) expand the possibilities of access to data sources based on basic connection drivers that the operating system itself or some other applications can provide<!--more-->

Access to certain file types, or tables in certain types of databases, may be limited depending on the data providers that a spatial data management application incorporates. But if this application also includes data providers for standard access or connections, such as <a title="ODBC Wiki" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> and others, the range of possibilities of access, and therefore of manage, geospatial data can grow significantly

Consider, for example, **the ability to access spreadsheets in <a title="Microsoft Excel" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Microsoft Excel</a> as if they were tables in a geospatial database**. That will not only open access to <a title="Microsoft Excel" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Excel</a> files themselves, but also to any of the file formats that <a title="Microsoft Excel" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Excel</a> can import or open (<a title="CSV WIki" href="http://en.wikipedia.org/wiki/Comma-separated_values" target="_blank" rel="nofollow">CSV</a>, <a title="DBF Wiki" href="http://en.wikipedia.org/wiki/Dbf#File_formats" target="_blank" rel="nofollow">DBF</a>, <a title="TXT Wiki" href="http://en.wikipedia.org/wiki/Text_file" target="_blank" rel="nofollow">TXT</a>, etc.)

The products in the Spatial Manager™ suite include, among many others, a powerful data provider to read <a title="ODBC Wiki" href="http://en.wikipedia.org/wiki/" target="_blank" rel="nofollow">ODBC</a> data sources, that allows you to access tables that contain point type Features or <a title="WKB Wiki" href="http://en.wikipedia.org/wiki/Well-known_binary" target="_blank" rel="nofollow">WKB</a> (Well-known binary) geometries

In the example you can see in this video, <a title="Spatial Manager™ for AutoCAD - Page" href="/spm-forautocad/" target="_blank" rel="nofollow">Spatial Manager™ for AutoCAD</a> is used to import to an <a title="Autodesk" href="http://www.autodesk.com/" target="_blank" rel="nofollow">AutoCAD</a> drawing of a city a large number of streetlights from an <a title="Microsoft Excel" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Excel</a> spreadsheet, which includes the coordinates of these streetlights using a Latitude/Longitude system (CRS: <a title="WGS84 Wiki" href="http://en.wikipedia.org/wiki/WGS84" target="_blank" rel="nofollow">WGS84</a> / EPSG: 4326)

We use a Block definition in the drawing to import the streetlights. This Block definition includes some Attribute definitions whose values ​​will also be imported from their corresponding data in <a title="Microsoft Excel" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Excel</a>. The target drawing is defined using the CRS UTM30-ETRS89 (EPSG: 25830) so that the coordinates of the source streetlights will be transformed from EPSG 4326 to this CRS inside the import process

Almost all such steps shown in the video would apply equally in <a title="Spatial Manager Desktop™ - Page" href="/spm-desktop/" target="_blank" rel="nofollow">Spatial Manager Desktop™</a>

_Note: This video also discusses what the right way is to create or edit <a title="ODBC Wiki" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> access for 32-bit and 64-bit applications, when using 64-bit operating systems_

Please, watch the video:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/wOybx5wmUso" allowfullscreen></iframe>
</div>