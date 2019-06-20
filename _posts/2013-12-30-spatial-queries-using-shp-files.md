---
published: true
title: Spatial Queries using SHP files
date: 2013-12-30T12:33:11+00:00
author: admin
layout: old-post
guid: http://berlin.opencartis.com/wordpress/?p=410
permalink: /spatial-queries-using-shp-files/
image: /images/blog/2013/12/Spatial-query-85.png
categories:
  - Desktop L1 (Basic)
tags:
  - 'Queries &amp; Filters'
  - Shapefiles (SHP)
  - Spatial queries
---
Within the Spatial Manager Desktop™ functional suite, you can find some advanced functions such as Spatial Queries to solve the search of interferences between Features<!--more-->

**Spatial Queries allows you to locate Features in a Layer that interfere with the selected Features, using a geometric operation**. The list of geometric operations included in this function is the following: Intersects, Touches, Within, Contains, Disjoint, Overlaps and Crosses. Each operation returns individual results depending on the type of the selected Features and the type of the Features that includes the Layer over which the Spatial Query is performed

In this sample, we have three SHP files that, over an area of a municipality, contain respectively a chart of Parcels, a chart of Pipes from the water service and also the locations of the Valves from this service

We must get, first, a **list of all Valves that are located within any Parcel of the municipality**, and then a **list of all PVC Pipes that cross or are within any of the Parcels**

We run **two different Spatial Queries** to get these results. For the first case **we use the &#8220;Within&#8221; operation and latter we use the &#8220;Intersects&#8221; operation**, to create two new layers containing the two sets of Features searched for, considering the imposed conditions. In the second case we **also conduct a Selection Query over the above result to filter only the PVC Pipes**
  
The results of these queries can be **exported from the Data Grid** and can be opened or imported into applications such as Excel, Access and others

Please, watch the video:

<center>
  <br />
</center>