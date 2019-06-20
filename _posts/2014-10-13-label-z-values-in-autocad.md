---
published: true
title: Label Z values in AutoCAD
date: 2014-10-13T17:11:47+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=1840
permalink: /label-z-values-in-autocad/
image: /images/blog/2014/10/Label-Z-values-in-AutoCAD-Spatial-Manager.png
categories:
  - CAD L2 (Medium)
tags:
  - Import
  - Labels
  - Tricks and Tools
---
<span>Nearly all</span> <span>data providers</span> included in<span> </span>Spatial <span>Manager™ for</span> <span>AutoCAD</span> feature a large number of resources to optimize the import processes from the different data sources supported by the application

<!--more-->

<span>Along this blog post we will discuss some chances to &#8220;play&#8221; with certain parameters to get different outcomes in the imported objects using the XYZ ASCII provider</span>

## XYZ files

The XYZ files are one of the most common types of files to store points coordinates. They are plain-text ASCII files, without binary numbers or any other data type that has to be interpreted, can be easily read or written by any application and a user can look at their content using common utilities, such as Window Notepad

Every line in the file corresponds to a point data and every number between two delimiter characters in a line corresponds to a coordinate (X, Y or Z) of a point feature. There are various characters that may be used as the delimiter character. The most common used delimiter characters are the comma, the tab, the space character or the semicolon

<p>
  <img src="/images/blog/2014/08/AutoCAD-XYZ-Notepad.png" alt="AutoCAD XYZ file - Open XYZ file in Notepad" width="542" height="244" srcset="/images/blog/2014/08/AutoCAD-XYZ-Notepad.png 542w, /images/blog/2014/08/AutoCAD-XYZ-Notepad-300x135.png 300w" sizes="(max-width: 542px) 100vw, 542px" />
</p>

## XYZ to CAD

CAD applications users often need to import these kind of point data files into their drawings, and the content of the files is usually very diverse: GPS generic data, surveying data, hydrants, signals, address points, etc.

<a title="AutoCAD product page" href="http://www.autodesk.com/products/autocad/overview" target="_blank" rel="nofollow">AutoCAD</a>, being one of the popular applications in the CAD market, cannot directly translate the contents of XYZ files to AutoCAD, not even as Point type objects. To perform a task such as Import XYZ files to AutoCAD, you will need an additional AutoCAD utility or plug-in

## Import XYZ files and label Z values in AutoCAD

<a title="Spatial Manager™ for AutoCAD product page" href="http://www.spatialmanager.com/spm-forautocad/" target="_blank" rel="nofollow">Spatial Manager™ for AutoCAD</a> includes, in addition to many other access tools, a powerful &#8220;AutoCAD XYZ&#8221; data provider to import XYZ files into AutoCAD

As when importing point type features using any other data provider included in the application, you can choose between Point objects or Block references and many other interesting drawing options through the import process

You can also perform a coordinate transformation &#8220;on the fly&#8221; when importing. The coordinate transformation is an important issue to consider in Spatial Manager™ for AutoCAD when importing from XYZ files because a lot of coordinate data comes from GPS devices or similar. Thus the coordinate data is formatted using Latitude and Longitude values and the users usually need to import the data to projected coordinates into the DWG drawing

This example shows how to Import a XYZ file into AutoCAD. We will import a set of surveying points into an AutoCAD drawing

First, we will choose AutoCAD Block references to import the Points as 3D objects by selecting a &#8220;XYZ&#8221; file format

Next, we will **apply a nice trick by adding an Attribute to the Block** definition and by catching the Z coordinate inside the Attribute to get 2D Points with the Z coordinate <span>labeled</span> <span>right next to the</span> <span>point, when <strong>selecting &#8220;XY Description&#8221;</strong> as the file format</span>

Please, watch the video: