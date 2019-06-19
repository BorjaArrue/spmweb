---
id: 306
title: Export tables from PostGIS or SQL Server Spatial
date: 2013-11-27T15:11:24+00:00
author: admin
layout: old-post
guid: http://berlin.opencartis.com/wordpress/?p=306
permalink: /export-tables-from-postgis-or-sql-server-spatial/
image: /images/blog/2013/11/Blog1-85px4.png
categories:
  - Desktop L2 (Medium)
tags:
  - Corporate
  - Data sources
  - PostGIS
  - SQL Spatial
---
If you work in a corporate GIS environment, it is likely that you access spatial data stored in geospatial data servers such as PostGIS, SQL Server Spatial, etc.<!--more-->

In this case, it is also very likely that you often have the need to **export information from these servers and generate GIS files, such as SHP, TAB, MIF, KML or others**, in order to share them with other users or to use as information compatible with many GIS applications, which cannot directly access your original data tables

Spatial Manager Desktop™ includes the technology and tools needed to keep these export processes simple and intuitive:

  * First common problem to solve: the **access to the data tables into the servers is tedious**. Depending on the type of server, you need to enter a lot of connection parameters which are not easy to remember, such as the server name, the user, the password, the connection port, the name of the database, etc. 
      * Spatial Manager Desktop™ brings the concept of **&#8220;User Data Source&#8221;** (UDS), which allows you to store, inside your user settings, all the access parameters for the servers that you regularly connect to, by defining all the parameters once
  * Second common problem to solve: **perhaps the process of extraction of the tables from the servers must be executed on a regular basis** and sometimes these processes require the introduction of several more or less complex parameters, such as the destination file type, its location and its own parameters, perform a coordinate transformation between the origin and target, etc. 
      * Spatial Manager Desktop™ also brings **the concept of &#8220;Task&#8221;, that allows you to store all needed operations and parameters for any import or export process** of spatial information. Once all necessary operations and parameters are saved as a Task, you can then run it from the Task Manager whenever you need. In addition, the application also allows you to run these Tasks from the operating system Command window and use wildcard characters for the name of the Tasks to be executed. This feature will allow you to program simple but powerful batch processes for the execution of multiple Tasks

In this video, you can see, as an example, the extractions of two tables from a <a title="PostGIS website" href="http://postgis.net/" target="_blank" rel="nofollow">PostGIS</a> database schema and its conversion to SHP files, performing a coordinate transformation between the source data and the target data. To illustrate the process in the example, **we will define two Tasks, which are subsequently executed inside the application itself and from the operating system Command window**

Please, watch the video:

<center>
  <br />
</center>