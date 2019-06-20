---
published: true
title: Enhance the Map images quality
date: 2017-12-04T11:37:57+00:00
author: admin
layout: old-post
permalink: /enhance-the-map-images-quality/
image: /images/blog/2017/11/Enhanced-Maps85-2.png
categories:
  - CAD L2 (Medium)
tags:
  - Background Maps
  - Tricks and Tools
---
In the latest version of &#8216;Spatial Manager&#8217; for CAD applications (_AutoCAD / BricsCAD / ZWCAD_), you will find a new configuration option that allows you to improve the visual quality of the &#8216;Background Maps&#8217;<!--more-->

<h2></h2>
Click on the image below to check how the rendering engine can now **enhance the &#8216;Background Map&#8217; images** (on screen as in printed maps)



<div>
  <a href="/images/blog/2017/11/Image_quality_1_to_4.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/11/Image_quality_1_to_4.png" alt="Enhanced 'Background Maps' quality" width="800" height="380" srcset="/images/blog/2017/11/Image_quality_1_to_4.png 800w, /images/blog/2017/11/Image_quality_1_to_4-300x143.png 300w, /images/blog/2017/11/Image_quality_1_to_4-768x365.png 768w, /images/blog/2017/11/Image_quality_1_to_4-624x296.png 624w" sizes="(max-width: 800px) 100vw, 800px" /></a>
  
  <p>
    Enhanced &#8216;Background Map&#8217; quality
  </p>
</div>

<h2></h2>
As you can see in the right sample of this image, the texts and some other components of the Map **are more clearly readable** than in the left sample

<h2></h2>
This is accomplished by processing and smoothing **high-resolution versions** of the original Map images. However, the initial display and the subsequent updates of the Map on screen may be somewhat slower

## How to control and configure this functionality?

You will find a new setting control when accessing the application configuration (SPMOPTIONS). The control allows you to choose from **three settings**:

<h2></h2>
  1. Standard images quality / High performance
  2. Enhanced images quality / Medium performance
  3. Best images quality / Low performance

<h2></h2>
Since the **optimum configuration depends on several factors** (read more below), your experience will tell you the setting to select in a particular combination of system, drawing and &#8216;Background Map&#8217;

<h2></h2>
<div>
  <a href="/images/blog/2017/11/New-SPMOPTIONS.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/11/New-SPMOPTIONS.png" alt="'Image quality' setting in SPMOPTIONS" width="646" height="557" srcset="/images/blog/2017/11/New-SPMOPTIONS.png 646w, /images/blog/2017/11/New-SPMOPTIONS-300x259.png 300w, /images/blog/2017/11/New-SPMOPTIONS-624x538.png 624w" sizes="(max-width: 646px) 100vw, 646px" /></a>
  
  <p>
    &#8216;Image quality&#8217; setting in SPMOPTIONS
  </p>
</div>

## AutoCAD specific comments

AutoCAD is the CAD platform where **enhancing the map images may be more necessary**, because the internal AutoCAD antialiasing tool operates for some zoom levels only

<h2></h2>
If you expand the image below (click on it), you will be able to check the Map image quality that you can get by using the standard AutoCAD GeoMap technology (only &#8216;Bing&#8217;) and the enhanced Map images quality that you can get when selecting the &#8216;Background Maps&#8217; technology developed in &#8216;Spatial Manager&#8217; (the same &#8216;Bing&#8217; map in the sample in order to compare)

<h2></h2>
<div>
  <a href="/images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM.png" target="_blank" rel="nofollow"><img src="/images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM-877x1024.png" alt="Bing Maps - AutoCAD versus 'Spatial Manager' enhanced images" width="625" height="730" srcset="/images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM-877x1024.png 877w, /images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM-257x300.png 257w, /images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM-768x897.png 768w, /images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM-624x729.png 624w, /images/blog/2017/11/Bing-Maps-AutoCAD-vs-SPM.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Bing Maps &#8211; AutoCAD versus &#8216;Spatial Manager&#8217; enhanced images
  </p>
</div>



## And last, but not at least

As you can read in the Technical Wikis of the products (<a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_enhance_the_quality_of_the_.27Background_Maps.27.3F" target="_blank" rel="nofollow"><span><em>AutoCAD</em></span></a> / <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_enhance_the_quality_of_the_.27Background_Maps.27.3F" target="_blank" rel="nofollow"><span><em>BricsCAD</em></span></a> / <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)#Can_I_enhance_the_quality_of_the_.27Background_Maps.27.3F" target="_blank" rel="nofollow"><span><em>ZWCAD</em></span></a>), the quality improvement will be more appreciable depending on your **graphic system, the zoom level** and the **selected &#8216;Background Map&#8217;**

<h2></h2>
In addition, the quality improvements may be more necessary **if the CRS of the Map has to be transformed**, as the resulting Map images will be obtained by deforming rectangular frames

<h2></h2>
Finally, keep in mind that the command **&#8216;IMAGEQUALITY&#8217; (Draft/High)** can also affect the &#8216;Background Maps&#8217; quality

<h2></h2>
<span>Learn more</span> about the **use and configuration of &#8216;Background Maps&#8217;** in Spatial Manager:

<h2></h2>
  * **Blog**: 
      * _<span><span><a href="/tag/background-maps/" target="_blank" rel="nofollow">&#8216;Background Maps&#8217; posts</a></span></span>_

<h2></h2>
  * **Technical Wiki**: 
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)" target="_blank" rel="nofollow">Spatial Manager for AutoCAD</a></span>_
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span>_
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD_-_FAQs:_Background_Maps_(%22Standard%22_and_%22Professional%22_editions_only)" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span>_