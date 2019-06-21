---
published: true
title: Import directly to PostGIS databases
date: 2014-02-25T16:02:05+00:00
author: admin
layout: old-post
permalink: /import-directly-postgis-databases/
image: /images/blog/2014/02/logo-PostGIS-85.png
categories:
  - Desktop L2 (Medium)
tags:
  - Data conversion
  - Import
  - PostGIS
---
Many Spatial Manager Desktop™ users are familiar with the large number of options included in the application to export spatial data, but few users are aware of the possibility to directly Import Tables to a container, such as a Schema of a PostGIS database<!--more-->

Using Spatial Manager Desktop™, any Provider that brings access to spatial data files (such as SDF or SQLite) or spatial databases (such as <a title="Microsoft SQL Server website" href="http://www.microsoft.com/en-us/sqlserver/default.aspx" target="_blank" rel="nofollow">SQL Server Spatial</a> or <a title="PostGIS website" href="http://postgis.net/" target="_blank" rel="nofollow">PostGIS</a>), which include Schemas inside their internal structure, **allows you to directly Import tables** to any of these Schemas. To do it, simply right-click on the corresponding access in the Data Sources panel of the application, and select the &#8220;Import&#8221; function

When working in <a title="PostGIS website" href="http://postgis.net/" target="_blank" rel="nofollow">PostGIS</a> database servers, you must first create a new User Data Source (UDS) to connect and define the connection parameters of the server to access its spatial databases already containing their respective Schemas

**The Import processes are very similar to the export processes** and may include the same options for the copy and the transformations. Only one difference: when executing Import processes the target of the data is known and now it is necessary to define the source data and its connection parameters and options. As in any Export process, **you can  immediately run the Import Task and/or save it** while defined

_Note: to learn more about UDSs and Tasks, see the post <a title="Export tables from PostGIS or SQL Server Spatial" href="/export-tables-from-postgis-or-sql-server-spatial/" target="_blank" rel="nofollow">Export tables from PostGIS or SQL Server Spatial</a>_

In this example, several spatial data Tables are imported from different sources to the same Schema of a PostGIS database server to build spatial data information about a city

Please, watch the video:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/2jK6XD6yELQ" allowfullscreen></iframe>
</div>