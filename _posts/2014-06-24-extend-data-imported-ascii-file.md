---
published: true
title: Extend the data to be imported from an ASCII file
date: 2014-06-24T18:06:55+00:00
author: admin
layout: old-post
guid: http://www.spatialmanager.com/?p=1280
permalink: /extend-data-imported-ascii-file/
image: /images/blog/2014/06/Table-points-85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - ASCII
  - ODBC
---
When importing or loading points from spatial ASCII files (CSV, XYZ etc.), Spatial Manager™, like most applications which support these kinds of spatial data sources, includes only usual connection parameters<!--more-->

In the best case, the data provider for ASCII files allows you to read the Point number, its XYZ coordinates and its Description:

<a href="/images/blog/2014/06/ASCII-standard-data-provider.png" target="_blank" rel="nofollow"><img src="/images/blog/2014/06/ASCII-standard-data-provider.png" alt="Spatial_Manager_ASCII_standard_data_provider" width="615" height="648" /></a>

But, what happens if **the ASCII file includes more data fields** for the points, as shown in the following image? How can you include this data in loading, importing or exporting processes using Spatial Manager™ applications?

<a href="/images/blog/2014/06/ASCII-file-including-more-data.png" target="_blank" rel="nofollow"><img src="/images/blog/2014/06/ASCII-file-including-more-data.png" alt="Spatial_Manager_ASCII_file_including_more_data" width="615" height="391" srcset="/images/blog/2014/06/ASCII-file-including-more-data.png 905w, /images/blog/2014/06/ASCII-file-including-more-data-300x190.png 300w, /images/blog/2014/06/ASCII-file-including-more-data-624x397.png 624w" sizes="(max-width: 615px) 100vw, 615px" /></a>

A good choice is to use the <a title="ODBC Wikipedia" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> data provider, which allows you access to standard Windows connections for <a title="MS Excel page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS Excel </a>workbooks, <a title="MS Access page" href="http://office.microsoft.com/en-us/access/" target="_blank" rel="nofollow">MS Access</a> databases and many other spatial data containers. An example of a typical process can be summarized in the following steps:

1 &#8211; Import (open) the ASCII file using <a title="MS Excel page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS Excel</a>
  
2 &#8211; Add a header row and fill in the field names

<a href="/images/blog/2014/06/ASCII-file-imported-in-Excel.png" target="_blank" rel="nofollow"><img src="/images/blog/2014/06/ASCII-file-imported-in-Excel.png" alt="Spatial_Manager_ASCII_file_imported_in_Excel" width="615" height="280" srcset="/images/blog/2014/06/ASCII-file-imported-in-Excel.png 1144w, /images/blog/2014/06/ASCII-file-imported-in-Excel-300x136.png 300w, /images/blog/2014/06/ASCII-file-imported-in-Excel-1024x466.png 1024w, /images/blog/2014/06/ASCII-file-imported-in-Excel-624x284.png 624w" sizes="(max-width: 615px) 100vw, 615px" /></a>

3 &#8211; Define a name inside the <a title="MS Excel page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS Excel </a>workbook for the full range of the data cells and the header row
  
4 &#8211; Define an <a title="ODBC Wikipedia" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> connection in Windows for the <a title="MS Excel page" href="http://office.microsoft.com/en-us/excel/" target="_blank" rel="nofollow">MS Excel</a> workbook
  
5 &#8211; Define a <a title="UDS Wiki" href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Data_sources#What_are_the_User_Data_Sources_.28UDSs.29.3F" target="_blank" rel="nofollow">User Data Source (UDS) </a>using the Spatial Manager™ <a title="ODBC Wikipedia" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> Data Provider. The **User Data Source (UDS) can be now used in Spatial Manager™ to perform any process** in which the entire data table will be included

To find out more about the processes which use the <a title="ODBC Wikipedia" href="http://en.wikipedia.org/wiki/Odbc" target="_blank" rel="nofollow">ODBC</a> Data Provider, please see this post in the Blog: &#8220;<a title="How to access ODBC connections - Blog post" href="http://www.spatialmanager.com/access-odbc-connections/" target="_blank" rel="nofollow">How to access ODBC connections</a>&#8221;