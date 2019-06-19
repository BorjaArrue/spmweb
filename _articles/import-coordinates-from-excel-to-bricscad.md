---
id: 1997
title: Import coordinates from Excel to BricsCAD
date: 2015-01-27T15:27:52+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=1997
application: spm_forbricscad
text:
  - MS Excel spreadsheets may be considered as tables containing spatial data including coordinates and specific information
  - By connecting through the Windows ODBC standard (Open Database Connectivity) the applications can expand the possibilities of access to spatial data
  - Spatial Manager for BricsCAD allows you to import points from Excel to BricsCAD as Points or Blocks Entities including attached Extended Entity Data (EED) and Attributes
---
<span style="color: #ff0000;"><em>*** Update: Please, <span style="color: #0000ff; text-decoration: underline;"><a style="color: #0000ff; text-decoration: underline;" href="https://youtu.be/g4ZqOL_QMk0?rel=0" target="_blank" rel="nofollow">watch this video</a></span> that shows a quicker way to Import from Excel or Access taking advantage of the Enhanced ASCII data provider from v.4 ***</em></span>

Watch this video to learn how to **Import coordinates from Excel to BricsCAD**:



<a title="BricsCAD product page" href="https://www.bricsys.com/en_INTL/bricscad/" target="_blank" rel="nofollow">BricsCAD</a> <span class="hps">users</span> <span class="hps">often need to import</span> <a title="Microsoft Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS <span class="hps">Excel</span></a> spreadsheets, considered <span class="hps">as</span> <span class="hps">tables containing</span> <span class="hps">spatial data</span> including <span class="hps">coordinates</span> <span class="hps">and specific information,</span> as BricsCAD Point or Block Entitie<span class="hps">s</span>

By connecting through the Windows <a title="ODBC in Wikipedia" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> standard the applications can expand the possibilities of access to most data sources based on standard connection drivers that the operating system itself or any other applications can provide

## ODBC Connections

Access to tables in MS Excel files, may be limited depending on the data providers that a spatial data management application incorporates. But if this application includes data providers for standard access or connections, such as ODBC, the range of possibilities of access to and therefore  the management of geospatial data from Excel files can grow significantly, and the user can import not only coordinate values but also related data

## Spatial Manager™ for BricsCAD and ODBC

All products in the <a title="Spatial Manager™ web" href="http://www.spatialmanager.com/" target="_blank" rel="nofollow">Spatial Manager™</a> suite include, among many other access tools, a powerful data provider to read ODBC data sources, that allows you to access Excel tables that contain point type Features

<a href="http://www.spatialmanager.com/wp-content/uploads/2014/12/Import-coordinates-from-Excel-to-BricsCAD.png" target="_blank" rel="nofollow"><img class="aligncenter size-large wp-image-2003" src="http://www.spatialmanager.com/wp-content/uploads/2014/12/Import-coordinates-from-Excel-to-BricsCAD-1024x575.png" alt="Import coordinates from Excel to BricsCAD - Adding ODBC data source" width="625" height="350" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/12/Import-coordinates-from-Excel-to-BricsCAD-1024x575.png 1024w, http://www.spatialmanager.com/wp-content/uploads/2014/12/Import-coordinates-from-Excel-to-BricsCAD-300x168.png 300w, http://www.spatialmanager.com/wp-content/uploads/2014/12/Import-coordinates-from-Excel-to-BricsCAD-624x350.png 624w, http://www.spatialmanager.com/wp-content/uploads/2014/12/Import-coordinates-from-Excel-to-BricsCAD.png 1281w" sizes="(max-width: 625px) 100vw, 625px" /></a>

&nbsp;

## Excel coordinates and BricsCAD

Most applications in the market developed to **Import coordinates from Excel to BricsCAD**, operate using only ASCII files, such as <a title="CSV files in Wikipedia" href="http://en.wikipedia.org/wiki/Comma-separated_values" target="_blank" rel="nofollow">CSV</a> files exported from Excel, and manage only coordinates but not related data and rarely perform a coordinate transformation

The coordinate transformation <span class="hps">is an important</span> <span class="hps">issue to consider</span> because a lot of coordinate data comes from <a title="GPS in Wikipedia" href="http://en.wikipedia.org/wiki/Gps" target="_blank" rel="nofollow">GPS</a> devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values in Excel and the users usually need to import the data to projected coordinates into the DWG drawing

## Example: Import coordinates from Excel to BricsCAD

Scenario: importing into a BricsCAD drawing of a city a large number of streetlights from an Excel spreadsheet, which includes the coordinates of these <span class="hps">streetlights,</span> using a Latitude/Longitude system (CRS: <a title="WGS84 in Wikipedia" href="http://en.wikipedia.org/wiki/WGS84" target="_blank" rel="nofollow"><span style="color: #0054a0;">WGS84</span></a> / EPSG: 4326), and the related <span class="hps">streetlights</span> data

Although <a title="Spatial Manager™ for BricsCAD product page" href="http://www.spatialmanager.com/spm-forbricscad" target="_blank" rel="nofollow">Spatial Manager™ for BricsCAD</a> can import the <span class="hps">streetlights</span> as Point Entities, and we will get all related data as Extended Entity Data (EED), we can also use a Block definition in the drawing to import them. This Block definition includes some Attribute definitions whose values will also be imported from their corresponding data in Excel

The target drawing is defined using the CRS UTM30-ETRS89 (EPSG: 25830) so that the coordinates of the source streetlights will be transformed from EPSG 4326 to this CRS inside the import process

_Note: This video also discusses what the right way is to create or edit ODBC access for 32-bit and 64-bit applications, when using 64-bit operating systems_

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-bricscad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>