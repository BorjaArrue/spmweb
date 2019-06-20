---
published: true
title: Sharing Background Maps, Data Sources, etc.
date: 2018-01-31T11:57:55+00:00
author: admin
layout: old-post
permalink: /sharing-background-maps-data-sources-etc/
image: /images/blog/2018/01/Copy-Settings-2-85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Configuration
  - Tricks and Tools
---
<p>
  Most of the &#8216;Spatial Manager&#8217; application settings can be shared between different users in a company or organization, so they do not need to repeat the same configuration processes on every workstation or for every user in a workstation
</p>

<p>
  <!--more-->
</p>

<div>
  <a href="/images/blog/2018/01/SPM-User-settings.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/01/SPM-User-settings.png" alt="'Spatial Manager' Data Sources & User Background Maps" width="931" height="550" srcset="/images/blog/2018/01/SPM-User-settings.png 931w, /images/blog/2018/01/SPM-User-settings-300x177.png 300w, /images/blog/2018/01/SPM-User-settings-768x454.png 768w, /images/blog/2018/01/SPM-User-settings-624x369.png 624w" sizes="(max-width: 931px) 100vw, 931px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; Data Sources & User Background Maps
  </p>
</div>

<h2>
</h2>

<p>
  Thus, the <strong>Data Sources</strong> (Shortcuts or User Data Sources), <strong>User Background Maps</strong> and even <strong>Tasks</strong> settings can be replicated to any &#8216;Spatial Manager&#8217; user because they are stored in a set of simple files. All you need to do is copy these files from one computer to another
</p>

<h2>
</h2>

<p>
  You <strong>can even share some configuration files between different applications</strong>. For example, you can define a set of User Background Maps in &#8216;Spatial Manager for AutoCAD&#8217; and replicate it in &#8216;Spatial Manager Desktop&#8217;, assuming you are a user of these applications
</p>

<h2>
</h2>



<h2>
  Which configuration files can be shared and which cannot?
</h2>

<h6>
  <em>WARNING: Be sure to copy any original configuration file that you plan to replace in to order to restore it later if you want to return to the original configuration</em>
</h6>

<p>
  The following is a list of the configuration files and the options when sharing:
</p>

<h2>
</h2>

<ul>
  <li>
    <em>BackgroundMaps.config</em> and <em>BackgroundMapGroups.config</em> <ul>
      <li>
        Settings: User Background Maps and Groups, as well as the configuration of some default Background Maps when needed
      </li>
      <li>
        Can be shared between different users/workstations: <strong>Yes</strong>
      </li>
      <li>
        Can be shared between different applications: <strong>Yes</strong>
      </li>
      <li>
        Note: It is imperative to <span>share both files together</span>
      </li>
    </ul>
  </li>
  
  <li>
    <em>Shortcuts.config</em> <ul>
      <li>
        Settings: Shortcuts to local or network folders and disks
      </li>
      <li>
        Can be shared between different users/workstations: <strong>Yes</strong>
      </li>
      <li>
        Can be shared between different applications: <strong>Yes</strong>
      </li>
      <li>
        Note: Take care with the network disks and folders and their accesses from a particular user/workstation
      </li>
    </ul>
  </li>
  
  <li>
    <em>UserDataSources.config</em> <ul>
      <li>
        Settings: User Data Sources (USD) defining the accesses to spatial Servers and/or specific files with parameters
      </li>
      <li>
        Can be shared between different users/workstations: <strong>Yes</strong>
      </li>
      <li>
        Can be shared between different applications: <strong>Yes</strong>
      </li>
      <li>
        Note: As with the Shortcuts, take care with the network disks and folders and their accesses from a particular user/workstation. In addition, take care with the accesses to any particular spatial Server
      </li>
    </ul>
  </li>
  
  <li>
    <em>Tasks.config</em> <ul>
      <li>
        Settings: User Data Sources defining the accesses to spatial Servers and/or specific files with parameters
      </li>
      <li>
        Can be shared between different users/workstations: <strong>Yes</strong>
      </li>
      <li>
        Can be shared between different applications: <strong>No</strong>
      </li>
      <li>
        Note: All the Tasks parameters must coincide (Shortcuts, USD, etc.)
      </li>
    </ul>
  </li>
  
  <li>
    <em>UserSettings.config</em> <ul>
      <li>
        Settings: Application general configurations
      </li>
      <li>
        Can be shared between different users/workstations: <strong>No</strong>
      </li>
      <li>
        Can be shared between different applications: <strong>No</strong>
      </li>
      <li>
        Note: Although in some cases it can work, this configuration <span>should never be copied</span>
      </li>
    </ul>
  </li>
