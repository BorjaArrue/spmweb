---
published: true
title: 'Enhanced ASCII data provider (CSV, TXT, ASC, XYZ, &#8230;)'
date: 2017-10-16T09:21:17+00:00
author: admin
layout: old-post
permalink: /enhanced_ascii_data_provider_v4/
image: /images/blog/2017/10/ASCII-Points-85.png
categories:
  - CAD L1 (Basic)
  - Desktop L1 (Basic)
tags:
  - ASCII
  - Import
  - Providers
---
<p>
  The ASCII data files (often named “Comma-separated values” CSV), are one of the most common types of files to store Points tabular data. They are plain-text ASCII files, without binary numbers or any other data type that has to be interpreted<!--more-->
</p>

<h2>
  Related videos: <span><span><a href="https://youtu.be/EJG26apAFM4?rel=0" target="_blank" rel="nofollow">Desktop</a></span></span> / <span><span><a href="https://youtu.be/IIYQLKIuuj0?rel=0" target="_blank" rel="nofollow">AutoCAD</a></span></span> / <span><span><a href="https://youtu.be/G-y0Reu6sWs?rel=0" target="_blank" rel="nofollow">BricsCAD</a></span></span>
</h2>

* * *

<p>
  Every line in the file corresponds to a <strong>record</strong> of a data table and every text or number between two delimiter characters in a line corresponds to a <strong>field</strong> in this record. Various characters may be used as <strong>delimiter</strong> characters and the most commonly used are the comma, the tab, the space character or the semicolon
</p>

<div>
  <a href="/images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2-1024x576.png" alt="Importing Points from a CSV file" width="625" height="352" srcset="/images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2-1024x576.png 1024w, /images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2-300x169.png 300w, /images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2-768x432.png 768w, /images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2-624x351.png 624w, /images/blog/2017/10/New-Spatial-Manager-ASCII-Provider-2.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Importing Points from a CSV file
  </p>
</div>

<p>
  The file extensions used for these type of files are <strong>CSV, XYZ, TXT, ASC</strong>, and some others, and their content may fit standard formats (XYZ, XY Description, PNEZD &#8211; GPS, Code XY. etc.), although the format may also be outside these standards
</p>

<h2>
  Enhanced data provider
</h2>

<p>
  The &#8220;Enhanced ASCII data provider&#8221; <em>(included in the v.4 of the applications)</em> adds the option to work with <strong>&#8220;Custom&#8221;</strong> format files, in which some data fields <em>(2 or 3)</em> are for the coordinate values <em>(X/Y/Z)</em> and the rest of the fields include other data <em>(please take a look to the above image)</em>
</p>

<p>
  As you can see in the related videos, the first line in the file may include the <strong>field names</strong>. In this case, the selection of the coordinate fields may be automatic because the application looks for names such as <em>X, LON, LONGITUDE, Y, LAT, LATITUDE, Z/H (case insensitive)</em>
</p>

<p>
  Please, go to the Wiki if you want to learn more about Loading <em>(Desktop)</em> or Importing <em>(AutoCAD/BricsCAD)</em> spatial data:
</p>

<p>
  · <span><span><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop™_-_FAQs:_Import_and_export" target="_blank" rel="nofollow">Spatial Manager Desktop</a></em></span></span><br /> · <span><span><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for AutoCAD</a></em></span></span><br /> · <span><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></em></span>
</p>