---
id: 4804
title: More about dynamic Google Maps in your drawings or Maps
date: 2018-01-04T12:54:47+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=4804
permalink: /more-about-dynamic-google-maps-in-your-drawings-or-maps/
image: /images/blog/2017/12/DWG-G_Maps-pin-85-2.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Background Maps
  - Google Maps
  - Tricks and Tools
---
<p>
  Some weeks ago, another entry in this Blog explained how to configure dynamic Google Maps in &#8216;Spatial Manager&#8217; in order to use them as Background Maps in your drawings (AutoCAD, BricsCAD, ZWCAD) or in your Maps (Desktop). But there are more Google Maps types to show and some other interesting parameters that allow you to customize these Maps<!--more-->
</p>

<h2>
</h2>

* * *

<h2>
  <span><a href="http://cdn.spatialmanager.com/images/blog/2017/12/SPM-More-Google-Maps-ACAD.png" target="_blank" rel="nofollow">AutoCAD</a></span> / <span><a href="http://cdn.spatialmanager.com/images/blog/2018/01/SPM-More-Google-Maps-BCAD.png" target="_blank" rel="nofollow">BricsCAD</a></span> / <span><a href="http://cdn.spatialmanager.com/images/blog/2018/01/SPM-More-Google-Maps-ZCAD.png" target="_blank" rel="nofollow">ZWCAD</a></span> / <span><a href="http://cdn.spatialmanager.com/images/blog/2018/01/SPM-More-Google-Maps-DTOP.png" target="_blank" rel="nofollow">Desktop</a></span>
</h2>

<div>
  <a href="/images/blog/2017/12/SPM-More-Google-Maps-ACAD.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/12/SPM-More-Google-Maps-ACAD-1024x576.png" alt="Multiple Google Maps configured in' Spatial Manager' as User Background Maps" width="625" height="352" srcset="/images/blog/2017/12/SPM-More-Google-Maps-ACAD-1024x576.png 1024w, /images/blog/2017/12/SPM-More-Google-Maps-ACAD-300x169.png 300w, /images/blog/2017/12/SPM-More-Google-Maps-ACAD-768x432.png 768w, /images/blog/2017/12/SPM-More-Google-Maps-ACAD-624x351.png 624w, /images/blog/2017/12/SPM-More-Google-Maps-ACAD.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Multiple Google Maps configured in&#8217; Spatial Manager&#8217; as User Background Maps
  </p>
</div>

&nbsp;

In the previous entry (<a href="http://www.spatialmanager.com/google-maps-in-your-cad-drawings-of-course/" target="_blank" rel="nofollow">Google Maps in your CAD drawings? Of course</a>) you learn how to define User Background Maps for the &#8220;Hybrid&#8221; and &#8220;Standard Roadmap&#8221; Google Maps. The following value list for the parameter &#8220;lyrs&#8221; in the URL is a more **complete set of the available map types** in Google Maps:

## 

  * h = Roads only
  * _m = Standard Roadmap (as seen in the previous entry)_
  * p = Terrain
  * r = Roadmap (alternative version)
  * s = Satellite only
  * t = Terrain only
  * _y = Hybrid (as seen in the previous entry)_

## __

<div>
  <a href="/images/blog/2017/12/SPM-Google-Maps-Parameters.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/12/SPM-Google-Maps-Parameters.png" alt="Google Maps Parameters" width="977" height="443" srcset="/images/blog/2017/12/SPM-Google-Maps-Parameters.png 977w, /images/blog/2017/12/SPM-Google-Maps-Parameters-300x136.png 300w, /images/blog/2017/12/SPM-Google-Maps-Parameters-768x348.png 768w, /images/blog/2017/12/SPM-Google-Maps-Parameters-624x283.png 624w" sizes="(max-width: 977px) 100vw, 977px" /></a>
  
  <p>
    Google Maps Parameters
  </p>
</div>

## More parameters

<li>
  <strong>Available servers</strong>: The Google Maps are accessible from more than one server in order to balance the downloading of data. The following names of the servers can be used to define the Maps URL: <ul>
    <li>
      https://mt.google.com/vt/&#8230;
    </li>
    <li>
      https://mt0.google.com/vt/&#8230;
    </li>
    <li>
      https://mt1.google.com/vt/&#8230;
    </li>
    <li>
      https://mt2.google.com/vt/&#8230;
    </li>
    <li>
      https://mt3.google.com/vt/&#8230;
    </li>
  </ul>
</li>

  1. **Toponymics local language**: You can use the parameter &#8220;hl&#8221; to define the language for the shown Map. If available, the place names on the Map will appear in the selected language 
    <li>
      Take a look at the next sample image to check how the Map can change from English language (hl=en) to Polish language (hl=pl)
    </li>
    <li>
      The valid values for the language parameter fit the <span><a href="https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes" target="_blank" rel="nofollow">&#8220;standard two-characters ISO&#8221;</a></span>: &#8220;en&#8221; for English, &#8220;fr&#8221; for French, etc.
    </li>

## 

<div>
  <a href="/images/blog/2017/12/SPM-Google-Maps-hl-en-and-pl.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/12/SPM-Google-Maps-hl-en-and-pl.png" alt="Google Maps Language parameter" width="800" height="985" srcset="/images/blog/2017/12/SPM-Google-Maps-hl-en-and-pl.png 800w, /images/blog/2017/12/SPM-Google-Maps-hl-en-and-pl-244x300.png 244w, /images/blog/2017/12/SPM-Google-Maps-hl-en-and-pl-768x946.png 768w, /images/blog/2017/12/SPM-Google-Maps-hl-en-and-pl-624x768.png 624w" sizes="(max-width: 800px) 100vw, 800px" /></a>
  
  <p>
    Google Maps Language parameter
  </p>
</div>

## Transparent Maps

<p>
  Since &#8216;Spatial Manager&#8217; supports Transparent Background Maps, through the transparent areas you will<strong> see the background color of the drawings and maps or any background element</strong>, such as grids, etc.. Check this feature when configuring and showing the Google &#8220;Roads only&#8221; Map:
</p>

## 

https://mt1.google.com/vt/<span><strong>lyrs=h</strong></span>&hl=en&x={x}&y={y}&z={level}

## 

<div>
  <a href="/images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample-1024x521.png" alt="Spatial Manager Transparent Maps (Google Maps-Road only sample)" width="625" height="318" srcset="/images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample-1024x521.png 1024w, /images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample-300x153.png 300w, /images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample-768x391.png 768w, /images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample-624x318.png 624w, /images/blog/2017/12/SPM-Transparent-Maps-Google-Maps-Road-only-sample.png 1061w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Spatial Manager Transparent Maps (Google Maps-Road only sample)
  </p>
</div>

## 

* * *

<p>
  If you want to learn more about the User Dynamic Background Maps, please review the following technical resources:
</p>

<h2>
</h2>

<span><em><a href="http://www.spatialmanager.com/tag/background-maps/" target="_blank" rel="nofollow">· Blog posts</a></em></span>

## 

Technical Wikis:

## 

<p>
  <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">· Spatial Manager for AutoCAD</a></em><br /> <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow"><em>· Spatial Manager for BricsCAD<br /> </em></a><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">· Spatial Manager for ZWCAD<br /> </a><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Background_Maps#Can_I_configure_my_own_Web_Map_Services.3F" target="_blank" rel="nofollow">· Spatial Manager Desktop</a></em>
</p>