---
id: 2553
title: Speed up when importing heavy sources
date: 2015-08-13T10:11:07+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=2553
permalink: /speed-up-when-importing-heavy-sources/
image: /images/blog/2015/06/Spatial-Manager-AutoCAD-BricsCAD-Speed-Up-3-85.png
categories:
  - CAD L2 (Medium)
tags:
  - Import
  - Tricks and Tools
---
Sometimes the display of the import parameters window of Spatial Manager™ may be significantly delayed when importing complex information in AutoCAD or BricsCAD

<!--more-->

This is because of a preliminary process which requires the **reading of data fields** (not of the data itself) from the table being imported. This process can be quite complex depending on the selected data provider for importing and the number of existing fields in the incoming table

## Why is it necessary to review the data fields before importing?

The user can configure multiple import parameters based on the values of certain fields in the imported table. These parameters can be the Layer, Elevation or Thickness of the imported objects, some parameters for Block insertions when used for point elements, and more

**Spatial Manager™ needs to review the data fields** to show the user the different options available for selecting these parameters

## Speeding up!

If you do not need to define these parameters, it is not necessary to waste time (sometimes it can be a long time) in the process of reviewing the data fields in the table to import

Spatial Manager™ has a **&#8220;Skip&#8221; button** to quickly cancel reading fields and go directly to the import parameters window which will accelerate the global process when you do not want to define any parameter based on the field values

<p>
  <a href="/images/blog/2015/06/Spatial-Manager-AutoCAD-BricsCAD-Skip-Button.png" target="_blank" rel="nofollow"><img src="/images/blog/2015/06/Spatial-Manager-AutoCAD-BricsCAD-Skip-Button.png" alt="Spatial Manager AutoCAD-BricsCAD Skip Button" width="567" height="574" srcset="/images/blog/2015/06/Spatial-Manager-AutoCAD-BricsCAD-Skip-Button.png 567w, /images/blog/2015/06/Spatial-Manager-AutoCAD-BricsCAD-Skip-Button-296x300.png 296w" sizes="(max-width: 567px) 100vw, 567px" /></a>
</p>

## Please, watch the videos:

### AutoCAD sample



### BricsCAD sample