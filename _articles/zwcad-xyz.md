---
id: 4404
title: ZWCAD XYZ
date: 2017-10-17T19:10:38+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=4404
application: spm_forzwcad
text:
  - The XYZ files are one of the most common types of files to store points coordinates
  - Spatial Manager™ for ZWCAD includes, in addition to many other access tools, a powerful "ZWCAD XYZ" data provider to import XYZ files into ZWCAD
  - You can choose between Point Entities or Block references and many other interesting drawing options through the import process
  - You can perform a coordinate transformation "on the fly" when importing
---
Watch this video to see how to **Import XYZ files into ZWCAD**:



<div id="attachment_1639" style="width: 552px" class="wp-caption aligncenter">
  <a href="http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad.png" target="_blank" rel="nofollow"><img class="wp-image-1639 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad.png" alt="ZWCAD XYZ file - Open XYZ file in Notepad" width="542" height="244" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad.png 542w, http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad-300x135.png 300w" sizes="(max-width: 542px) 100vw, 542px" /></a>
  
  <p class="wp-caption-text">
    ZWCAD XYZ file &#8211; Open XYZ file in Notepad
  </p>
</div>

This technical page describes the **ZW****CAD** **XYZ** import method. The XYZ files are one of the most common types of files to store points coordinates. They are plain-text <a title="ASCII in Wikipedia" href="http://en.wikipedia.org/wiki/Ascii" target="_blank" rel="nofollow">ASCII</a> files, without binary numbers or any other data type that has to be interpreted, can be easily read or written by any application and a user can look at their content using common utilities, such as Window Notepad

Every line in the file corresponds to a point data and every number between two delimiter characters in a line corresponds to a coordinate (X, Y or Z) of a point feature. There are various characters that may be used as the delimiter character. The most common used delimiter characters are the comma, the tab, the space character or the semicolon

## XYZ to CAD

CAD applications users often need to import these kind of point data files into their drawings, and the content of the files is usually very diverse: <a title="GPS in Wikipedia" href="http://en.wikipedia.org/wiki/Gps" target="_blank" rel="nofollow">GPS</a> generic data, surveying data, hydrants, signals, address points, etc.

<a href="https://www.zwsoft.com/zwcad/" target="_blank" rel="nofollow">ZWCAD</a>, being one of the popular applications in the CAD market, cannot directly translate the contents of **XYZ files to ZWCAD**, not even as Point type Entities. To perform a task such as Import XYZ to ZWCAD, you will need an additional ZWCAD utility or plug-in

## Import ZWCAD XYZ file

<a href="http://www.spatialmanager.com/spm-forzwcad/" target="_blank" rel="nofollow">Spatial Manager™ for ZWCAD</a> includes, in addition to many other access tools, a powerful **&#8220;ZWCAD XYZ&#8221;** data provider to import XYZ files into ZWCAD

As when importing point type features using any other data provider included in the application, you can choose between Point Entities or Block references and many other interesting drawing options through the import process

You can also perform a coordinate transformation &#8220;on the fly&#8221; when importing. The coordinate transformation is an important issue to consider in Spatial Manager™ for ZWCAD when importing from **XYZ files** because a lot of  coordinate data comes from GPS devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values and the users usually need to import the data to projected coordinates into the <a title="DWG in Wikipedia" href="http://en.wikipedia.org/wiki/.dwg" target="_blank" rel="nofollow">DWG</a> drawing

## Example: Import XYZ file into ZWCAD

This example shows how to **Import a XYZ file into ZWCAD**. We will import a set of surveying points into an ZWCAD drawing. First, we will choose ZWCAD Block references to import the Points as 3D Entities by selecting a **&#8220;XYZ&#8221; file format**

Next, we will apply a nice trick by adding an Attribute to the Block definition and by catching the Z coordinate inside the Attribute to get 2D Points with the Z coordinate <span class="hps">labeled</span> <span class="hps">right next to the</span> <span class="hps">point, when selecting &#8220;Custom&#8221; as the file format</span>

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-zwcad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>