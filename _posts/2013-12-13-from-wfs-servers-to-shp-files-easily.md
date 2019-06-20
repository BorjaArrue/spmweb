---
published: true
title: From WFS servers to SHP files easily
date: 2013-12-13T17:27:41+00:00
author: admin
layout: old-post
guid: http://berlin.opencartis.com/wordpress/?p=372
permalink: /from-wfs-servers-to-shp-files-easily/
image: /images/blog/2013/12/WFS-in-center-85.png
categories:
  - Desktop L3 (Advanced)
tags:
  - Corporate
  - Data sources
  - Shapefiles (SHP)
  - WFS
---
<p>
  The Open Geospatial Consortium Web Feature Service Interface Standard (WFS) provides an interface allowing requests for geographical features across the web using platform-independent calls<!--more-->
</p>

<p>
  The basic Web Feature Service allows querying and retrieval of features. The client generates the request and posts it to a web feature server using HTTP. The web feature server then executes the request
</p>

<p>
  Increasingly,<strong> government departments and other public entities, use WFS data stores to make public their geo-spatial information</strong>. Connecting to these services from Spatial Manager Desktop ™ and extracting information from their data tables is extremely simple
</p>

<p>
  In this example, we will connect to a WFS server, visualize some of their spatial data tables and, finally, we will export one of them to a Shapefile. These are the main steps to perform:
</p>

<li>
  <strong>Create a User Data Source (UDS)</strong> to connect to the WFS server. Notes: <ul>
    <li>
      This UDS will remain in the configuration of your application, as long as you do not delete it, to connect as many times as necessary with the same WFS server without re-writing the connection parameters
    </li>
    <li>
      Sometimes, the connection line includes other data, such as the chosen SRID (WFS servers can store the Features using several SRIDs), username, password, the version of the WFS data store, etc. Note, that when creating the new UDS, you can introduce these last three parameters into their corresponding boxes
    </li>
    <li>
      There are two available Data Providers to connect to WFS servers; one uses the generic FDO data Provider and one an OGR data source. The choice is based on the best performance and compatibility offered by either depending on the server to which the connection is established. In this example we will use the first option
    </li>
  </ul>
</li>

<li>
  If you want to, <strong>load a new Map layer</strong> from any data table of the WFS server, to display it on the screen
</li>
  * Choose the **Export** option in one of the data tables to export it to an SHP file, introducing all the parameters for the exporting operation. Note: 
    <li>
      If you plan to repeat this export process frequently, <strong>save the Task</strong>, as in the example, to run it whenever you like
    </li>

Please, watch the video:

<center>
  <br />
</center>