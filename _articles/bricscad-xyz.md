---
id: 2021
title: BricsCAD XYZ
date: 2015-01-27T15:27:34+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=2021
application: spm_forbricscad
text:
  - The XYZ files are one of the most common types of files to store points coordinates
  - Spatial Manager™ for BricsCAD includes, in addition to many other access tools, a powerful "BricsCAD XYZ" data provider to import XYZ files into BricsCAD
  - You can choose between Point Entities or Block references and many other interesting drawing options through the import process
  - You can perform a coordinate transformation "on the fly" when importing
---
Watch this video to see how to **Import XYZ files into BricsCAD**:



This technical page describes the **BricsCAD** **XYZ** import method. The XYZ files are one of the most common types of files to store points coordinates. They are plain-text <a title="ASCII in Wikipedia" href="http://en.wikipedia.org/wiki/Ascii" target="_blank" rel="nofollow">ASCII</a> files, without binary numbers or any other data type that has to be interpreted, can be easily read or written by any application and a user can look at their content using common utilities, such as Window Notepad **<a href="http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad.png" target="_blank" rel="nofollow"><img class="aligncenter wp-image-1639 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad.png" alt="AutoCAD XYZ file - Open XYZ file in Notepad" width="542" height="244" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad.png 542w, http://www.spatialmanager.com/wp-content/uploads/2014/08/AutoCAD-XYZ-Notepad-300x135.png 300w" sizes="(max-width: 542px) 100vw, 542px" /></a>_BricsCAD_** _**XYZ** file &#8211; Open XYZ file in Notepad_

Every line in the file corresponds to a point data and every number between two delimiter characters in a line corresponds to a coordinate (X, Y or Z) of a point feature. There are various characters that may be used as the delimiter character. The most common used delimiter characters are the comma, the tab, the space character or the semicolon

## XYZ to CAD

CAD applications users often need to import these kind of point data files into their drawings, and the content of the files is usually very diverse: <a title="GPS in Wikipedia" href="http://en.wikipedia.org/wiki/Gps" target="_blank" rel="nofollow">GPS</a> generic data, surveying data, hydrants, signals, address points, etc.

<a title="BricsCAD product page" href="https://www.bricsys.com/en_INTL/bricscad/" target="_blank" rel="nofollow">BricsCAD</a>, being one of the popular applications in the CAD market, cannot directly translate the contents of **XYZ files to BricsCAD**, not even as Point type Entities. To perform a task such as Import XYZ to BricsCAD, you will need an additional BricsCAD utility or plug-in

## Import BricsCAD XYZ file

<a title="Spatial Manager™ for BricsCAD product page" href="http://www.spatialmanager.com/spm-forbricscad" target="_blank" rel="nofollow">Spatial Manager™ for BricsCAD</a> includes, in addition to many other access tools, a powerful **&#8220;BricsCAD XYZ&#8221;** data provider to import XYZ files into BricsCAD

As when importing point type features using any other data provider included in the application, you can choose between Point Entities or Block references and many other interesting drawing options through the import process

You can also perform a coordinate transformation &#8220;on the fly&#8221; when importing. The coordinate transformation is an important issue to consider in Spatial Manager™ for BricsCAD when importing from **XYZ files** because a lot of  coordinate data comes from GPS devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values and the users usually need to import the data to projected coordinates into the <a title="DWG in Wikipedia" href="http://en.wikipedia.org/wiki/Dwg" target="_blank" rel="nofollow">DWG</a> drawing

## Example: Import XYZ file into BricsCAD

This example shows how to **Import a XYZ file into BricsCAD**. We will import a set of surveying points into an BricsCAD drawing. First, we will choose BricsCAD Block references to import the Points as 3D Entities by selecting a **&#8220;XYZ&#8221; file format**

Next, we will apply a nice trick by adding an Attribute to the Block definition and by catching the Z coordinate inside the Attribute to get 2D Points with the Z coordinate <span class="hps">labeled</span> <span class="hps">right next to the</span> <span class="hps">point, when selecting &#8220;XY Description&#8221; as the file format</span>

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-bricscad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>