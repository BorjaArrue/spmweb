---
published: true
title: Improve performance when importing from OpenStreetMap
date: 2017-09-07T13:42:55+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=4176
permalink: /improving_performance_when_importing_from_openstreetmap/
image: /images/blog/2017/08/Speed-UpOSM85.jpg
categories:
  - CAD L2 (Medium)
tags:
  - Import
  - OpenStreetMap
  - Tricks and Tools
---
<p>
  <span lang="en"><span lang="en"><span lang="en" tabindex="-1">As was said in another post from this Blog, the display of the Import parameters window is often delayed when importing some &#8220;heavy&#8221; data sources in AutoCAD or BricsCAD</span></span></span><!--more-->
</p>

<p>
  <strong>OpenStreetMap</strong> stands out as one of the ‘Spatial Manager’ data providers that is commonly used for the massive import of spatial data
</p>

<div>
  <a href="/images/blog/2017/09/SPMImport-Frankfurt-OSM.jpg" target="_blank" rel="nofollow"><img src="/images/blog/2017/09/SPMImport-Frankfurt-OSM-300x169.jpg" alt="Importing from OpenStreetMap to AutoCAD or BricsCAD" width="625" height="352" srcset="/images/blog/2017/09/SPMImport-Frankfurt-OSM-300x169.jpg 300w, /images/blog/2017/09/SPMImport-Frankfurt-OSM-768x432.jpg 768w, /images/blog/2017/09/SPMImport-Frankfurt-OSM-624x351.jpg 624w, /images/blog/2017/09/SPMImport-Frankfurt-OSM.jpg 960w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Importing from OpenStreetMap to AutoCAD or BricsCAD
  </p>
</div>

<h2>
</h2>

<h2>
  <strong>Related videos: </strong><span><a href="https://youtu.be/YulY1kTUdoo" target="_blank" rel="nofollow">AutoCAD</a> / <a href="https://youtu.be/L0mLhuFmTfc" target="_blank" rel="nofollow">BricsCAD</a></span>
</h2>

<h2>
</h2>

<p>
  The delay effect occurs because a preliminary process <strong>that requires the reading of data fields</strong> (not of the data itself) from the table being imported. This process can be quite complex depending on the number of existing fields in the incoming table, which may be very high when importing from OpenStreetMap
</p>

<p>
  <em>Why is it necessary to review the data fields before importing?</em><br /> The user can configure multiple import parameters based on the values of certain fields in the imported table. These parameters can be the Layer, Elevation or Thickness of the imported objects, some parameters for Block insertions when used for point elements, the Label text when labeling the objects, and more. &#8216;Spatial Manager&#8217; firstly needs to review the data fields to show the user the different options available for selecting these parameters
</p>

<p>
  <em>What can be done to improve the overall importing process?</em><br /> If you do not need to use these parameters, it is not necessary to waste time (sometimes it can be a long time) in the process of reviewing the data fields in the OpenStreetMap table to import. &#8216;Spatial Manager&#8217; has a <strong>“Skip” Button</strong> that allows you to quickly cancel fields reading and go directly to the import parameters window, which will accelerate the global process when you do not want to define any parameter based on the field values
</p>

<div>
  <a href="/images/blog/2017/09/Reading-fields-OSM-SPM.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/09/Reading-fields-OSM-SPM.png" alt="Reading OSM fields" width="553" height="643" srcset="/images/blog/2017/09/Reading-fields-OSM-SPM.png 553w, /images/blog/2017/09/Reading-fields-OSM-SPM-258x300.png 258w" sizes="(max-width: 553px) 100vw, 553px" /></a>
  
  <p>
    Reading OSM fields
  </p>
</div>

<p>
  You can choose to use this Button or not in your own tests or projects. Or you may want to use it first in order to get a quick preview of the OpenStreetMap data in your drawing, and then running the definitive importing process where you will let &#8216;Spatial Manager&#8217; perform the full importing tasks
</p>

<p>
  You can also <strong>take advantage of the advanced Field options</strong> of the OpenStreetMap data provider. Please read this <a href="http://www.spatialmanager.com/little-known-options-when-importing-from-openstreetmap/" target="_blank" rel="nofollow"><em>Blog post</em></a> to find out how
</p>

<p>
  Learn more about Importing with &#8216;Spatial Manager&#8217; in the Technical Wiki of <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow">&#8216;Spatial Manager for AutoCAD&#8217;</a></em> or <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow">&#8216;Spatial Manager for BricsCAD&#8217;</a></em>
</p>