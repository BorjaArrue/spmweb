---
id: 4287
title: Import KML to ZWCAD
date: 2017-10-08T15:15:53+00:00
author: admin
layout: article
guid: http://www.spatialmanager.com/?page_id=4287
application: spm_forzwcad
text:
  - The primary need for ZWCAD users who work with KML files is to import these kinds of files into their drawings
  - Convert Google Earth features to ZWCAD Entities using a very interesting data provider designed and optimized for KML/KMZ files
  - You can distribute the Entities over ZWCAD Layers according to the folder structures of the KML data source
---
Please, watch the video of this &#8220;KML ZWCAD&#8221; example:



<span class="hps alt-edited">Every day many <a href="https://www.zwsoft.com/zwcad/" target="_blank" rel="nofollow">ZWCAD</a> users who handle geo-spatial information data, make use of thousands of <a title="KML in Wikipedia" href="http://en.wikipedia.org/wiki/Keyhole_Markup_Language" target="_blank" rel="nofollow">KML/KMZ Google Earth</a> files and their primary need is importing these types of file in their ZWCAD drawings</span>

## KML to CAD (KML to ZWCAD)

Using <a href="http://www.spatialmanager.com/spm-forzwcad" target="_blank" rel="nofollow">Spatial Manager™ for ZWCAD</a>, whose main function is to import Features from geo-spatial data sources as ZWCAD Entities, any user can convert KML to ZWCAD Entities by selecting a very interesting data provider designed and optimized for KML/KMZ files

The KML data provider can read complex KML/KMZ files (including complex folder structures), and allows you to accurately select the information you are importing and distribute it over ZWCAD Layers according to the folder of the data source in the KML/KMZ file or following the criteria defined by the value of any data Field of the KML/KMZ table when you import KML to ZWCAD drawings

<a href="http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-KML-to-ZWCAD-Data-provider-SPM-for-ZWCAD.png" target="_blank" rel="nofollow"><img class="aligncenter wp-image-4300" src="http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-KML-to-ZWCAD-Data-provider-SPM-for-ZWCAD.png" alt="Import KML to BricsCAD - Data provider - Spatial Manager for ZWCAD" width="625" height="508" srcset="http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-KML-to-ZWCAD-Data-provider-SPM-for-ZWCAD.png 840w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-KML-to-ZWCAD-Data-provider-SPM-for-ZWCAD-300x244.png 300w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-KML-to-ZWCAD-Data-provider-SPM-for-ZWCAD-768x624.png 768w, http://www.spatialmanager.com/wp-content/uploads/2017/10/Import-KML-to-ZWCAD-Data-provider-SPM-for-ZWCAD-624x507.png 624w" sizes="(max-width: 625px) 100vw, 625px" /></a>

&nbsp;

_Importing using Spatial Manager™ for ZWCAD and the &#8220;ZWCAD KML&#8221; data provider_

## Example: Import KML to ZWCAD

Part one: we will import the full content of a Google Earth KML file into ZWCAD, without distributing this information in different Layers nor transforming the <a title="CRS in Wikipedia" href="http://en.wikipedia.org/wiki/Spatial_reference_system" target="_blank" rel="nofollow">Coordinate Reference System</a> of the incoming data. The files in KML/KMZ formats are always defined using the WGS 84 geographic system, whose standard identifier (<a title="EPSG in Wikipedia" href="http://en.wikipedia.org/wiki/International_Association_of_Oil_%26_Gas_Producers#European_Petroleum_Survey_Group" target="_blank" rel="nofollow">EPSG</a>) is 4326, and, as you can see in the drawing when the import process is finished, the cursor coordinates indicate values of Latitude and Longitude

In this case, the point type Features are converted to ZWCAD Points, the linear type Features to ZWCAD open Polylines and the polygon type Features to ZWCAD closed Polylines, adding ZWCAD Hatches, using the SOLID pattern with a certain level of Transparency, for those polygons

Part two: we will separately import two folders from the same KML file that was used in part one, into an existing drawing, whose coordinate values are established as the UTM30-ED50 projected system which, as you can see in the drawing, uses the meter as the unit length. The standard identifier (EPSG) for this system is 23030

The first folder holds point type Features belonging to a network and will be imported as  ZWCAD Block References using an existing Block Definition in the drawing. This Block Definition contains two attributes which can be &#8220;mapped&#8221; to any Field from the source table to take their values. As you can see in the video, if the name of a Field matches that of an Attribute, the application selects this relationship Field-Attribute as the default relationship. Furthermore, these Blocks References will be distributed into different new or existing Layers of the drawing depending on the values of one of the Fields of the point type Features in the source

The second folder holds linear type Features corresponding to the previous network, and will be imported using open Polylines into a single Layer

In both import processes carried out in the second part of the example, the Coordinates of the imported Entities are transformed from the original system of the KML file (WGS84) to that of the drawing (UTM30-ED50)

&nbsp;

<h2 style="text-align: justify;">
  <a href="http://www.spatialmanager.com/download/spatial-manager-zwcad/" target="_blank" rel="nofollow"><img class="aligncenter wp-image-3306 size-full" src="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png" alt="Download" width="330" height="50" srcset="http://www.spatialmanager.com/wp-content/uploads/2016/06/Download.png 330w, http://www.spatialmanager.com/wp-content/uploads/2016/06/Download-300x45.png 300w" sizes="(max-width: 330px) 100vw, 330px" /></a>
</h2>