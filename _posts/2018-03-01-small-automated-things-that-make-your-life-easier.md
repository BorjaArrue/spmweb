---
published: true
title: Small automated things that make your life easier
date: 2018-03-01T06:19:04+00:00
author: admin
layout: old-post
permalink: /small-automated-things-that-make-your-life-easier/
image: /images/blog/2018/02/SPM-Automate-85.png
categories:
  - CAD L2 (Medium)
tags:
  - Import
  - Tricks and Tools
---
<p>
  &#8216;Spatial Manager&#8217; (for AutoCAD, BricsCAD or ZWCAD) includes some little-known automations that make the everyday application tasks more comfortable. This article and the included videos review some of these little automatic assistances
</p>

<p>
  <!--more-->
</p>

<h2>
  Related videos: <span><a href="https://youtu.be/oSKPE9yezi0?rel=0" target="_blank" rel="nofollow"><span>AutoCAD</span></a> </span>/ <span><a href="https://youtu.be/n0x1CF7tXQY?rel=0" target="_blank" rel="nofollow"><span>BricsCAD</span></a> </span>/ <span><a href="https://youtu.be/wTbDU-xcc6c?rel=0" target="_blank" rel="nofollow"><span>ZWCAD</span></a></span>
</h2>

* * *

<div>
  <a href="/images/blog/2018/02/Little-automation-helps-Spatial-Manager.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/02/Little-automation-helps-Spatial-Manager-1024x535.png" alt="Little automation helps - Spatial Manager" width="625" height="327" srcset="/images/blog/2018/02/Little-automation-helps-Spatial-Manager-1024x535.png 1024w, /images/blog/2018/02/Little-automation-helps-Spatial-Manager-300x157.png 300w, /images/blog/2018/02/Little-automation-helps-Spatial-Manager-768x401.png 768w, /images/blog/2018/02/Little-automation-helps-Spatial-Manager-624x326.png 624w, /images/blog/2018/02/Little-automation-helps-Spatial-Manager.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Little automation helps &#8211; Spatial Manager
  </p>
</div>

<h2>
</h2>

<li>
  <div>
    Automatic<strong> assignment of the Coordinate System</strong> (CRS) to an unreferenced (no CRS assigned) drawing when importing from a source whose CRS is known. This simplifies the (likely) assignment of a CRS from the origin to the target
  </div>
</li>

<li>
  <div>
    If the drawing is empty, the import processes <strong>Zoom to the imported objects. </strong>So that you can easily locate them
  </div>
</li>

<li>
  Automatic <strong>assignment of a projected <span><a href="https://en.wikipedia.org/wiki/Web_Mercator" target="_blank" rel="nofollow">Pseudo-Mercator</a></span> CRS</strong> to the drawing when importing into an unreferenced drawing from <span><a href="https://en.wikipedia.org/wiki/Google_Earth" target="_blank" rel="nofollow">Google Earth,</a></span>  <span><span><a href="https://en.wikipedia.org/wiki/OpenStreetMap" target="_blank" rel="nofollow">OpenStreetMap</a></span></span>, <span><a href="https://en.wikipedia.org/wiki/GPS_Exchange_Format" target="_blank" rel="nofollow">GPX</a></span> and others. These formats use a <span><a href="https://en.wikipedia.org/wiki/Geographic_coordinate_system#Geographic_latitude_and_longitude" target="_blank" rel="nofollow">geographic CRS</a></span> to store the spatial information, and the users are usually interested in getting <span><a href="https://en.wikipedia.org/wiki/Geographic_coordinate_system#Map_projection" target="_blank" rel="nofollow">projected</a></span> spatial information into the drawings. This automation can be deactivated (read the next paragraph)
</li>
<li>
  In addition, in the previous import scenario, <strong>the &#8220;Transform Coordinates&#8221; option is also automatically activated</strong>. You can uncheck this option in the Importing Wizard. In this case, the automations #3 and #4 would be not effective but the automation #1 would be applied
</li>
<li>
  If the <strong>drawing is empty and unreferenced</strong>, when &#8216;SPMBGMAPSHOW&#8217; is executed the application <strong>will assign the Background Map CRS</strong> to the drawing
</li>
<li>
  Automatic <strong>activation of the &#8220;Transform Coordinates&#8221; option</strong> while importing, if the drawing has any assigned CRS and the source has the CRS defined (or the user defines it while importing)
</li>
<li>
  Automatic <strong>mapping of appropriate data column names as X Y Z Coordinates</strong> when importing from user ASCII files. Many names, such as X, Lat, Longitude, H, etc. are considered valid
</li>

<h2>
</h2>

<div>
  <a href="/images/blog/2018/02/Automated-XYZ-columns-selection.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/02/Automated-XYZ-columns-selection-300x247.png" alt="Automated XYZ columns selection" width="450" height="370" srcset="/images/blog/2018/02/Automated-XYZ-columns-selection-300x247.png 300w, /images/blog/2018/02/Automated-XYZ-columns-selection.png 563w" sizes="(max-width: 450px) 100vw, 450px" /></a>
  
  <p>
    Automated XYZ columns selection
  </p>
</div>

<h2></h2>
* * *

<h2>
</h2>

<p>
  Learn more about <strong>Importing geo-spatial data</strong> in &#8216;Spatial Manager&#8217;:
</p>

<h2></h2>
  * **Blog**: 
      * _<span><span><a href="/tag/import/" target="_blank" rel="nofollow">Importing posts</a></span></span>_

<h2></h2>
  * **Technical Wiki**: 
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for AutoCAD</a></span>_
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span>_
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span>_<span><br /> </span>