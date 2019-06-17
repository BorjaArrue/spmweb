---
id: 6547
title: How to access Yandex maps
date: 2019-05-14T09:40:44+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=6547
permalink: /how-to-access-yandex-maps/
image: /wp-content/uploads/2019/05/SPMYandex85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Background Maps
  - Yandex
---
<p>
  Yandex provides image mapping services as an alternative to similar ones such as Google Maps, OpenStreetMap, etc. Yandex allows users access to tile map servers (XYZ/TMS) for the whole planet but with more diffusion and detail for Eastern European countries
</p>

<p>
  <!--more-->
</p>

<h2>
  Related videos: <a href="https://youtu.be/z6bZ60zfUZo?rel=0" target="_blank" rel="nofollow"><span><span>AutoCAD</span></span></a> / <a href="https://youtu.be/3ZcfbU8wflQ?rel=0" target="_blank" rel="nofollow"><span><span>BricsCAD</span></span></a> / <a href="https://youtu.be/mtOSbhEryAg?rel=0" target="_blank" rel="nofollow"><span><span>ZWCAD</span></span></a> / <span><a href="https://youtu.be/jbu-j8AHMls?rel=0" target="_blank" rel="nofollow">Desktop</a></span>
</h2>

<h2>
</h2>

<div>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2019/05/SPMYandexMaps.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2019/05/SPMYandexMaps-1024x550.png" alt="Yandex Maps configured as 'Spatial Manager' dynamic Background Maps" width="625" height="336" srcset="http://www.spatialmanager.com/wp-content/uploads/2019/05/SPMYandexMaps-1024x550.png 1024w, http://www.spatialmanager.com/wp-content/uploads/2019/05/SPMYandexMaps-300x161.png 300w, http://www.spatialmanager.com/wp-content/uploads/2019/05/SPMYandexMaps-768x413.png 768w, http://www.spatialmanager.com/wp-content/uploads/2019/05/SPMYandexMaps-624x335.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Yandex Maps configured as &#8216;Spatial Manager&#8217; dynamic Background Maps
  </p>
</div>

<h2>
</h2>

<p>
  Although <a href="https://yandex.com/" target="_blank" rel="nofollow"><span><em>Yandex</em></span></a> is a global services platform on the web, in this Blog post we will focus on the access and use of the <span><em><a href="https://tech.yandex.com/maps/" target="_blank" rel="nofollow">Yandex Maps</a></em></span> and their <strong>configuration and application in &#8216;Spatial Manager&#8217;</strong> as user dynamic Background Maps
</p>

<p>
  As mentioned above, this map server uses the <span><em><a href="https://en.wikipedia.org/wiki/Tile_Map_Service" target="_blank" rel="nofollow">XYZ/TMS</a></em></span> specifications and protocols similar for example to Google Maps servers <a href="http://www.spatialmanager.com/tag/google-maps/" target="_blank" rel="nofollow"><span><em>widely discussed in this Blog</em></span></a>, although some differential nuances must be noted:
</p>

<h2>
</h2>

<li>
  There is a server <strong>(vec)</strong> for images obtained from vectorial documentation and a different one <strong>(sat)</strong> for satellite images
</li>
<li>
  Although most XYZ/TMS servers define the maps based on the generic &#8220;WGS 84 / Pseudo-Mercator&#8221; coordinate system (EPSG:3857), Yandex uses a <strong>variant of the Pseudo Mercator system (EPSG:3395)</strong>, which offers a more precise model for the Eastern Europe area. Thanks to the ability to configure in &#8216;Spatial Manager&#8217; the coordinate system in which the XYZ/TMS user maps are defined, you will be able to <strong>setup this parameter through the &#8220;Advanced options&#8221; button</strong><em> (take a look at the above image)</em>
</li>

## 

Next you can find some examples of URLs appropriate in order to access the Yandex maps:

<u>Roadmap (Russian toponyms)</u>:

_http://<span><strong>vec{01,02,03,04}</strong></span>.maps.yandex.net/tiles?**<span>l=map</span>**<span>&</span><span><strong><strong>lang=ru-RU</strong></strong></span>&v=2.26.0&x={x}&y={y}&z={level}_

<u>Roadmap (US English toponyms)</u>:

_http://<span><strong>vec{01,02,03,04}</strong></span>.maps.yandex.net/tiles?**<span>l=map</span>**<span>&</span><span><strong><strong>lang=en-US</strong></strong></span>&v=2.26.0&x={x}&y={y}&z={level}_

<u>Satellite</u>:

_http://<span><strong>sat{01,02,03,04}</strong></span>.maps.yandex.net/tiles?**<span>l=sat</span>**<span>&</span>&v=2.26.0&x={x}&y={y}&z={level}_

<u>Only Roads</u> (that you can <span><em><a href="http://www.spatialmanager.com/bring-background-maps-to-front/" target="_blank" rel="nofollow">Bring to front</a></em></span> above of your drawing/maps objects):

_http://<span><strong>vec{01,02,03,04}</strong></span>.maps.yandex.net/tiles?**<span>l=skl</span>**<span>&</span>v=2.26.0&x={x}&y={y}&z={level}_

## 

Parameters detail:

## 

  * **&#8220;http://vec&#8221;** or **&#8220;http://sat&#8221;**: The map servers (read above)
  * **&#8220;{01,02,03,04}&#8221;**: Sub-domains available on these servers (learn more on <span><em><a href="http://www.spatialmanager.com/map_servers_sub-domains/" target="_blank" rel="nofollow">this Blog post</a></em></span>)
  * &#8220;**l=**&#8220;: Map layer
  * **&#8220;lang=&#8221;** (optional): Language for the map Toponyms, according to the specifications of the <span><em><a href="https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes" target="_blank" rel="nofollow">standard two-characters ISO</a></em></span>

The above videos will show you how to deal with Yandex Maps in &#8216;Spatial Manager&#8217; (and a **little trick to get Hybrid Maps &#8211; Satellite + Roads &#8211;** in the application CAD versions)

<h2>
</h2>

&nbsp;

## 

<h2>
</h2>

<h2>
</h2>

<h2>
</h2>

<p>
  <em>Learn more about configuring user dynamics Background Maps in ‘Spatial Manager’:</em>
</p>

<h2>
</h2>

<ul>
  <li>
    <span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager for AutoCAD</em></span></a></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager for BricsCAD</em></span></a></span></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager for ZWCAD</em></span></a></span></span>
  </li>
  <li>
    <span><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Background_Maps#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">Spatial Manager Desktop</a></em></span>
  </li>
</ul>

<h2>
</h2>

<p>
  <em>Note: In &#8216;Spatial Manager&#8217; for CAD versions (AutoCAD, BricsCAD and ZWCAD), the Background Maps functionality can be found in the Standard and Professional editions only</em>
</p>