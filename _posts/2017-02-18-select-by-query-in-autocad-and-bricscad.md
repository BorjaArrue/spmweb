---
id: 3796
title: Select by query in AutoCAD and BricsCAD
date: 2017-02-18T11:22:53+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=3796
permalink: /select-by-query-in-autocad-and-bricscad/
image: /images/blog/2017/02/Query-DWG-85.png
categories:
  - CAD L2 (Medium)
tags:
  - Alphanumeric data
  - 'Queries &amp; Filters'
---
<p>
  <span lang="en">In order to increasingly add spatial or territorial analysis tools to the CAD applications, &#8216;Spatial Manager&#8217; now includes the functionality to select graphic objects based on their alphanumeric data. The easy-to-use but powerful technology already used in Desktop has been reprogrammed in AutoCAD and BricsCAD</span>
</p>

<!--more-->

## 

<div>
  <a href="/images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD-1024x567.png" alt="Spatial Manager - Select by query BCAD" width="625" height="346" srcset="/images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD-1024x567.png 1024w, /images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD-300x166.png 300w, /images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD-768x425.png 768w, /images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD-624x346.png 624w, /images/blog/2017/02/Spatial-Manager-Select-by-query-BCAD.png 1136w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    BricsCAD sample
  </p>
</div>

<div>
  <a href="/images/blog/2017/02/Spatial-Manager-Select-by-query.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/02/Spatial-Manager-Select-by-query-1024x576.png" alt="Spatial Manager - Select by query" width="625" height="352" srcset="/images/blog/2017/02/Spatial-Manager-Select-by-query-1024x576.png 1024w, /images/blog/2017/02/Spatial-Manager-Select-by-query-300x169.png 300w, /images/blog/2017/02/Spatial-Manager-Select-by-query-768x432.png 768w, /images/blog/2017/02/Spatial-Manager-Select-by-query-624x351.png 624w, /images/blog/2017/02/Spatial-Manager-Select-by-query.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    AutoCAD sample
  </p>
</div>

## 

<p>
  <strong>Related videos: </strong><a href="https://youtu.be/b-j_AFHF0aY" target="_blank" rel="nofollow">AutoCAD</a> / <a href="https://youtu.be/i9-PqDRcKy4" target="_blank" rel="nofollow">BricsCAD</a>
</p>

<h2>
</h2>

<p>
  <em>Note: some of the command features you can read below may not be included in the videos</em>
</p>

<p>
  The <strong><em>SPMSELECTBYQUERY</em></strong> command allows you to select objects in the drawing <strong>according to the result of a simple or compound data query</strong>, while navigating through an intuitive user interface
</p>

<p>
  <a href="/images/blog/2017/02/SelectByQuery36.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/02/SelectByQuery36.png" alt="SelectByQuery36" width="609" height="434" srcset="/images/blog/2017/02/SelectByQuery36.png 609w, /images/blog/2017/02/SelectByQuery36-300x214.png 300w" sizes="(max-width: 609px) 100vw, 609px" /></a>
</p>

<h2>
</h2>

  * The query can be applied to one data table or to all the data tables defined in the drawing
  * Add at least one condition to create a data query (a condition that stands for &#8220;Property & Comparator & Value&#8221;)
  * When you are defining a compound query, you can add as many conditions as you want to the conditions list 
      * You can select the logical operators &#8220;And&#8221; or &#8220;Or&#8221; when adding new conditions
  * In addition, if there are objects selected when you run the command, you can: 
      * Apply the query to the current selection, and not to the entire drawing, or,
      * Keep the current selection so the new &#8220;query selection&#8221; will be added to the current selection
  * _Notes:_ 
      * _The command keeps the list of query conditions used the last time it was executed_
      * _If there are no results during a query, the command window is shown again and keeps the list of query conditions_
      * _You can remove specific conditions from the list, or you can Clean all the query conditions from the list_

<p>
  Additionally, you may want to use the <strong>SPMSELECTBYTABLE</strong> command as a faster way to select all Objects attached to a specific data table
</p>

<p>
  After running any of the above commands you can use <strong>SPMZOOMTOSELECTION</strong> to Zoom to the selected objects
</p>

<p>
  <a href="/images/blog/2017/02/SelectByCommands.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/02/SelectByCommands.png" alt="SelectByCommands" width="225" height="198" /></a>
</p>

<h2>
</h2>

<p>
  <em>Editions Note: All the “Data Management” functionality as these commands in particular are available in the “Standard” and “Professional” editions only</em>
</p>