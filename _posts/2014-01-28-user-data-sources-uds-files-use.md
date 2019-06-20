---
published: true
title: User Data Sources (UDS) for files. Why use them?
date: 2014-01-28T12:12:23+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=550
permalink: /user-data-sources-uds-files-use/
image: /images/blog/2014/01/59_FMP_file_logo-85.png
categories:
  - CAD L3 (Advanced)
  - Desktop L3 (Advanced)
tags:
  - Data sources
---
User Data Sources (UDS) have been developed inside every product of the Spatial Manager™ suite mainly to access spatial databases and spatial stores, but they can also be used to access spatial data files including their own connection parameters<!--more-->

Access to certain file types when using any Spatial Manager™ product may require some connection parameters. For example, working with an OSM file (OpenStreetMap XML), it is necessary to define which Feature types (agreed with the OpenStreetMap community) you want to include, as well as whether or not to load the version attributes of the Features in the data table, when loading or exporting the file. Similar cases would be KML/KMZ complex files (Google Earth), ASCII point files, etc.

**If you frequently access a file** which requires some connection parameters to load it into a Map, export it or use it as part of any Task definition, **you may be interested in creating a UDS** for this file access, which will also include the connection parameters you choose at the time of defining the new UDS

In these video samples, we create and use a UDS to access an OSM file, and another UDS to access a KML file including subfolders, in Spatial Manager Desktop™ (creating the UDSs of these samples would be similar in Spatial Manager™ for AutoCAD)

Please, watch the video: