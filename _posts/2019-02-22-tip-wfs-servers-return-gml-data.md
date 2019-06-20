---
published: true
title: 'Tip &#8211; WFS servers return GML data'
date: 2019-02-22T12:51:54+00:00
author: admin
layout: old-post
permalink: /tip-wfs-servers-return-gml-data/
image: /images/blog/2019/02/WFSasGML85.png
categories:
  - CAD L3 (Advanced)
  - Desktop L3 (Advanced)
tags:
  - Data sources
  - GML
  - Tricks and Tools
  - WFS
---
<p>
  WFS data servers provide the ability to access vector spatial information via a remote connection. Although you can use &#8216;Spatial Manager&#8217; User Data Sources (UDS) to access this type of servers, it is interesting to know that these servers return data in GML format
</p>

<p>
  <!--more-->
</p>

<div>
  <a href="/images/blog/2019/02/WFS_as_GMData2.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/02/WFS_as_GMData2-1024x511.png" alt="Import GML data from WFS servers" width="625" height="312" srcset="/images/blog/2019/02/WFS_as_GMData2-1024x511.png 1024w, /images/blog/2019/02/WFS_as_GMData2-300x150.png 300w, /images/blog/2019/02/WFS_as_GMData2-768x383.png 768w, /images/blog/2019/02/WFS_as_GMData2-624x312.png 624w, /images/blog/2019/02/WFS_as_GMData2.png 1264w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Import GML data from WFS servers
  </p>
</div>

<h2>
</h2>

<p>
  <span><em><a href="http://www.spatialmanager.com/" target="_blank" rel="nofollow">&#8216;Spatial Manager&#8217;</a></em></span> includes two <strong>spatial data providers</strong> to access <span><a href="https://en.wikipedia.org/wiki/Web_Feature_Service" target="_blank" rel="nofollow"><em><span>WFS (Web Feature Service)</span></em></a></span> servers, one of them based on <span><em><a href="http://fdo.osgeo.org/" target="_blank" rel="nofollow">OSGeo FDO</a></em></span> and the other based on <a href="https://en.wikipedia.org/wiki/GDAL" target="_blank" rel="nofollow"><span><em>GDAL/OGR</em></span></a>
</p>

<div>
  <a href="/images/blog/2019/02/SPMDataProviders.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/02/SPMDataProviders.png" alt="'Spatial Manager' data providers" width="563" height="673" srcset="/images/blog/2019/02/SPMDataProviders.png 563w, /images/blog/2019/02/SPMDataProviders-251x300.png 251w" sizes="(max-width: 563px) 100vw, 563px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; data providers
  </p>
</div>

<h2>
</h2>

<p>
  However, as mentioned, the content returned by these servers is structured in <span><em><a href="https://en.wikipedia.org/wiki/Geography_Markup_Language" target="_blank" rel="nofollow">GML (Geography Markup Language)</a></em></span> format. Since you can also <strong>directly import GML files</strong> using &#8216;Spatial Manager&#8217;, if you <strong>experience any connection or access problems</strong> to the WFS server you can use the technique described below
</p>

<h2>
</h2>

<p>
  Let&#8217;s use the following WFS server as an example:
</p>

<p>
  <span><em>https://www.baysis.bayern.de/gis/services/wfs/BAYSIS_Strassenbestand/MapServer/WFSServer?</em></span>
</p>

<p>
  To <strong>get the Layers</strong> (Tables) provided by this server, you can enter the following URL in any Internet browser:
</p>

<p>
  <span><em>https://www.baysis.bayern.de/gis/services/wfs/BAYSIS_Strassenbestand/MapServer/WFSServer<strong><span>?service=wfs&request=GETCAPABILITIES</span></strong></em></span>
</p>

<p>
  In the GML formatted text returned by the server, you can search for <strong>&#8220;FeatureType&#8221;</strong> and <strong>&#8220;Name&#8221;</strong> nodes. These are the names that must be added as parameters to access each Layer (see below):
</p>

<h2>
</h2>

<p>
  <img src="/images/blog/2019/02/XMLLayersList.png" alt="XMLLayersList" width="438" height="191" srcset="/images/blog/2019/02/XMLLayersList.png 438w, /images/blog/2019/02/XMLLayersList-300x131.png 300w" sizes="(max-width: 438px) 100vw, 438px" />
</p>

<h2>
</h2>

<p>
  To <strong>access the Layer data</strong>, enter the following URL in any Internet browser:
</p>

<p>
  <span><em>https://www.baysis.bayern.de/gis/services/wfs/BAYSIS_Strassenbestand/MapServer/WFSServer<span><strong>?service=wfs&request=GETFEATURE&typename=<span>STRBESTAND_WFS:Fahrstreifen<span>&maxFeatures=50&startIndex=1000</span></span></strong></span></em></span>
</p>

<p>
  You can now <strong>copy</strong> to the clipboard the GML content returned by the browser, <strong>paste</strong> it into any text editor, <strong>save</strong> this file with the GML (or XML) extension and <strong>import</strong> it using &#8216;Spatial Manager&#8217;. If your browser gives you the possibility to do so, you can also directly save the content of the page in a file with GML (or XML) extension. It&#8217;s that simple. Try it by yourself
</p>

<h2>
</h2>

<p>
  In the sample URL above, the <strong><em>maxFeatures</em> parameter limits the number of elements</strong> to read to 50, and the <strong><em>startIndex</em> parameter points to the element</strong> 1000 as the first element to read. You can modify these parameters according to your needs or remove them if you want to read the whole layer (beware of the size)
</p>

<h2>
</h2>

* * *

<p>
  <em><strong>Note:</strong></em>
</p>

<p>
  In some servers, like the one in the example above, the specification of the <strong>WFS version</strong> is optional, but in others servers this parameter is mandatory. You can get the version (or versions) supported by the server using the same URL indicated above for the Layer search and locating the identifier <strong>&#8220;AcceptVersions&#8221;</strong>
</p>

<h2>
</h2>

<p>
  <a href="/images/blog/2019/02/XMLAcceptVersions.png" target="_blank" rel="nofollow"><img src="/images/blog/2019/02/XMLAcceptVersions.png" alt="XMLAcceptVersions" width="295" height="108" /></a>
</p>

<h2>
</h2>

<p>
  If it is necessary (or even optional) to include the version number, you can define the parameter as in the following example:
</p>

<p>
  <span><em>https://www.baysis.bayern.de/gis/services/wfs/BAYSIS_Strassenbestand/MapServer/WFSServer</em></span><span><em>?service=wfs&request=GETFEATURE&typename=</em></span><span><em>STRBESTAND_WFS:Fahrstreifen<span>&maxFeatures=50&startIndex=1000</span></em></span><em><strong><span>&version=2.0.0</span></strong></em>
</p>

<h2>
</h2>

* * *

<h2>
</h2>

<p>
  <em>Learn more about import spatial data in &#8216;Spatial Manager&#8217;:</em>
</p>

<h2>
</h2>

<ul>
  <li>
    <span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_AutoCAD_-_FAQs:_Import" target="_blank" rel="nofollow"><span><em>Spatial Manager for AutoCAD</em></span></a></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Import" target="_blank" rel="nofollow"><span><em>Spatial Manager for BricsCAD</em></span></a></span></span>
  </li>
  <li>
    <span><span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Import" target="_blank" rel="nofollow"><span><em>Spatial Manager for ZWCAD</em></span></a></span></span>
  </li>
  <li>
    <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Import_and_export" target="_blank" rel="nofollow"><span><em>Spatial Manager Desktop</em></span></a>
  </li>
</ul>

<h2>
</h2>

<p>
  <span><i>Warning: Some of the features discussed here are available in the Standard and/or Professional editions only</i></span>
</p>