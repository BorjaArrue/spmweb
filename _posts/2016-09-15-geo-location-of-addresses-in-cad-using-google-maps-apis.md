---
published: true
title: Geo-location of addresses in CAD using Google Maps APIs
date: 2016-09-15T13:52:32+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=3149
permalink: /geo-location-of-addresses-in-cad-using-google-maps-apis/
image: /images/blog/2016/09/Blog1-CAD-85px.png
categories:
  - CAD L2 (Medium)
tags:
  - Geo-location
  - Google Maps
  - ODBC
---
Within this interesting example we show how to include, on an existing AutoCAD or BricsCAD drawing of a city, locations from a list of addresses as points (Blocks) on the drawing, using Google Maps APIs for geo-location_
  
_ 

<!--more-->

<p>
  <a href="/images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD.png" target="_blank" rel="nofollow"><img src="/images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD-1024x576.png" alt="geolocation-using-spatial-manager-acad-or-bcad" width="625" height="352" srcset="/images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD-1024x576.png 1024w, /images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD-300x169.png 300w, /images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD-768x432.png 768w, /images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD-624x351.png 624w, /images/blog/2016/09/GeoLocation-using-Spatial-Manager-ACAD-or-BCAD.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
</p>

<h2>
  <strong>Videos: <span><span><a href="https://youtu.be/vRFodKNo3Ig?rel=0" target="_blank" rel="nofollow">AutoCAD</a> </span>/ <span><a href="https://youtu.be/qOJ_qRxBRoI?rel=0" target="_blank" rel="nofollow">BricsCAD</a></span></span></strong>
</h2>

The process is also supported by a small application developed using VBA in Excel and **applying these APIs to get the Latitude and Longitude from the list of addresses**. The process works as follows:

  * **Excel** 
      * In the first three columns the user can enter the name of the Street, the house Numbering (if any) and the name of the City
      * The next column is automatically calculated by concatenation of the data in the previous columns. The result is passed as a parameter to the next column in which, using the &#8220;GoogleGeocode&#8221; function defined in the VBA application, Google Maps APIs returns the full address values and the Latitude and Longitude of the mailing address
      * In the last two columns the corresponding Latitude and Longitude values are extracted, using the &#8220;GetPartOf&#8221; also defined in the VBA application
  * **Data source** 
      * We define a Windows ODBC source for this Excel worksheet and we create a &#8216;Spatial Manager™&#8217; User Data Source (UDS)  for this ODBC source
  * ** AutoCAD or BricsCAD: Points import for the addresses** 
      * Over a drawing of the city which has been used as our example in the addresses Excel worksheet, we import the points from the UDS created using AutoCAD or BricsCAD Block References
  * <span>Notes</span> 
      * The **number of addresses to calculate it is unlimited** because you just need to copy and paste any row in the Excel worksheet
      * As you can see in the video, **the addresses can be extended** on the same Excel worksheet **to different cities or even to different countries** (just add the name of the country separated by a comma after the name of the city)
      * The accuracy of the geo-location returned by Google Maps APIs will obviously be greater as the data entered is more accurate