---
id: 4036
title: Little-known options when importing from OpenStreetMap
date: 2017-06-06T13:10:59+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=4036
permalink: /little-known-options-when-importing-from-openstreetmap/
image: /images/blog/2017/06/SPM-OSM-Options85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Import
  - OpenStreetMap
  - Thematics
---
<p>
  <span lang="en"><span lang="en"><span lang="en" tabindex="-1">The project OpenStreetMap is considered a prominent example of volunteered geographic information and has become the &#8220;Wikipedia&#8221; of spatial and territorial information. It gives you free access to tons of geo-spatial data, and &#8216;Spatial Manager&#8217; allows you to import it to Maps (Desktop) and drawings of Maps (AutoCAD and BricsCAD) in a filtered and controlled way</span></span></span>
</p>

<!--more-->

<h2>
</h2>

<div>
  <a href="/images/blog/2017/06/SPM-Import-OSM-options.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/06/SPM-Import-OSM-options-1024x576.png" alt="Importing from OpenStreetMap in order to create or add information to maps" width="625" height="352" srcset="/images/blog/2017/06/SPM-Import-OSM-options-1024x576.png 1024w, /images/blog/2017/06/SPM-Import-OSM-options-300x169.png 300w, /images/blog/2017/06/SPM-Import-OSM-options-768x432.png 768w, /images/blog/2017/06/SPM-Import-OSM-options-624x351.png 624w, /images/blog/2017/06/SPM-Import-OSM-options.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Importing from OpenStreetMap in order to create or add information to maps
  </p>
</div>

<h2>
</h2>

<h2>
  <strong>Related videos: </strong><span><a href="https://youtu.be/3hI0ZDiYI4Q" target="_blank" rel="nofollow">AutoCAD</a> / <a href="https://youtu.be/LEAQlVPZsQ4" target="_blank" rel="nofollow">BricsCAD</a> / <a href="https://youtu.be/TeDGZSXEkaQ" target="_blank" rel="nofollow">Desktop</a></span>
</h2>

<h2>
</h2>

<p>
  <span lang="en" tabindex="-1">As you well know, uncontrolled power does not provide good results in any discipline. The valuable OpenStreetMap information can become a pile of useless data if you are not able to specify <strong>what you want to and how you want it</strong></span>
</p>

<p>
  Besides the query possibilities available in the data source where you are exporting the OSM or PBF files, for example layer filtering in &#8216;OpenStreetMap.org&#8217; website, the &#8216;OpenStreetMap&#8217; data provider in &#8216;Spatial Manager&#8217; includes a set of little-know parameters that allows you to greatly <strong>enhance the data that you can extract from any OSM or PBF file</strong>
</p>

<h2>
</h2>

<div>
  <a href="/images/blog/2017/06/OpenStreeMap-import-parameters-Spatial-Manager.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/06/OpenStreeMap-import-parameters-Spatial-Manager.png" alt="OpenStreeMap import parameters (Spatial Manager data provider)" width="553" height="643" srcset="/images/blog/2017/06/OpenStreeMap-import-parameters-Spatial-Manager.png 553w, /images/blog/2017/06/OpenStreeMap-import-parameters-Spatial-Manager-258x300.png 258w" sizes="(max-width: 553px) 100vw, 553px" /></a>
  
  <p>
    OpenStreeMap import parameters (Spatial Manager data provider)
  </p>
</div>

<h2>
</h2>

<li>
  In the upper area of the &#8216;OpenStreetMap&#8217; parameters window you can find the <strong>structure (up to three levels) </strong>of the &#8216;OpenStreetMap&#8217; community agreed feature types, so that you can select which standard elements you want to import and which ones you do not
</li>
<li>
  As you can see in the above linked videos, one of the most practical parameters allows you <strong>to create a new data field for the imported elements (OSM_TYPE) that will include the feature type </strong>according to the said data structure. As expected, up to three optional levels in the structure can combine the data as &#8220;Group1&#8221;, &#8220;Group1.Group2&#8221;, etc. <ul>
    <li>
      <span lang="en" tabindex="-1">When using this option you can easily <strong>separate or discriminate</strong> layers of data or generate thematic maps quickly</span>
    </li>
  </ul>
</li>

<li>
  By applying a second choice, you can also add new<strong> data fields for the version attributes</strong> (version, timestamp, etc.)
</li>
<li>
  For the imported polygonal areas you can select if they will be considered as open (Polylines) or closed (Polygons) elements<strong> only when the &#8216;area&#8217; tag is set</strong>
</li>
<li>
  If you want a data structure in your Map (or drawing of the Map) that represents the data as &#8220;Field=Value&#8221;, you can opt to <strong>&#8220;merge&#8221; data fields names and values</strong>, which will result in new data fields named &#8220;Field_0&#8221;, &#8220;Field_1&#8221;, etc., whose content for each field will be the original field name, the equal sign and the field value
</li>
<li>
  And last but not at least, you have two exclusive options to <em>drastically reduce the number of data fields </em>included in the imported elements, since<span lang="en" tabindex="-1"> many of them will usually be null or they may have very little or no interest</span> <ul>
    <li>
      First, you can set the <strong>limit number of data fields</strong> for every element. Only the first specified data fields will be imported
    </li>
    <li>
      Alternatively, but not both, you can apply the option to define the <strong>names of the fields that must be imported</strong>
    </li>
  </ul>
</li>

<h2>
</h2>

<p>
  On a few<span><strong> <a href="http://www.spatialmanager.com/tag/openstreetmap/" target="_blank" rel="nofollow"><span>entries in this Blog</span></a> </strong></span>you can learn more about how to take advantage of the OpenStreetMap information (vector features or image maps) when using &#8216;Spatial Manager&#8217;
</p>