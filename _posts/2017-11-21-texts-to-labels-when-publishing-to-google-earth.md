---
published: true
title: Texts to Labels when Publishing to Google Earth
date: 2017-11-21T11:34:56+00:00
author: admin
layout: old-post
permalink: /texts-to-labels-when-publishing-to-google-earth/
image: /images/blog/2017/11/Labels-in-GE85.png
categories:
  - CAD L2 (Medium)
tags:
  - Export
  - Google Earth (KML)
  - Labels
---
<p>
  From of &#8216;Spatial Manager&#8217; v.4 (<em>AutoCAD / BricsCAD / ZWCAD</em>), when a drawing is Published to Google Earth the text objects are exported as named points in order to display the tags automatically<!--more-->
</p>

<h2>
  Related videos: <span><a href="https://youtu.be/JDOB5BMRU7A?rel=0" target="_blank" rel="nofollow">AutoCAD</a></span> / <span><a href="https://youtu.be/oCM2gWvwcGY?rel=0" target="_blank" rel="nofollow">BricsCAD</a></span> / <span><a href="https://youtu.be/kys90XIqxHE?rel=0" target="_blank" rel="nofollow">ZWCAD</a></span>
</h2>

* * *

<div>
  <a href="/images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth-1024x530.png" alt="Text objects from CAD converted to Labels in Google Earth" width="625" height="323" srcset="/images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth-1024x530.png 1024w, /images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth-300x155.png 300w, /images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth-768x398.png 768w, /images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth-624x323.png 624w, /images/blog/2017/11/Spatial-Manager-Texts-to-Labels-when-Publishing-to-Google-Earth.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Text objects from CAD converted to Labels in Google Earth
  </p>
</div>

<h2>
</h2>

The &#8216;Export to Google Earth&#8217; (publish) tool in &#8216;Spatial Manager&#8217; assumes the following automations:

## 

  * _The process considers the current Layers organization and the properties of the Layers and objects_
  * _The elements in the KML/KMZ file will assume the colors, line weights, etc. of the objects in the drawing_
  * _A subdivision based on the type(s) of the objects in the Layers will also be created for each Layer, allowing you a high level of visibility control in Google Earth_
  * _The values for the NAME and DESCRIPTION of the elements in the KML/KMZ file will be automatically taken from the data fields &#8220;Name&#8221; and &#8220;Description&#8221; if those exist_
  * The **Text objects will display their content as a Label in Google Earth** (automatic Field &#8220;TxtString&#8221;)

## How it works?

The processes performed when Publishing to Google Earth make use internally of **two application components** (_see the image below_):

## 

  * The **Export engine**, whose parameter set includes the options to export several sets of Text data such as the Contents, which will go to a new data field named &#8220;TxtString&#8221;
  * The **KML/KMZ Data Provider**, which allows you to select a data field to set the NAME of the exported objects. In the Publishing processes the field &#8220;TxtString&#8221; is automatically selected

## 

<div>
  <a href="/images/blog/2017/11/Export-KML-Parameters.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/11/Export-KML-Parameters.png" alt="Application Export parameters set, and KML data provider parameters set" width="782" height="643" srcset="/images/blog/2017/11/Export-KML-Parameters.png 782w, /images/blog/2017/11/Export-KML-Parameters-300x247.png 300w, /images/blog/2017/11/Export-KML-Parameters-768x631.png 768w, /images/blog/2017/11/Export-KML-Parameters-624x513.png 624w" sizes="(max-width: 782px) 100vw, 782px" /></a>
  
  <p>
    Application Export parameters set, and KML data provider parameters set
  </p>
</div>

<h2>
</h2>

* * *

<p>
  Please, go to the technical Wikis if you want to learn more about Publishing to Google Earth from CAD drawings:
</p>

<p>
  <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Export_(%22Professional%22_edition_only)#Can_I_quickly_Export_the_current_drawing_status_.28Publish.29_to_Google_Earth_.28.22Standard.22_and_.22Professional.22_editions.29" target="_blank" rel="nofollow">· Spatial Manager for AutoCAD</a></em><br /> <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Export_(%22Professional%22_edition_only)#Can_I_quickly_Export_the_current_drawing_status_.28Publish.29_to_Google_Earth_.28.22Standard.22_and_.22Professional.22_editions.29" target="_blank" rel="nofollow"><em>· Spatial Manager for BricsCAD<br /> </em></a><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Export_(%22Professional%22_edition_only)#Can_I_quickly_Export_the_current_drawing_status_.28Publish.29_to_Google_Earth_.28.22Standard.22_and_.22Professional.22_editions.29" target="_blank" rel="nofollow">· Spatial Manager for ZWCAD</a></em>
</p>