---
id: 4856
title: RTDISPLAY effects on the Background Map images
date: 2018-01-18T08:53:32+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=4856
permalink: /rtdisplay-effects-on-the-background-map-images/
image: /wp-content/uploads/2018/01/Map-Panning85.png
categories:
  - CAD L2 (Medium)
tags:
  - Background Maps
  - Tricks and Tools
---
<p>
  Many BricsCAD and ZWCAD users report that the &#8216;Spatial Manager&#8217; Background Maps temporarily vanish while Zooming or Panning in their drawings. The cause is to be found in the value of the &#8216;RTDISPLAY&#8217; system variable<!--more-->
</p>

<h2>
  Related videos: <span><a href="https://youtu.be/ra5zQfTBvbs?rel=0" target="_blank" rel="nofollow"><span>BricsCAD</span></a></span> / <span><a href="https://youtu.be/gq_EmJusz6Q?rel=0" target="_blank" rel="nofollow"><span>ZWCAD</span></a></span>
</h2>

* * *

<div>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2018/01/RTDISPLAY-Variable-and-Spatial-Manager-Maps.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2018/01/RTDISPLAY-Variable-and-Spatial-Manager-Maps.png" alt="RTDISPLAY System Variable" width="331" height="307" srcset="http://www.spatialmanager.com/wp-content/uploads/2018/01/RTDISPLAY-Variable-and-Spatial-Manager-Maps.png 331w, http://www.spatialmanager.com/wp-content/uploads/2018/01/RTDISPLAY-Variable-and-Spatial-Manager-Maps-300x278.png 300w" sizes="(max-width: 331px) 100vw, 331px" /></a>
  
  <p>
    RTDISPLAY System Variable
  </p>
</div>

<h2>
</h2>

<p>
  The &#8216;RTDISPLAY&#8217; system variable controls whether the raster images <strong>outline</strong> or the <strong>content</strong> of raster images is displayed during the execution of<b> ZOOM or PAN operations</b>. The &#8216;RTDISPLAY&#8217; value is saved in the current user profile and does not change unless modified again
</p>

<h2>
</h2>

<ul>
  <li>
    <em>0: Display the content of raster image (or OLE object)</em>
  </li>
  <li>
    <em>1: Display the outline of raster image (or OLE object) only</em>
  </li>
</ul>

<h2>
</h2>

<p>
  As the Background Maps in &#8216;Spatial Manager&#8217; are <strong>internally managed as raster images</strong> (whether they are full or tiled images), they are affected by the &#8216;RTDIPSLAY&#8217; setting
</p>

<p>
  In order to display the content of Background Maps while Zooming or Panning, be sure the value of &#8216;RTDISPLAY&#8217; is 0. If not, you can change it by keying <strong>RTDISPLAY 0</strong> in the command line or through the BricsCAD/ZWCAD &#8216;Options&#8217; (see the images below)
</p>

<h2>
</h2>

<div>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2018/01/BricsCAD-Real-Time-Display-setting.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2018/01/BricsCAD-Real-Time-Display-setting.png" alt="BricsCAD Real-Time Display setting" width="582" height="398" srcset="http://www.spatialmanager.com/wp-content/uploads/2018/01/BricsCAD-Real-Time-Display-setting.png 582w, http://www.spatialmanager.com/wp-content/uploads/2018/01/BricsCAD-Real-Time-Display-setting-300x205.png 300w" sizes="(max-width: 582px) 100vw, 582px" /></a>
  
  <p>
    BricsCAD Real-Time Display setting
  </p>
</div>

<div>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2018/01/ZWCAD-Real-Time-Display-setting.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2018/01/ZWCAD-Real-Time-Display-setting.png" alt="ZWCAD Real-Time Display setting" width="647" height="396" srcset="http://www.spatialmanager.com/wp-content/uploads/2018/01/ZWCAD-Real-Time-Display-setting.png 647w, http://www.spatialmanager.com/wp-content/uploads/2018/01/ZWCAD-Real-Time-Display-setting-300x184.png 300w, http://www.spatialmanager.com/wp-content/uploads/2018/01/ZWCAD-Real-Time-Display-setting-624x382.png 624w" sizes="(max-width: 647px) 100vw, 647px" /></a>
  
  <p>
    ZWCAD Real-Time Display setting
  </p>
</div>

## 

_Additional useful notes for ZWCAD users (from the <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD" target="_blank" rel="nofollow">Technical Wiki</a>):_

## 

  * _Due to the particular behavior when Zooming in or out by using the mouse wheel in ZWCAD, if you cannot enlarge or reduce the view scale from a certain Zoom level (you will see a warning like this in the status line: &#8220;Can´t be further zoomed in/out&#8221;), please execute &#8220;REGEN&#8221; and you will be able to continue Zooming in or out on the Map_
  * _This warning is not about Background Maps but about Polygon fills: Remember to deactivate the option &#8220;Not display hatch while zooming&#8221; in ZWCAD Options\Display if you want to display the polygon fills while zooming or panning  (see the &#8220;yellowed&#8221; option in the image above)_

## 

* * *

<p>
  If you want to learn more about the Dynamic Background Maps, please review the following technical resources:
</p>

<h2>
</h2>

<span><em><a href="http://www.spatialmanager.com/tag/background-maps/" target="_blank" rel="nofollow">· Blog posts</a></em></span>

## 

Technical Wikis:

## 

<p>
  <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)" target="_blank" rel="nofollow">· Spatial Manager for AutoCAD</a></em><br /> <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)" target="_blank" rel="nofollow"><em>· Spatial Manager for BricsCAD<br /> </em></a><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)" target="_blank" rel="nofollow">· Spatial Manager for ZWCAD<br /> </a><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Background_Maps" target="_blank" rel="nofollow">· Spatial Manager Desktop</a></em>
</p>