---
id: 2017
title: Import CSV into BricsCAD
date: 2015-01-27T15:28:11+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=2017
application: spm_forbricscad
text:
  - The "Comma-separated values" CSV files are one of the most common types of files to store tabular data
  - Spatial Manager™ for BricsCAD includes, in addition to many access tools, a powerful BricsCAD CSV data provider to import CSV files into BricsCAD
  - You can choose between Point Entities or Block references and many other interesting drawing options through the import process
  - You can perform a coordinate transformation "on the fly" when importing
---
Watch this video to see how to **Importing CSV into BricsCAD**:



<span class="hps">This technical page</span> <span class="hps">describes how</span> <span class="hps">to <strong>Import</strong></span>** CSV <span class="hps">into</span> Brics**<span class="hps"><strong>CAD</strong>. </span><span class="hps">The &#8220;Comma-separated values&#8221; <a title="CSV in Wikipedia" href="http://en.wikipedia.org/wiki/Comma-separated_values" target="_blank" rel="nofollow">CSV</a> files are one of the most common types of files to store tabular data. They are plain-text <a title="ASCII in Wikipedia" href="http://en.wikipedia.org/wiki/Ascii" target="_blank" rel="nofollow">ASCII</a> files, without binary numbers or any other data type which has to be interpreted, can be easily read or written by any application and a user can look at their content using common utilities, such as <a title="Windows Notepad in Wikipedia" href="http://en.wikipedia.org/wiki/Windows_Notepad" target="_blank" rel="nofollow">Window Notepad</a><br /> </span>

<a href="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Notepad.png" target="_blank" rel="nofollow"><img class="aligncenter wp-image-1556 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Notepad.png" alt="Import CSV into BricsCAD - Open in Notepad" width="673" height="508" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Notepad.png 673w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Notepad-300x226.png 300w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Notepad-624x471.png 624w" sizes="(max-width: 673px) 100vw, 673px" /></a>

Every line in the file corresponds to a record of a data table and every text or number between two delimiter characters in a line corresponds to a field in this record. There are various characters that may be used as the delimiter character. The most common used delimiter characters are the comma, the tab, the space character or the semicolon

<span class="hps">In addition</span>, <span class="hps">other common</span> <span class="hps">applications, such as</span> <a title="MS Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow"><span class="hps">MS</span> </a><span class="hps"><a title="MS Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Excel</a>,</span> also <span class="hps alt-edited">allow you</span> to <span class="hps">open and edit</span> <span class="hps">this type of file because of their tabular data format</span>

<a href="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Excel.png" target="_blank" rel="nofollow"><img class="aligncenter wp-image-1555 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Excel.png" alt="Import CSV into BricsCAD - Open in Excel" width="700" height="422" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Excel.png 700w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Excel-300x180.png 300w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-CSV-into-AutoCAD-Open-in-Excel-624x376.png 624w" sizes="(max-width: 700px) 100vw, 700px" /></a>

## CSV to CAD

CAD applications users often need to import these kind of point data files into their drawings, and the content of the files is usually very diverse: <a title="GPS in Wikipedia" href="http://en.wikipedia.org/wiki/Gps" target="_blank" rel="nofollow">GPS</a> generic data, surveying data, hydrants, signals, address points, etc.

<a title="BricsCAD product page" href="https://www.bricsys.com/en_INTL/bricscad/" target="_blank" rel="nofollow">BricsCAD</a>, being one of popular applications in the CAD market, cannot directly translate the contents of **CSV to BricsCAD**, not even as Point type Entities. To perform a task such as **Import CSV to BricsCAD**, you will need an additional BricsCAD utility or plug-in

## Import CSV into BricsCAD

<a title="Spatial Manager™ for BricsCAD product page" href="http://www.spatialmanager.com/spm-forbricscad" target="_blank" rel="nofollow">Spatial Manager™ for BricsCAD</a> includes, in addition to many other access tools, a powerful **&#8220;BricsCAD CSV&#8221;** data provider to **import CSV files into BricsCAD**. The provider allows you to access the most usual formats of CSV point files: XYZ, XY Description, Code XY, PNEZD, PENZD, UPT, etc.

As when importing point type features using any other data provider included in the application, you can choose between Point Entities or Block references and many other interesting drawing options through the import process

You can also perform a coordinate transformation &#8220;on the fly&#8221; when importing. The coordinate transformation is an important issue to consider in Spatial Manager™ for BricsCAD when importing from CSV files because a lot of coordinate data comes from GPS devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values and the users usually need to import the data to projected coordinates into the <a title="DWG in Wikipedia" href="http://en.wikipedia.org/wiki/Dwg" target="_blank" rel="nofollow">DWG</a> drawing

## Example: BricsCAD imports CSV

This example shows how to Import a CSV file into BricsCAD. We will import a set of hydrants from two different CSV files into a drawing of a city

First, we will use a simple XYZ coordinate CSV file and BricsCAD Points. Next, we will use a XY and Description CSV file and BricsCAD Block References including an Attribute to catch the Description values

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-bricscad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>