---
published: true
title: Applications configuration files and backup copy
date: 2014-02-08T16:48:34+00:00
author: admin
layout: old-post
permalink: /applications-configuration-files-backup-copy/
image: /images/blog/2014/02/ApplicationConfigurationLogo-85.png
categories:
  - CAD L2 (Medium)
  - Desktop L2 (Medium)
tags:
  - Configuration
---
All the settings for the Spatial Manager™ applications are stored in XML files and a backup copy is automatically created whenever any of them is modified<!--more-->

This is the list of **configuration files** for Spatial Manager:

**·** _Shortcuts.config_: Shortcuts configuration
  
**·** _Tasks.config_: saved Tasks
  
**·** _UserDataSources.config_: User Data Source (UDS) configuration
  
**·** _UserSettings.config_: Global application settings
  
**·** _BackgroundMaps.config_: User Background Maps configuration
  
**·** _BackgroundMapGroups.config_: Background Maps Groups configuration

You will find them in the following **folders**:

**·** **Desktop**: &#8216;_user folder_\AppData\Local\OpenCartis\Spatial Manager Desktop&#8217;
  
**·** **AutoCAD**: &#8216;_user folder_\AppData\Local\OpenCartis\Spatial Manager for AutoCAD&#8217;
  
**·** **BricsCAD**: &#8216;_user folder_\AppData\Local\OpenCartis\Spatial Manager BricsCAD&#8217;

<a href="/images/blog/2014/02/XML.png" target="_blank" rel="nofollow"><img src="/images/blog/2014/02/XML-300x238.png" alt="XML" width="300" height="238" srcset="/images/blog/2014/02/XML-300x238.png 300w, /images/blog/2014/02/XML-624x497.png 624w, /images/blog/2014/02/XML.png 767w" sizes="(max-width: 300px) 100vw, 300px" /></a>In all cases the **automatic backup files** are stored in the sub-folder &#8220;backup&#8221; within the folders listed above. A backup file includes in its name the date and the time at which it is generated

So, for example, a backup file named &#8220;Shortcuts.config.2016\_21\_08\_19\_22_48.bak&#8221; corresponds to a backup copy of the configuration file &#8220;Shortcuts.config&#8221;, which has been modified on August 21, 2016 at 19:22:48 hours If you want to restore any backup file, just **rename it as the original configuration file and copy it to the appropriate folder**, replacing the current application configuration file. You should carry out this operation after closing the application and we recommend you make a copy of the replaced file before replacing it

_Note: the backup files are not kept more than 15 days_