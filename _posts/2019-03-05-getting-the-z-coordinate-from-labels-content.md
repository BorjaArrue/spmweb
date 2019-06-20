---
published: true
title: Getting the Z-coordinate from label contents
date: 2019-03-05T21:22:54+00:00
author: admin
layout: old-post
permalink: /getting-the-z-coordinate-from-labels-content/
image: /images/blog/2019/03/SurveyPts85.png
categories:
  - CAD L2 (Medium)
tags:
  - 3D
  - Excel
  - Export
  - Tricks and Tools
---
<p>
  While &#8216;Spatial Manager&#8217; allows you to handle any type of 3D information and therefore export 3D-point tables from your drawing or map, there are times when the points Z-coordinate information is in a label form. Here you will find a little trick to get the XYZ coordinate tables in these cases
</p>

<p>
  <!--more-->
</p>

<h2>
  Related videos: <a href="https://youtu.be/Q7o7Kv8W8IA?rel=0" target="_blank" rel="nofollow"><span><span>AutoCAD</span></span></a> / <a href="https://youtu.be/0LN-QIJEp3k?rel=0" target="_blank" rel="nofollow"><span><span>BricsCAD</span></span></a> / <a href="https://youtu.be/SE1OxTAjNw8?rel=0" target="_blank" rel="nofollow"><span><span>ZWCAD</span></span></a>
</h2>

<div>
  <a href="/images/blog/2019/03/SPMZText.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/03/SPMZText-1024x577.png" alt="'Spatial Manager' - Exporting Z-Coordinates from labels" width="625" height="352" srcset="/images/blog/2019/03/SPMZText-1024x577.png 1024w, /images/blog/2019/03/SPMZText-300x169.png 300w, /images/blog/2019/03/SPMZText-768x433.png 768w, /images/blog/2019/03/SPMZText-624x351.png 624w, /images/blog/2019/03/SPMZText.png 1266w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; &#8211; Exporting Z-Coordinates from labels
  </p>
</div>

<h2>
</h2>

<p>
  In the above videos you can review a scenario in which a <strong>survey points cloud</strong> is drawn in the XY plane of a drawing (Z=0) and the points<strong> Z-coordinate is labeled</strong> next to the points themselves
</p>

<h2>
</h2>

<p>
  This is a fairly common situation and you will be able to export the labels so that, in addition to the XY coordinates, you will <strong>add the text content</strong> (the Z coordinate) in the same export process
</p>

<h2>
</h2>

<p>
  When the Text Content of text objects is selected as one of the export parameters, a <strong>new &#8220;TxtString&#8221; field will be aggregated</strong> to the output table. In our sample we are exporting to a <span><a href="https://en.wikipedia.org/wiki/Comma-separated_values" target="_blank" rel="nofollow"><em>CSV</em></a></span> format and the resulting table will contain the XY coordinates, the Z-coordinates (that will be 0 for all points), and the Text Strings, which are actually the Z-coordinates. Through a simple edition of this CSV file you can delete the column of the null Z-coordinates and <strong>rename the &#8220;TxtString&#8221; column as &#8220;Z&#8221;</strong>. And voila, here is the points 3D table
</p>

<h2>
</h2>

<p>
  <em>In this example it is assumed that the insertion points of the labels <span>match the survey points themselves</span>, which is quite common. If this is not the case, the displacement of the labels in relation to the points is usually constant, so once all the labels have been selected though the &#8220;Select similar&#8221; command and before exporting, you can Move them that constant distance</em>
</p>

<h2>
</h2>

&nbsp;

<h2>
</h2>

<p>
  <em>Learn more about Export features in &#8216;Spatial Manager&#8217;:</em>
</p>

<h2>
</h2>

<ul>
  <li>
    <span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Export_(%22Professional%22_edition_only)#How_can_I_Export_AutoCAD_objects_as_spatial_features.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager for AutoCAD</em></span></a></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Export_(%22Professional%22_edition_only)#How_can_I_Export_BricsCAD_entities_as_spatial_features.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager for BricsCAD</em></span></a></span></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Export_(%22Professional%22_edition_only)#How_can_I_Export_ZWCAD_entities_as_spatial_features.3F" target="_blank" rel="nofollow"><span><em>Spatial Manager for ZWCAD</em></span></a></span></span>
  </li>
</ul>

<h2>
</h2>

<p>
  <em>Note: The full Export functionality of &#8216;Spatial Manager&#8217; is available in the Professional edition only</em>
</p>