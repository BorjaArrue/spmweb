---
id: 4415
title: Import coordinates from Excel to ZWCAD
date: 2017-10-29T19:57:34+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=4415
application: spm_forzwcad
text:
  - MS Excel spreadsheets may be considered as tables containing spatial data including coordinates and specific information
  - Although you can access Excel or Access files by connecting through the Windows ODBC standard (Open Database Connectivity), it is usually faster to export from Excel to a CSV file and take advantage of the Enhanced ASCII data provider
  - Spatial Manager for ZWCAD allows you to import points from Excel to ZWCAD as Points or Blocks Entities including attached Extended Entity Data (EED) and Attributes
---
Watch this video to learn how to **Import coordinates from Excel to ZWCAD**:



<a href="https://www.zwsoft.com/zwcad/" target="_blank" rel="nofollow">ZWCAD</a> <span class="hps">users</span> <span class="hps">often need to import</span> <a title="Microsoft Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS <span class="hps">Excel</span></a> spreadsheets, considered <span class="hps">as</span> <span class="hps">tables containing</span> <span class="hps">spatial data</span> including <span class="hps">coordinates</span> <span class="hps">and specific information,</span> as ZWCAD Point or Block Entitie<span class="hps">s</span>

Although you can access Excel or Access files in &#8216;Spatial Manager&#8217; by connecting through the Windows <a href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> standard (Open Database Connectivity), it is usually faster to export from Excel to a CSV file and take advantage of the Enhanced ASCII data provider

## Spatial Manager™ for ZWCAD and ASCII point data

All products in the <a title="Spatial Manager™ web" href="http://www.spatialmanager.com/" target="_blank" rel="nofollow">Spatial Manager™</a> suite include, among many other access tools, a powerful ASCII data provider to read plain text files (CSV, ASC, XYZ, etc.), which allows you to access Excel tables that contain point type Features

<div id="attachment_4420" style="width: 611px" class="wp-caption aligncenter">
  <a href="http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD.png" target="_blank" rel="nofollow"><img class="wp-image-4420" src="http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD-300x169.png" alt="Import coordinates from Excel to ZWCAD" width="601" height="338" srcset="http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD-300x169.png 300w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD-768x432.png 768w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD-1024x576.png 1024w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD-624x351.png 624w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-coordinates-from-Excel-to-ZWCAD.png 1280w" sizes="(max-width: 601px) 100vw, 601px" /></a>
  
  <p class="wp-caption-text">
    Import coordinates from Excel to ZWCAD
  </p>
</div>

## Excel coordinates and ZWCAD

Most applications in the market developed to **Import coordinates from Excel to ZWCAD,** operate using only exported basic format ASCII files, such as XYZ, PNEZ or UPT files, and manage only coordinates but not related data and rarely perform a coordinate transformation

The coordinate transformation <span class="hps">is an important</span> <span class="hps">issue to consider</span> because a lot of coordinate data comes from <a title="GPS in Wikipedia" href="http://en.wikipedia.org/wiki/Gps" target="_blank" rel="nofollow">GPS</a> devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values in Excel and the users usually need to import the data to projected coordinates into the DWG drawing

## Example: Import coordinates from Excel to ZWCAD

Scenario: importing into a ZWCAD drawing of a city a large number of streetlights from an Excel spreadsheet, which includes the coordinates of these <span class="hps">streetlights,</span> using a Latitude/Longitude system (CRS: <a title="WGS84 in Wikipedia" href="http://en.wikipedia.org/wiki/WGS84" target="_blank" rel="nofollow"><span style="color: #0054a0;">WGS84</span></a> / EPSG: 4326), and the related <span class="hps">streetlights</span> data

Although <a title="Spatial Manager™ for BricsCAD product page" href="http://www.spatialmanager.com/spm-forzwcad" target="_blank" rel="nofollow">Spatial Manager™ for ZWCAD</a> can import the <span class="hps">streetlights</span> as Point Entities, and we will get all related data as Extended Entity Data (EED), we can also use a Block definition in the drawing to import them. This Block definition includes some Attribute definitions whose values will also be imported from their corresponding data in Excel

The target drawing is defined using the CRS UTM30-ETRS89 (EPSG: 25830) so that the coordinates of the source streetlights will be transformed from EPSG 4326 to this CRS inside the import process

&nbsp;

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-zwcad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>