</ul>

<h2>
</h2>



<h2>
  Where to find the application configuration files?
</h2>

<div>
  <a href="/images/blog/2018/01/SPM-Application-Config-folder.png" target="_blank" rel="nofollow"><img src="/images/blog/2018/01/SPM-Application-Config-folder.png" alt="'Spatial Manager' Configuration folder (for AutoCAD, in this sample)" width="668" height="293" srcset="/images/blog/2018/01/SPM-Application-Config-folder.png 668w, /images/blog/2018/01/SPM-Application-Config-folder-300x132.png 300w, /images/blog/2018/01/SPM-Application-Config-folder-624x274.png 624w" sizes="(max-width: 668px) 100vw, 668px" /></a>
  
  <p>
    &#8216;Spatial Manager&#8217; Configuration folder (for AutoCAD, in this sample)
  </p>
</div>

<h2>
</h2>

<h6>
  <em>WARNING: Be sure to copy any original configuration file that you plan to replace in to order to restore it later if you want to return to the original configuration</em>
</h6>

<h2>
</h2>

<p>
  The &#8220;<em>*.config</em>&#8221; files can be found inside the user &#8220;AppData&#8221; folder:
</p>

<h2>
</h2>

<ul>
  <li>
    <em>&#8216;Spatial Manager for AutoCAD&#8217;</em> <ul>
      <li>
        C:\Users\<span><em>username</em></span>\AppData\Local\OpenCartis\Spatial Manager for AutoCAD
      </li>
    </ul>
  </li>
  
  <li>
    <em>&#8216;Spatial Manager for BricsCAD&#8217;</em> <ul>
      <li>
        C:\Users\<span><em>username</em></span>\AppData\Local\OpenCartis\Spatial Manager for BricsCAD
      </li>
    </ul>
  </li>
  
  <li>
    <em>&#8216;Spatial Manager for ZWCAD&#8217;</em> <ul>
      <li>
        C:\Users\<span><em>username</em></span>\AppData\Local\OpenCartis\Spatial Manager for ZWCAD
      </li>
    </ul>
  </li>
  
  <li>
    <em>&#8216;Spatial Manager Desktop&#8217;</em> <ul>
      <li>
        C:\Users\<span><em>username</em></span>\AppData\Local\OpenCartis\Spatial Manager Desktop
      </li>
    </ul>
  </li>
</ul>

<h2>
</h2>



<h2>
  Backup Configuration files
</h2>

<p>
  It is important to mention here that, when working with any &#8216;Spatial Manager&#8217; application, the modified configuration files are updated every time you exit from the application, and the corresponding backup files are created on a &#8220;Backup&#8221; folder including the previous settings values
</p>

<h2>
</h2>



<h2>
  One more note for expert users
</h2>

<h6>
  <em>WARNING: Be sure to copy any original configuration file that you plan to replace in to order to restore it later if you want to return to the original configuration</em>
</h6>

<p>
  The &#8220;*.config&#8221; files are formatted using XML structures. If you know how to edit XML files you can even merge data between different configuration files. Thus, for example you could merge User Background Maps definitions coming from different configuration files
</p>

<h2>
</h2>

* * *

<p>
  If you want to learn more about the &#8216;Spatial Manager&#8217; configuration files, please review the following technical resources:
</p>

<h2>
</h2>

<p>
  <a href="/applications-configuration-files-backup-copy/" target="_blank" rel="nofollow"><em>· Blog entry</em></a>
</p>

<h2>
</h2>

<p>
  Technical Wikis:
</p>

<h2>
</h2>

<p>
  <em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_AutoCAD_-_FAQs:_Interface#Configuration_files" target="_blank" rel="nofollow">· Spatial Manager for AutoCAD</a></em><br /> <a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_BricsCAD_-_FAQs:_Interface#Configuration_files" target="_blank" rel="nofollow"><em>· Spatial Manager for BricsCAD<br /> </em></a><em><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager™_for_ZWCAD_-_FAQs:_Interface#Configuration_files" target="_blank" rel="nofollow">· Spatial Manager for ZWCAD<br /> </a><a href="http://wiki.spatialmanager.com/index.php/Spatial_Manager_Desktop™_-_FAQs:_Interface#Configuration_files" target="_blank" rel="nofollow">· Spatial Manager Desktop</a></em>
</p>