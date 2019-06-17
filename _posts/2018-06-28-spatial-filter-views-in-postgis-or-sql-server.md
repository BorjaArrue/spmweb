---
id: 5473
title: Spatial filter Views in PostGIS or SQL Server
date: 2018-06-28T14:09:08+00:00
author: admin
layout: post
guid: http://www.spatialmanager.com/?p=5473
permalink: /spatial-filter-views-in-postgis-or-sql-server/
image: /wp-content/uploads/2018/05/DBaseView_SPM85.jpg
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - PostGIS
  - Spatial queries
  - SQL Spatial
---
<p>
  While many &#8216;Spatial Manager&#8217; users operate with spatial databases, such as PostGIS or SQL Server Spatial, very few know that database Views are processed in this application in the same way as database Tables. In the sample shown in this post you can see how to use a spatial query to create a database View<br /> <!--more-->
</p>

<div>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM-1024x472.png" alt="Filtered PostGIS or SQL Server Spatial View in 'Spatial Manager'" width="625" height="288" srcset="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM-1024x472.png 1024w, http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM-300x138.png 300w, http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM-768x354.png 768w, http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM-624x288.png 624w, http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM.png 1280w" sizes="(max-width: 625px) 100vw, 625px" /></a>
  
  <p>
    Filtered PostGIS or SQL Server Spatial View in &#8216;Spatial Manager&#8217;
  </p>
</div>

<h2>
</h2>

<p>
  To illustrate the example (PostGIS and SQL Server Spatial), let&#8217;s assume that we want to consult the &#8220;Census&#8221; Table that has the &#8220;geom&#8221; Column (Field) defined in the &#8220;City&#8221; schema and obtain only the geometries that coincide with a rectangle whose envelope coordinates are:
</p>

<h2>
</h2>

<ul>
  <li>
    xmin: <strong>1884515</strong>
  </li>
  <li>
    ymin: <strong>451900</strong>
  </li>
  <li>
    xMax: <strong>1897526</strong>
  </li>
  <li>
    yMax: <strong>458931</strong>
  </li>
</ul>

<h2>
</h2>

* * *

<h2>
  <span>PostGIS</span>
</h2>

<p>
  The SQL statement to query and create the View would be:
</p>

<h2>
</h2>

<p>
  <span><strong>SELECT *<br /> </strong><strong>FROM &#8220;City&#8221;.&#8221;Census&#8221;<br /> </strong><strong>WHERE ST_Intersects(&#8220;geom&#8221; , ST_GeometryFromText(&#8216;SRID=26741;POLYGON((1884515 451900, 1884515 458931, 1897526 458931,1897526 451900,1884515 451900))&#8217;)::geometry)</strong></span>
</p>

<h2>
</h2>

<ul>
  <li>
    <strong>ST_Intersects</strong> is the function that compares each geometry of the Table. There are other functions for other types of queries:<em> ST_Contains, ST_Crosses, ST_Intersects, ST_Touches</em>, …
  </li>
  <li>
    <strong>ST_GeometryFromText</strong> is the function to compose a polygon (or any other type of geometry) from its text representation in <em><span><a href="https://en.wikipedia.org/wiki/Well-known_text" target="_blank" rel="nofollow">WKT</a></span></em> format <ul>
      <li>
        Note: For non-projected geometries that are defined in latitude-longitude, you should use <em>ST_GeographyFromText</em>
      </li>
    </ul>
  </li>
  
  <li>
    <strong>SRID=26741</strong> is the code of the coordinate reference system (CRS). It must be the same as the geometries to be queried in order to work correctly. If it is not defined, this parameter can be omitted
  </li>
  <li>
    <strong>POLYGON((1884515 451900, 1884515 458931, 1897526 458931,1897526 451900,1884515 451900))</strong> WKT representation of the geometry to be used for the spatial query
  </li>
</ul>

<h2>
</h2>

<p>
  The created View will appear in the USD area of the &#8216;Spatial Manager&#8217; data sources panel as any database Table so you can use it as any source to import or load the filtered features:
</p>

<h2>
</h2>

<h2>
  <img src="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_in-USD-zrea.png" width="211" height="128" />
</h2>

<h2>
</h2>

<p>
  Importing  / loading results &#8211; <strong><span>Green</span></strong> for the full table &#8220;Census&#8221;, <strong><span>Red</span></strong> for the created &#8220;CensusFiltered&#8221; View:
</p>

<h2>
</h2>

<h2>
  <a href="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_Results.png" target="_blank" rel="nofollow"><br /> </a><a href="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_Results.png" target="_blank" rel="nofollow"><img src="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_Results-227x300.png" width="227" height="300" srcset="http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_Results-227x300.png 227w, http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_Results-624x823.png 624w, http://www.spatialmanager.com/wp-content/uploads/2018/05/FilteredPGISView_SPM_Results.png 667w" sizes="(max-width: 227px) 100vw, 227px" /></a>
