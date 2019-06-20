---
published: true
title: Geo-location of addresses using Google Maps APIs
date: 2013-11-18T18:29:58+00:00
author: admin
layout: old-post
permalink: /geo-location-of-addresses-using-google-maps-apis/
image: /images/blog/2013/11/Blog1-85px3.png
categories:
  - Desktop L2 (Medium)
tags:
  - Geo-location
  - Google Maps
  - ODBC
---
Within this interesting example we show how to include, on an existing Map of a city, locations from a list of addresses as points on the Map, using Google Maps APIs for geo-location._
  
_ 

<!--more-->

The process is also supported by a small application developed using VBA in Excel and **applying these APIs to get the Latitude and Longitude from the list of addresses**. The process works as follows:

  * **Excel** 
      * In the first three columns the user can enter the name of the Street, the house Numbering (if any) and the name of the City
      * The next column is automatically calculated by concatenation of the data in the previous columns. The result is passed as a parameter to the next column in which, using the &#8220;GoogleGeocode&#8221; function defined in the VBA application, <a title="Google Maps APIs" href="https://developers.google.com/maps/" target="_blank" rel="nofollow">Google Maps APIs</a> returns the full address values and the Latitude and Longitude of the mailing address
      * In the last two columns the corresponding Latitude and Longitude values are extracted, using the &#8220;GetPartOf&#8221; also defined in the VBA application
  * **Data source** 
      * We define a Windows ODBC source for this Excel worksheet and create a Spatial Manager Desktop ™ User Data Source (UDS)  for this ODBC source
  * **Points features load for addresses** 
      * Over a Map of the city that has been used as our example in the addresses Excel worksheet, we load the points Layer from the UDS created, and then we stylize this Layer
  * Notes 
      * The **number of addresses to calculate it is unlimited** because you just need to copy and paste any row in the Excel worksheet
      * As you can see in the video, **the addresses can be extended** on the same Excel worksheet **to different cities or even to different countries** (just add the name of the country separated by a comma after the name of the city)
      * The accuracy of the geo-location returned by <a title="Google Map APIs" href="https://developers.google.com/maps/" target="_blank" rel="nofollow">Google Maps APIs</a> will obviously be greater as the data entered is more accurate

&nbsp;

Please, watch the video:

<center>
  <br />
</center>