---
published: true
title: Command-line Importing. Scripts
date: 2017-11-02T11:26:36+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=4436
permalink: /command-line_importing_scripts/
image: /images/blog/2017/10/SCR-SPMIMPORT-Logo85.png
categories:
  - CAD L2 (Medium)
tags:
  - Batch processing
  - Import
---
<p>
  From version 4, &#8216;Spatial Manager for AutoCAD/BricsCAD&#8217; includes the command &#8220;-SPMIMPORT&#8221; (notice the hyphen), which is a &#8220;command line&#8221; version of the &#8220;SPMIMPORT&#8221; command designed to allow the executing of Tasks from the command line, Scripts, VBA, LISP, etc.<!--more-->
</p>

<h2>
  Related videos: <span><span><a href="https://youtu.be/8K-MGjy7sAg?rel=0" target="_blank" rel="nofollow">AutoCAD</a></span></span> / <span><span><a href="https://youtu.be/oS-UyRPMzQ8?rel=0" target="_blank" rel="nofollow">BricsCAD</a></span></span>
</h2>

* * *

<p>
  The <span><em>Tasks</em></span> technology allows <em>&#8216;Spatial Manager&#8217;</em> users <strong>to save all the steps and configuration</strong> needed to perform a specific Importing process in order to comfortably repeat this process as many times as they want to do it
</p>

<p>
  The result is very useful when there are processes of importing tables from files, servers or data stores into your drawings, which are <strong>executed on a regular basis</strong>. Especially when these processes require the introduction of several more or less complex parameters of the data source/target and of the importing process itself, defining a coordinate transformation between the origin and target (drawing), etc.
</p>

<div>
  <a href="/images/blog/2017/10/Spatial-Manager-Task-Manager.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/10/Spatial-Manager-Task-Manager.png" alt="Spatial Manager Task Manager" width="349" height="548" srcset="/images/blog/2017/10/Spatial-Manager-Task-Manager.png 349w, /images/blog/2017/10/Spatial-Manager-Task-Manager-191x300.png 191w" sizes="(max-width: 349px) 100vw, 349px" /></a>
  
  <p>
    Spatial Manager Task Manager
  </p>
</div>

<p>
  <em>Please, take a look to this <span><span><a href="http://www.spatialmanager.com/may15-new-releases-the-powerful-tasks-technology/" target="_blank" rel="nofollow">Blog post</a></span></span> and this Wiki article (<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import#What_are_the_Tasks.3F_.28.22Professional.22_edition_only.29" target="_blank" rel="nofollow">AutoCAD</a></span>/<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Import#What_are_the_Tasks.3F_.28.22Professional.22_edition_only.29" target="_blank" rel="nofollow">BricsCAD</a></span>) if you want to learn more about &#8220;Tasks&#8221;</em>
</p>

<h2>
  Executing &#8220;Tasks&#8221; from the command-line (-SPMIMPORT <em>TaskName</em>)
</h2>

<p>
  &#8220;-SPMIMPORT&#8221; adds a new dimension to the execution of repetitive processes since it supports <strong>wildcards</strong> in the &#8220;Task name&#8221; parameter. For example, the following command will execute all the Tasks whose name starts with &#8220;RED&#8221;:
</p>

<p>
  <strong><em>-SPMIMPORT RED*</em></strong>
</p>

<p>
  In this way, the following <strong>AutoCAD/BricsCAD Script</strong> will execute all the Tasks covered by the names and wildcards in the first three lines and it will change some properties of the Layer &#8220;LOCAL&#8221; (which may be created automatically in the importing process):
</p>

<p>
  <strong><em>-SPMIMPORT RED*</em></strong><br /> <strong> <em>-SPMIMPORT Loop_E3</em></strong><br /> <strong> <em>-SPMIMPORT KML*</em></strong><br /> <strong> <em>-LAYER LW 0.50 LOCAL<br /> </em></strong>
</p>

<p>
  <em>Note: You can write any Script by means of a simple text editor such as Windows Notepad (save with *.scr extension), and execute them using the command SCRIPT</em>
</p>