</h2>

<h2>
</h2>

<p>
  Other <strong>more advanced types of queries</strong> can be made. In the below example, a Column &#8220;Area&#8221; is added and the features whose area is greater than 20000 and whose &#8220;BGROUP&#8221; value is equal to 2, are also filtered:
</p>

<h2>
</h2>

<p>
  <span><strong>SELECT *, ST_AREA(&#8220;geom&#8221;) AS &#8220;Area&#8221;<br /> </strong><strong>FROM &#8220;City&#8221;.&#8221;Census&#8221;<br /> </strong><strong>WHERE ST_Intersects(&#8220;geom&#8221; , ST_GeometryFromText(&#8216;SRID=26741;POLYGON((1884515 451900, 1884515 458931, 1897526 458931,1897526 451900,1884515 451900))&#8217;)::geometry)<br /> </strong><strong>AND ST_AREA(&#8220;geom&#8221;)>200000<br /> </strong><strong>AND &#8220;BGROUP&#8221;=&#8217;2&#8242;</strong></span>
</p>

<h2>
</h2>

<p>
  More information about this type of queries:
</p>

<h2>
</h2>

<p>
  <span><em><span><a href="https://postgis.net/docs/using_postgis_dbmanagement.html" target="_blank" rel="nofollow">https://postgis.net/docs/using_postgis_dbmanagement.html</a></span></em></span>
</p>

<h2>
</h2>

<h2>
</h2>

* * *

## <span>SQL Server Spatial</span>

<p>
  On this case, the SQL statement to query and create the View would be:
</p>

<h2>
</h2>

<p>
  <span><strong>SELECT *</strong></span><br /> <span> <strong>FROM [Census]</strong></span><br /> <span> <strong>WHERE  [Geometry].STIntersects(geometry::STGeomFromText(&#8216;POLYGON((1884515 451900, 1884515 458931, 1897526 458931,1897526 451900,1884515 451900))&#8217;,26741))=1</strong></span>
</p>

<h2>
</h2>

<ul>
  <li>
    <strong>STIntersects</strong> is the function that compares each geometry of the Table (it returns 1 in case of equality). There are other functions for other types of queries:<em> STContains, STCrosses, STIntersects, STTouches</em>, …
  </li>
  <li>
    <strong>geometry::STGeomFromText</strong> is the function to compose a polygon (or any other type of geometry) from its text representation in <em><span><a href="https://en.wikipedia.org/wiki/Well-known_text" target="_blank" rel="nofollow">WKT</a></span></em> format <ul>
      <li>
        Note: For non-projected geometries that are defined in latitude-longitude, you should use <em>geography::STGeomFromText</em>
      </li>
    </ul>
  </li>
  
  <li>
    <strong>POLYGON((1884515 451900, 1884515 458931, 1897526 458931,1897526 451900,1884515 451900))</strong> WKT representation of the geometry to be used for the spatial query
  </li>
  <li>
    <strong>26741</strong> is the code of the coordinate reference system (CRS). It must be the same as the geometries to be queried in order to work correctly. If it is not defined, this parameter must be set to &#8220;0&#8221;
  </li>
</ul>

<h2>
</h2>

<p>
  As in PostGIS case, the created View will appear in the USD area of the &#8216;Spatial Manager&#8217; data sources panel as any database Table so you can use it as any source to import or load the filtered features. Importing  / loading results &#8211; <strong><span>Green</span></strong> for the full table &#8220;Census&#8221;, <strong><span>Red</span></strong> for the created &#8220;CensusFiltered&#8221; View. <em>Please, take a look at the above images</em>
</p>

<h2>
</h2>

<p>
  More information about this type of queries:
</p>

<h2>
</h2>

<a href="https://docs.microsoft.com/en-us/sql/t-sql/spatial-geometry/ogc-methods-on-geometry-instances" target="_blank" rel="nofollow"><span><em>https://docs.microsoft.com/en-us/sql/t-sql/spatial-geometry/ogc-methods-on-geometry-instances</em></span></a>

<h2>
</h2>

* * *

<h2>
</h2>

<p>
  Learn more about the <strong>use and configuration of spatial databases</strong> in &#8216;Spatial Manager&#8217;:
</p>

## 

  * **Technical Wiki**: 
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Databases" target="_blank" rel="nofollow">Spatial Manager for AutoCAD</a></span>_
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_BricsCAD_-_FAQs:_Databases" target="_blank" rel="nofollow">Spatial Manager for BricsCAD</a></span>_
      * _<span><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager%E2%84%A2_for_ZWCAD_-_FAQs:_Databases" target="_blank" rel="nofollow">Spatial Manager for ZWCAD</a></span>_<span><br /> </span>
      * _<a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop%E2%84%A2_-_FAQs:_Databases" target="_blank" rel="nofollow">Spatial Manager Desktop</a>_