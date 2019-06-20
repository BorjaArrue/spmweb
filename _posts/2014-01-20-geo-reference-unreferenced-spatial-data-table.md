---
published: true
title: 'How to geo-reference an &#8216;unreferenced&#8217; spatial Table?'
date: 2014-01-20T11:28:10+00:00
author: admin
layout: old-post
permalink: /geo-reference-unreferenced-spatial-data-table/
image: /images/blog/2014/01/15-min_index-85.png
categories:
  - Desktop L3 (Advanced)
tags:
  - CRS
  - Geo-reference
---
Occasionally you will find some spatial data (SHP files or PostGIS tables, for example) that does not include geo-referencing information, but you know the Coordinate System (CRS) used to define the Features in the Table<!--more-->

If this applies to you, **try to use the Transformation of coordinates in Spatial Manager Desktop™** to get a copy of the Table including its geo-referencing information (CRS)

This is as **simple as running an export (or import) process**, activating the Transformation of coordinates and choosing the same CRS for the source and the target data while you are setting up the parameters of the process

When the Transformation of coordinates operation is running, if you have chosen the same CRS for the source and the target data, the application does not perform any geometric transformation of the Features, and warns you about it, but **the resulting target data includes this CRS as the geo-referencing information of the Table**

Please, watch the video: