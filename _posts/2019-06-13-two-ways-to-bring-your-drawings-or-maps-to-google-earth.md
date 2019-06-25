---
published: true
title: Two ways to bring your drawings or maps to Google Earth
date: 2019-06-13T18:22:42+00:00
author: admin
layout: old-post
permalink: /two-ways-to-bring-your-drawings-or-maps-to-google-earth/
image: /images/blog/2019/06/DwgToGEarth85.png
big_image: /images/blog/2019/06/ExportKML.png
categories:
  - CAD L1 (Basic)
  - Desktop L1 (Basic)
tags:
  - Export
  - Google Earth (KML)
---
<p>
  Google Earth is one of the most popular platforms for 2D and 3D visualization of spatial and geographic information, not only because it is free and very accessible to any non-expert user, but also because of the included tools and the frequency of updating the maps. &#8216;Spatial Manager&#8217; provides you with two powerful tools to bring your drawings or maps to Google Earth
</p>

<p>
  <!--more-->
</p>

<h2>
  Related videos: <a href="https://youtu.be/f32m8qwuDjI?rel=0" target="_blank" rel="nofollow"><span><span>AutoCAD</span></span></a> / <a href="https://youtu.be/7-Yewz6GjRc?rel=0" target="_blank" rel="nofollow"><span><span>BricsCAD</span></span></a> / <a href="https://youtu.be/Btku7AEBl-M?rel=0" target="_blank" rel="nofollow"><span><span>ZWCAD</span></span></a> / <a href="https://youtu.be/juOZMSXldcA?rel=0" target="_blank" rel="nofollow"><span>Desktop</span></a>
</h2>

<h2>
  <span>Option 1</span>: Publishing to Google Earth
</h2>

<p>
  The first &#8216;Spatial Manager&#8217; function that allows you to create a <span><em><a href="https://en.wikipedia.org/wiki/Keyhole_Markup_Language" target="_blank" rel="nofollow">KML/KMZ</a></em></span> file from your drawing or map is <strong>&#8220;Export to Google Earth&#8221;</strong> (or SPMCREATEKML command in the CAD versions)
</p>

<p>
  This tool, very immediate and intuitive, will let you select objects, a Layer or the whole drawing/map and define a few more options to generate a <strong>&#8220;cloned&#8221; file that can be opened directly in Google Earth</strong> at the end of the process. All point type, linear, polygonal or even raster (<span><em><a href="/exporting-images-to-google-earth-too/" target="_blank" rel="nofollow">only CAD versions</a></em></span>) type objects included in the selection set will be <strong>converted to their equivalents in the KML file</strong>
</p>

<p>
  The properties of the original exported objects (Color, Line weight, Transparency, etc.) <strong>will be preserved as closely as possible</strong>, and the attached data will be exported as alphanumeric data that can be displayed and accessed in Google Earth. The original Layers structure is &#8220;cloned&#8221; also and <strong>sub-layers for the different object types</strong> in each Layer are automatically created, allowing to easily deactivate in Google Earth fillings, contour polygons, raster images, etc.
</p>

<p>
  You can <strong>send this file to any user or partner who wants to review you drawing or map in Google Earth</strong>, and he does not need to install any special viewer, in addition to seeing the status of your project or work <strong>in 3D and its proper location</strong>
</p>

<p>
  In the <span>first half of the above videos</span> you can check the functionality and results of this option. Take a look at them
</p>

<div id="attachment_6636">
  <a href="/images/blog/2019/06/CADCreateKML.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/06/CADCreateKML-1024x576.png" alt="'Spatial Manager' Create KML function - Publishing drawings in Google Earth (click to enlarge)" width="625" height="352" srcset="/images/blog/2019/06/CADCreateKML-1024x576.png 1024w, /images/blog/2019/06/CADCreateKML-300x169.png 300w, /images/blog/2019/06/CADCreateKML-768x432.png 768w, /images/blog/2019/06/CADCreateKML-624x351.png 624w, /images/blog/2019/06/CADCreateKML.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; Create KML function &#8211; Publishing drawings in Google Earth (click to enlarge)
  </p>
</div>

<div id="attachment_6638">
  <a href="/images/blog/2019/06/CreateKML.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/06/CreateKML-1024x577.png" alt="Open resulting KML/KMZ in Google Earth (click to enlarge)" width="625" height="352" srcset="/images/blog/2019/06/CreateKML-1024x577.png 1024w, /images/blog/2019/06/CreateKML-300x169.png 300w, /images/blog/2019/06/CreateKML-768x433.png 768w, /images/blog/2019/06/CreateKML-624x351.png 624w, /images/blog/2019/06/CreateKML.png 1266w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Open resulting KML/KMZ in Google Earth (click to enlarge)
  </p>
</div>

<h2>
  <span>Option 2</span>: Exporting objects to KML/KMZ through the wizard
</h2>

<p>
  The second option you can choose in &#8216;Spatial Manager&#8217; is the use of the <strong>general Export Wizard</strong> (SPMEXPORT command in CAD versions), which works in a similar way to export objects from your drawing/map to any spatial file or data container (Shapefile, SDF, GML, PostGIS, SQL Server, etc., in addition to KML/KMZ)
</p>

<p>
  This function is not as direct and intuitive as the previous one but it will allow you to <strong>refine much more the data and properties to be exported and the appearance of the exported objects</strong> in Google Earth. You can choose which data to export from the data tables, add as alphanumeric data drawing properties (in CAD versions, hatches details, lengths or areas, etc.), and define line and fill colors as well as line weights or transparencies in the KML/KMZ file
</p>

<p>
  You can also <strong>define a folder structure</strong> for the outcoming objects (even adding them to an existing KML/KMZ file), or select how to consider the <strong>Z position and altitude</strong> of the resulting objects in Google Earth
</p>

<p>
  The remarks about the potentials of Google Earth and KML/KMZ files that are mentioned in the first option, are equally valid here
</p>

In the <span>second section of the above videos</span> you will see how this wizard works when exporting to KML/KMZ files. Please play them

<div id="attachment_6640">
  <a href="/images/blog/2019/06/CADExportKML.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/06/CADExportKML-1024x576.png" alt="'Spatial Manager' Export (to KML/KMZ) function and parameters - Structured KML/KMZ files (click to enlarge)" width="625" height="352" srcset="/images/blog/2019/06/CADExportKML-1024x576.png 1024w, /images/blog/2019/06/CADExportKML-300x169.png 300w, /images/blog/2019/06/CADExportKML-768x432.png 768w, /images/blog/2019/06/CADExportKML-624x351.png 624w, /images/blog/2019/06/CADExportKML.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; Export (to KML/KMZ) function and parameters &#8211; Structured KML/KMZ files (click to enlarge)
  </p>
</div>

<div id="attachment_6641">
  <a href="/images/blog/2019/06/ExportKML.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/06/ExportKML-1024x577.png" alt="Open resulting Exported KML/KMZ in Google Earth (click to enlarge)" width="625" height="352" srcset="/images/blog/2019/06/ExportKML-1024x577.png 1024w, /images/blog/2019/06/ExportKML-300x169.png 300w, /images/blog/2019/06/ExportKML-768x433.png 768w, /images/blog/2019/06/ExportKML-624x351.png 624w, /images/blog/2019/06/ExportKML.png 1266w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Open resulting Exported KML/KMZ in Google Earth (click to enlarge)
  </p>
</div>

<p>
  <em>Learn more about publishing to Google Earth and/or Exporting to KML/KMZ in &#8216;Spatial Manager&#8217;:</em>
</p>

<ul>
  <li>
    <span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Export_(%22Professional%22_edition_only)" target="_blank" rel="nofollow"><span><em>Spatial Manager for AutoCAD</em></span></a></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Export_(%22Professional%22_edition_only)" target="_blank" rel="nofollow"><span><em>Spatial Manager for BricsCAD</em></span></a></span></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD_-_FAQs:_Export_(%22Professional%22_edition_only)" target="_blank" rel="nofollow"><span><em>Spatial Manager for ZWCAD</em></span></a></span></span>
  </li>
  <li>
    <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop™_-_FAQs:_Import_and_export" target="_blank" rel="nofollow"><span><em>Spatial Manager Desktop</em></span></a>
  </li>
</ul>

<p>
  <em>Notes:</em>
</p>

<li>
  <em>In &#8216;Spatial Manager&#8217; for CAD versions, &#8216;Publishing to Google Earth&#8217; functionality is available in Standard and Professional editions. Full Exporting is available in Professional Edition only</em>
</li>
<li>
  <em>In &#8216;Spatial Manager Desktop&#8217;, &#8216;Publishing to Google Earth&#8217; functionality is available in Standard and Professional editions. Exporting functionality is available in all Editions (Basic, Standard and Professional)</em>
</li>
