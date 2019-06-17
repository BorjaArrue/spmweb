---
id: 1237
title: Share Maps with other Spatial Manager users
date: 2014-06-10T09:38:19+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=1237
permalink: /share-maps-spatial-manager-users/
image: /wp-content/uploads/2014/06/map-share85.png
categories:
  - Desktop L2 (Medium)
tags:
  - Disconnect
  - Layers
  - Share
---
One of the main problems of sharing maps with other users, and to be able to send a compact information, is the need to likewise share the data sources of the Map<!--more-->

<a title="Spatial Manager Desktop page" href="http://www.spatialmanager.com/spm-desktop/" target="_blank" rel="nofollow">Spatial Manager Desktop™</a> uses an interesting technique to solve this problem: the Map files of the application (*.spm) have been designed based on an internal data structure, to include Layers which reference to external data sources and/or Layers which **include their data inside the Map file itself**

If we combine this technology with the functionality of &#8220;**Disconnecting&#8221; Layers** from their external data sources, which is also included in the application, we can save Maps to be sent to other users, who will not need access to external data for the disconnected Layers

For example, if a map contains various Layers referring to spatial files, and some other Layers referring to spatial tables in a data server accessible through the Internet, it may be interesting to Disconnect the first group of Layers so that another user can work with the map without needing access to the spatial files, although he can access the spatial data server via the Internet for the rest of the Layers

If all the Layers are Disconnected in a Map, **we end up with a standalone Map** which does not require any access to external data. Moreover the Map does not become a simple &#8220;printed&#8221; Map, as **we do not lose any of the application tools**: we can still stylize the Map and the Layers, developing queries and spatial queries, editing data, exporting Layers and feature selections, etc.

In this example, we load various Layers into a Map, coming from a variety of spatial data sources. Next, all the Map Layers are Disconnected and the original used data sources are deleted. Finally, the Map is saved and reopened as a standalone Map, which contains all the information in the created SPM file itself. If the SPM file was sent to another user, he would have all the Map information inside this file, without the need to access any external data source

Please, watch the video: