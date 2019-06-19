---
id: 1133
title: 'Exporting Points (Data &#038; Coordinates)'
date: 2014-05-14T14:57:46+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=1133
permalink: /exporting-points-data-coordinates/
image: /images/blog/2014/05/map-places853.png
categories:
  - Desktop L1 (Basic)
tags:
  - Alphanumeric data
  - Data conversion
  - Excel
---
You often need to export Point features data from spatial data management applications to commonly used applications such as MS Excel or MS Access, using a format recognized by these applications<!--more-->

Spatial Manager Desktop™ allows you to export the alphanumeric data of any set of Features from the Data grid by setting several options, but, if you also want to export the coordinates of the Point Features, it is necessary to **perform a double operation**

To do so, after you export the alphanumeric data, **you can also export the coordinates of the Point Features**, using a text format (<a title="CSV Wiki" href="https://en.wikipedia.org/wiki/Comma-separated_values" target="_blank" rel="nofollow">XYZ, CSV, etc</a>.), and compose the two sets of data using any application that can read them, such as <a title="MS Excel product page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS Excel</a>. This functionality is possible because the export order of the alphanumeric data from the Data grid and the export order of the Features from Spatial Manager Desktop™ **is the same**, as long as the ordering of the elements <span>does not change</span> in the data grid between the two processes

In the following example, we will get a table which includes the data of the cafes, bars and restaurants in a city, along with their coordinates, using a latitude and longitude system and also a projected system suitable to be used in the geographical area of the city

After extracting the Point Features relevant for the establishments from a data source such as <a title="OpenStreetMap Wiki" href="https://en.wikipedia.org/wiki/OpenStreetMap" target="_blank" rel="nofollow">OpenStreetMap</a>, we run the procedures explained in the previous paragraphs

Please, watch the video:
