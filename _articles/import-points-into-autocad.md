---
id: 1588
title: Import points into AutoCAD
date: 2014-08-22T11:06:33+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=1588
application: spm_forautocad
text:
  - Point features in spatial data systems may represent different types of elements from the real world
  - Spatial Manager™ for AutoCAD includes many powerful "AutoCAD Import Points" data providers to import points into AutoCAD
  - You can choose between AutoCAD Point objects or Block references as imported objects, and many other interesting drawing options through the import process
  - You can perform a coordinate transformation "on the fly" when importing
---
Watch this video to see how to **Import Points into AutoCAD**:



<span class="hps">This technical page</span> <span class="hps">describes how</span> <span class="hps">to <strong>Import</strong></span>** points <span class="hps">into</span>** <span class="hps"><strong>AutoCAD</strong>. Point features in spatial data systems may <span class="hps alt-edited">represent different types of</span> <span class="hps">elements from the real</span> <span class="hps">world. These elements may be real objects (hydrants, containers, <span class="hps">streetlights, etc.) or <span class="hps">fictitious</span> points (milestones, locations, addresses, etc.)</span></span></span>

<span class="hps alt-edited">Most</span> file <span class="hps">formats</span> <span class="hps">and</span> <span class="hps">spatial servers</span> <span class="hps">include</span> in some way <span class="hps">the possibility to store</span> <span class="hps">information about</span> <span class="hps">Points. Some of them can only save basic data, such as the Point coordinates <span class="hps">and</span> <span class="hps alt-edited">slightly more data</span> in the <a title="ASCII in Wikipedia" href="http://en.wikipedia.org/wiki/Ascii" target="_blank" rel="nofollow">ASCII</a> <a title="CSV in Wikipedia" href="http://en.wikipedia.org/wiki/Comma-separated_values" target="_blank" rel="nofollow">CSV</a> standard formats, <span class="hps alt-edited">but most</span> <span class="hps">systems</span> include<span class="hps"> information</span>, usually <span class="hps">alphanumeric</span> data, <span class="hps">associated</span> <span class="hps">with</span> <span class="hps">the Points</span></span>

## <span class="hps alt-edited">Common containers</span> to store Points features

<span class="hps">As</span> <span class="hps alt-edited">already stated</span>, there are many <span class="hps">spatial systems</span> <span class="hps alt-edited">to store</span> Points <span class="hps">information, <span class="hps">but</span> <span class="hps">in</span> <span class="hps alt-edited">the following list</span> <span class="hps alt-edited">you can find some of</span> <span class="hps alt-edited">the most common</span>:</span>

· <a title="Shapefile in WIkipedia" href="http://en.wikipedia.org/wiki/Shapefile" target="_blank" rel="nofollow">Point ESRI Shape files (SHP)<br /> </a>· <a title="KML/KMZ in Wikipedia" href="http://en.wikipedia.org/wiki/Kml" target="_blank" rel="nofollow">Google Earth files (KML/KMZ)<br /> </a>· <a title="GPX in Wikipedia" href="http://en.wikipedia.org/wiki/GPS_eXchange_Format" target="_blank" rel="nofollow">GPS exchange format files (GPX)<br /> </a>· ASCII text files (CSV, TXT, XYZ, UPT, etc.) &#8211; data limited
  
· <a title="MS Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow"><span class="hps">MS</span> </a><span class="hps"><a title="MS Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">Excel</a></span> files (XLS)
  
· <a title="MS Access product page" href="http://office.microsoft.com/en-us/access/" target="_blank" rel="nofollow">MS Access</a> files (MDB)
  
· <a title="PostGIS in Wikipedia" href="http://en.wikipedia.org/wiki/Postgis" target="_blank" rel="nofollow">PostGIS databases<br /> </a>· <a title="MS SQL Server product page" href="http://www.microsoft.com/en-us/server-cloud/products/sql-server/default.aspx" target="_blank" rel="nofollow">MS SQL Server Spatial databases</a> <a href="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-KML-Signals.png" target="_blank" rel="nofollow"><img class="aligncenter size-large wp-image-1594" src="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-KML-Signals-1024x487.png" alt="Import points into AutoCAD - KML Signals in Google Earth" width="625" height="297" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-KML-Signals-1024x487.png 1024w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-KML-Signals-300x142.png 300w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-KML-Signals-624x296.png 624w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-KML-Signals.png 1564w" sizes="(max-width: 625px) 100vw, 625px" /></a>_Signal Points of a city stored in a KML file_

## Point features to CAD

CAD applications users often need to import Point features into their drawings, and the content of the data usually comes from very diverse sources: <a title="GPS in Wikipedia" href="http://en.wikipedia.org/wiki/Gps" target="_blank" rel="nofollow">GPS</a> generic data, surveying data, etc.

<a title="AutoCAD product page" href="http://www.autodesk.com/products/autocad/overview" target="_blank" rel="nofollow">AutoCAD</a>, being one of the popular applications in the CAD market, <span class="hps">only allows</span> <span class="hps">importing points</span> <span class="hps">from</span> <span class="hps">other CAD or MCAD applications</span>, <span class="hps">but leaves out</span> <span class="hps">all the</span> common <span class="hps">formats and</span> data <span class="hps">servers to handle</span> <span class="hps">spatial data</span>

## Import Points into AutoCAD

<a title="Spatial Manager™ for AutoCAD product page" href="http://www.spatialmanager.com/spm-forautocad/" target="_blank" rel="nofollow">Spatial Manager™ for AutoCAD</a> includes many powerful &#8220;**AutoCAD Import Points&#8221;** data providers to **import points into AutoCAD**. The providers allow you to access the most usual file formats and spatial data servers <span class="hps alt-edited">in which</span> <span class="hps">you can find</span> spatial Point data <a href="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-Point-sources.png" target="_blank" rel="nofollow"><img class="aligncenter size-full wp-image-1595" src="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-Point-sources.png" alt="Import points into AutoCAD - Point sources in Spatial Manager™ for AutoCAD" width="681" height="304" srcset="http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-Point-sources.png 681w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-Point-sources-300x133.png 300w, http://www.spatialmanager.com/wp-content/uploads/2014/08/Import-points-into-AutoCAD-Point-sources-624x278.png 624w" sizes="(max-width: 681px) 100vw, 681px" /></a>_**Importing Points into AutoCAD** &#8211; Selecting the source (and the data provider)_

When importing the Points, you can choose between AutoCAD Point objects or Block references as imported objects, and many other interesting drawing options through the import process

You can also perform a coordinate transformation &#8220;on the fly&#8221; when importing the Points. The coordinate transformation is an important issue to consider in Spatial Manager™ for AutoCAD when importing Points because a lot of coordinate data comes from GPS devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values and the users uusually need to import the data usually to projected coordinates in the <a title="DWG in Wikipedia" href="http://en.wikipedia.org/wiki/Dwg" target="_blank" rel="nofollow">DWG</a> drawing

## Example: AutoCAD imports Points

This example shows how to Import from different Point sources (KML, SHP, OSM &#8211; OpenStreetMap &#8211; and GPX) into AutoCAD. We will import a set of Point features into a drawing of a city, using AutoCAD Block References including Attributes to catch various alphanumeric data

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-autocad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>