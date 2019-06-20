---
published: true
title: Map servers sub-domains
date: 2018-09-06T09:52:31+00:00
author: admin
layout: old-post
permalink: /map_servers_sub-domains/
image: /images/blog/2018/09/SPMMDomain85-2.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Background Maps
  - Google Maps
---
<p>
  Some image map servers provide multi-domain or sub-domain structures in order to optimize data downloading.  Load balancing improves workload distribution across multiple computing resources and aims to optimize the use of resources, maximize performance and minimize response time. From v.4.2.1, &#8216;Spatial Manager&#8217; applications allow configuring access to multi-domain or sub-domain map servers
</p>

<p>
  <!--more-->
</p>

<div>
  <a href="/images/blog/2018/09/SPM-Severs-Multi-domain.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/09/SPM-Severs-Multi-domain-1024x580.png" alt="Sub-domain map servers setup in 'Spatial Manager'" width="625" height="354" srcset="/images/blog/2018/09/SPM-Severs-Multi-domain-1024x580.png 1024w, /images/blog/2018/09/SPM-Severs-Multi-domain-300x170.png 300w, /images/blog/2018/09/SPM-Severs-Multi-domain-768x435.png 768w, /images/blog/2018/09/SPM-Severs-Multi-domain-624x354.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Sub-domain map servers setup in &#8216;Spatial Manager&#8217;
  </p>
</div>

<h2></h2>
<p>
  One of the essential settings for configuring user dynamic Background Maps in &#8216;Spatial Manager&#8217; is the <strong>URL of the map server</strong>. When typing this parameter in the User Map configuration window for the map server you are configuring, just enter the beginnings of the sub-domain names <strong>between curly brackets { } and separated by commas</strong>
</p>

<h2>
</h2>

<p>
  An example of sub-domains is the structure used in the <strong>Google Maps</strong> <a href="https://en.wikipedia.org/wiki/Tile_Map_Service" target="_blank" rel="nofollow"><span><em>XYZ/TMS</em></span></a> tile map service. This service features the sub-domains:
</p>

<h2>
</h2>

<div>
  <em>mt.google.com</em>
</div>

<div>
  <em>mt0.google.com</em>
</div>

<div>
  <em>mt1.google.com</em>
</div>

<div>
  <em>Etc.</em>
</div>

<div>
</div>

<h2>
</h2>

<p>
  In previous versions of the application you had to choose one of the sub-domains to define the URL of the service but, from version 4.2.1 and as you can see if you click on the image above, you can <strong>configure multi-domain access</strong> through a composite URL:
</p>

<h2>
</h2>

https://**{mt,mt0,mt1,mt2,mt3}**.google.com/&#8230;

<h2>
</h2>

<p>
  In this way, when the application demands the download of map images from the service, it will be <strong>the service itself that balances the requests</strong> to the different sub-domains in order to optimize the download times
</p>

<h2>
</h2>

Read more about other **parameters in the Google Maps settings** in this other <a href="/more-about-dynamic-google-maps-in-your-drawings-or-maps/" target="_blank" rel="nofollow"><span><em>Blog entry</em></span></a>

<h2></h2>
&nbsp;

<h2></h2>
<p>
  To learn more about <b>how to configure user dynamic Background Maps</b> in &#8216;Spatial Manager&#8217;, take a look at the following articles in the products technical Wikis:
</p>

<h2>
</h2>

<ul>
  <li>
    <span><em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">Spatial Manager for AutoCAD</a></span></em></span>
  </li>
  <li>
    <span><em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span></em></span>
  </li>
  <li>
    <span><em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span></em></span>
  </li>
  <li>
    <span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Background_Maps#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager Desktop</em></span></a></span>
  </li>
</ul>