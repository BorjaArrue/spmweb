---
published: true
title: Import from Palette vs using SPMIMPORT
date: 2018-10-23T12:44:05+00:00
author: admin
layout: old-post
permalink: /import_from_palette_vs_using_spmimport/
image: /images/blog/2018/10/SPMIMPORT_vs_PaletteImportIcon.png
categories:
  - CAD L1 (Basic)
tags:
  - Import
  - Tricks and Tools
---
<p>
  The &#8216;Spatial Manager&#8217; main Palette includes many of the most relevant and commonly used functions in the application, such as the importing functions. But in the CAD versions (AutoCAD, BricsCAD or ZWCAD), you also can find direct import commands that can be more comfortable and faster when you don&#8217;t have the Palette open, or when you want to program/chain importing processes
</p>

<p>
  <!--more-->
</p>

<h2>
  Related videos: <a href="https://youtu.be/YCjVBEBvBBk?rel=0" target="_blank" rel="nofollow"><span><span>AutoCAD</span></span></a> / <a href="https://youtu.be/m2IAQ_Z0GWQ?rel=0" target="_blank" rel="nofollow"><span><span>BricsCAD</span></span></a> / <a href="https://youtu.be/-ej742ycJ1Y?rel=0" target="_blank" rel="nofollow"><span><span>ZWCAD</span></span></a>
</h2>

<div>
  <a href="/images/blog/2018/10/SPMIMPORT_vs_PaletteImport.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/10/SPMIMPORT_vs_PaletteImport-1024x576.png" alt="'Spatial Manager' - Import from the application palette or execute SPMIMPORT" width="625" height="352" srcset="/images/blog/2018/10/SPMIMPORT_vs_PaletteImport-1024x576.png 1024w, /images/blog/2018/10/SPMIMPORT_vs_PaletteImport-300x169.png 300w, /images/blog/2018/10/SPMIMPORT_vs_PaletteImport-768x432.png 768w, /images/blog/2018/10/SPMIMPORT_vs_PaletteImport-624x351.png 624w, /images/blog/2018/10/SPMIMPORT_vs_PaletteImport.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; &#8211; Import from the application palette or execute SPMIMPORT
  </p>
</div>

<h2>
</h2>

<h2>
</h2>

<p>
  Using the Palette right-click menus on any data source, you will be able to import objects from the data source with the choice of importing<strong> into the current drawing or into a new drawing</strong>. You will also have other administrative tools and the possibility of importing<strong> the whole content of a folder</strong> through the right-click menu of the folder
</p>

<h2>
</h2>

<p>
  Alternatively, as you can see in the videos above, if you want to import spatial data into the current drawing <strong>without using the Palette</strong>, you can execute the <strong>SPMIMPORT command</strong>, which will access the same data source structure as in the Palette and will launch the import wizard in the same way
</p>

<h2>
</h2>

<p>
  A variant of this command is also available in the <strong>Command Line (-SPMIMPORT)</strong> where the name of the import Task to be executed is specified as a parameter (About Tasks: <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import#What_are_the_Tasks.3F_.28.22Professional.22_edition_only.29" target="_blank" rel="nofollow"><span><em>AutoCAD</em></span></a> / <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import#What_are_the_Tasks.3F_.28.22Professional.22_edition_only.29" target="_blank" rel="nofollow"><span><em>BricsCAD</em></span></a> / <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Import#What_are_the_Tasks.3F_.28.22Professional.22_edition_only.29" target="_blank" rel="nofollow"><span><em>ZWCAD</em></span></a>). Since the command parameter supports <strong>wildcards</strong>, several Tasks whose names match a particular pattern can be executed at once
</p>

<h2>
</h2>

<p>
  By running this command from the Command Line, for example:
</p>

<h2>
</h2>

_-SPMIMPORT Buildings_, will run the saved &#8220;Buildings&#8221; Task
  
_-SPMIMPORT Build*_, will run consecutively all saved Tasks whose names start with &#8220;Build&#8221;

<h2>
</h2>

<p>
  It is also convenient to point out here that <em>-SPMIMPORT</em> can be <strong>executed from within a CAD Script</strong> (<em>*.SCR</em>), which will facilitate the execution of multiple import Tasks, using or not wildcards, when executing the Script. As an example:
</p>

<h2></h2>
_;Script to import Buildings (Areas 22 / 23) and Parcels_
  
_-SPMIMPORT Buildings_Area22_
  
_-SPMIMPORT Buildings_Area23_
  
_-SPMIMPORT Parcels*_

<h2></h2>


<p>
  Learn more about how to import and customize spatial objects and data into your drawings from the <strong>Application Palette</strong>, through the <strong>SPMIMPORT</strong> direct command, or from the Command line and Scripts <strong>(-SPMIMPORT)</strong>:
</p>

<h2>
</h2>

<ul>
  <li>
    <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow"><em><span>Spatial Manager for AutoCAD</span></em></a>
  </li>
  <li>
    <em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span></em>
  </li>
  <li>
    <em><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD_-_FAQs:_Import" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span></em>
  </li>
</ul>