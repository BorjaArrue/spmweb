---
published: true
title: Traffic and transit in Google Maps
date: 2019-04-11T11:30:58+00:00
author: admin
layout: old-post
permalink: /traffic-and-transit-in-google-maps/
image: /images/blog/2019/04/GMaps_Traffic_Transit85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Background Maps
  - Google Maps
---
<p>
  Following several previous posts about how to configure and apply diverse parameters for Google Maps as dynamic Background Maps in &#8216;Spatial Manager&#8217; (AutoCAD, BricsCAD, ZWCAD or Desktop), you can learn here how to add Real-Time Traffic and Transit (public transport tracing) information to these maps
</p>

<p>
  <!--more-->
</p>

<h2>
</h2>

<p>
  In the post <em><span><a href="/google-maps-in-your-cad-drawings-of-course/" target="_blank" rel="nofollow">&#8220;Google Maps in your CAD drawings? Of course&#8221;</a></span> </em>published in this Blog some months ago, you can review <strong>how to configure Google Maps</strong> in the Background Maps system of &#8216;Spatial Manager&#8217; and the use of basic parameters
</p>

<p>
  Also, in a later post <a href="/more-about-dynamic-google-maps-in-your-drawings-or-maps/" target="_blank" rel="nofollow"><span><em>&#8220;More about dynamic Google Maps in your drawings or Maps&#8221;</em></span></a> you can find out how to use a set of advanced map parameters in order to define <strong>the map type or the language</strong> of the texts and toponyms in the maps if available
</p>

<p>
  The complementary parameters <strong>&#8220;Traffic&#8221;</strong> and <strong>&#8220;Transit&#8221;</strong> will now allow you to add traffic status and public transport lines to any of the Google Maps. Take a look at the application of these parameters in the following examples:
</p>

<p>
  <strong>URL:</strong> <em>https://{mt,mt0,mt1,mt2,mt3}.google.com/vt/<span><strong>lyrs=m</strong></span><span><strong>,traffic</strong></span>&x={x}&y={y}&z={level}</em><br /> <strong>Result:</strong> Google Maps &#8220;Standard&#8221; + Traffic status<br /> <strong>Map</strong> <em>(Click in the image to enlarge)</em><strong>:</strong>
</p>

<h2>
</h2>

<div>
  <a href="/images/blog/2019/04/GMaps-Standard-Traffic.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/04/GMaps-Standard-Traffic-1024x502.png" alt="Google Maps Standard + Traffic" width="625" height="306" srcset="/images/blog/2019/04/GMaps-Standard-Traffic-1024x502.png 1024w, /images/blog/2019/04/GMaps-Standard-Traffic-300x147.png 300w, /images/blog/2019/04/GMaps-Standard-Traffic-768x376.png 768w, /images/blog/2019/04/GMaps-Standard-Traffic-624x306.png 624w, /images/blog/2019/04/GMaps-Standard-Traffic.png 1249w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Google Maps Standard + Traffic
  </p>
</div>

<h2>
</h2>

<p>
  <strong>URL:</strong> <em>https://{mt,mt0,mt1,mt2,mt3}.google.com/vt/<span><strong>lyrs=y</strong></span><span><strong>,traffic</strong></span>&x={x}&y={y}&z={level}</em><br /> <strong>Result:</strong> Google Maps &#8220;Satellite Hybrid&#8221; + Traffic status<br /> <b>Map</b> <em>(Click in the image to enlarge)</em><strong>:</strong>
</p>

<div>
  <a href="/images/blog/2019/04/GMaps-SatelliteHybrid-Traffic.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/04/GMaps-SatelliteHybrid-Traffic-1024x502.png" alt="Google Maps Satellite Hybrid + Traffic" width="625" height="306" srcset="/images/blog/2019/04/GMaps-SatelliteHybrid-Traffic-1024x502.png 1024w, /images/blog/2019/04/GMaps-SatelliteHybrid-Traffic-300x147.png 300w, /images/blog/2019/04/GMaps-SatelliteHybrid-Traffic-768x376.png 768w, /images/blog/2019/04/GMaps-SatelliteHybrid-Traffic-624x306.png 624w, /images/blog/2019/04/GMaps-SatelliteHybrid-Traffic.png 1249w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Google Maps Satellite Hybrid + Traffic
  </p>
</div>

<h2>
</h2>

<p>
  <strong>URL:</strong> <em>https://{mt,mt0,mt1,mt2,mt3}.google.com/vt/<span><strong>lyrs=h</strong></span><strong><span>,transit</span></strong>&x={x}&y={y}&z={level}<strong><span>&hl=fr</span></strong></em><br /> <strong>Result:</strong> Google Maps &#8220;Roads only&#8221; + Public transport lines (Transit). French texts, if available<br /> <strong>Map</strong> <em>(Click in the image to enlarge)</em><strong>:</strong>
</p>

<div>
  <a href="/images/blog/2019/04/GMaps-Roads-Transit2.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/04/GMaps-Roads-Transit2-1024x505.png" alt="Google Maps Roads only + Transit (Public transport)" width="625" height="308" srcset="/images/blog/2019/04/GMaps-Roads-Transit2-1024x505.png 1024w, /images/blog/2019/04/GMaps-Roads-Transit2-300x148.png 300w, /images/blog/2019/04/GMaps-Roads-Transit2-768x379.png 768w, /images/blog/2019/04/GMaps-Roads-Transit2-624x308.png 624w, /images/blog/2019/04/GMaps-Roads-Transit2.png 1249w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Google Maps Roads only + Transit (Public transport)
  </p>
</div>

<h2>
</h2>

<p>
  You can even <strong>combine both parameters</strong> in the map URL. Thus, for example, the map above could show Traffic and Transit using the two parameters together:
</p>

<p>
  <em>https://{mt,mt0,mt1,mt2,mt3}.google.com/vt/lyrs=h<span><strong>,traffic,transit</strong></span>&x={x}&y={y}&z={level}&hl=fr</em>
</p>

<p>
  In addition, the &#8220;Transit&#8221; information can be configured as an isolated layer, without the need to combine it with any other layer, if you <strong>want to have Public Transport lines only</strong>:
</p>

<p>
  <em>https://{mt,mt0,mt1,mt2,mt3}.google.com/vt/<span><strong>lyrs=transit</strong></span>&x={x}&y={y}&z={level}</em>
</p>

<p>
  And, although Traffic information cannot be presented separately, you can combine it with the Transit lines:
</p>

_https://{mt,mt0,mt1,mt2,mt3}.google.com/vt/<span><strong>lyrs=transit,traffic</strong></span>&x={x}&y={y}&z={level}_

<p>
  Try to combine parameters by yourself in order to get the custom maps that you are interested in
</p>

<h2>
</h2>

<h2>
</h2>

<h6>
  <em>Note for CAD versions: Background Maps functionalities are available in Standard or Professional editions only</em>
</h6>