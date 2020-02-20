# StoryMaps
tutorial

https://github.com/zarazaga/StoryMaps
Jessie Zarazaga – SMU Iniative for Spatial Literacy – jzarazaga@smu.edu

## Overview

This workshop aims to introduce participants to basic tools, concepts and techniques for creating web-stories which integrate text, images and maps, using StoryMaps, an online software distributed by Esri.   

GIS@SMU website - https://www.smu.edu/libraries/fondren/services/gis

# StoryMaps

tutorial link - https://github.com/zarazaga/StoryMaps

Jessie Zarazaga – SMU Iniative for Spatial Literacy -     jzarazaga@smu.edu

GIS@SMU website - https://www.smu.edu/libraries/fondren/services/gis


## Setup

prepare for this workshop by signing up for an ArcGIS online account.

SMU Affiliates with a valid SMU_ID can login to the Enterprise account at: [ArcGIS Online](https://www.arcgis.com/home/index.html) 

Use the ENTERPRISE login for 'smudallas' to set up an account with your SMU password [smudallas](https://www.arcgis.com/sharing/rest/oauth2/authorize?client_id=arcgisonline&display=default&response_type=token&state=%7B%22useLandingPage%22%3Atrue%7D&expiration=20160&locale=en-us&redirect_uri=https%3A%2F%2Fwww.arcgis.com%2Fhome%2Faccountswitcher-callback.html&force_login=true&hideCancel=true&showSignupOption=true&canHandleCrossOrgSignIn=true&signuptype=esri)

Or signup with a [free ESRI developer account](https://developers.arcgis.com/sign-up/)

### Data

The data package for the workshop can be downloaded from [https://github.com/zarazaga/storymap/master.zip](https://github.com/mapninja/QGIS-101/archive/master.zip)

The project data folder contains the following datasets:

* **deathAddresses.csv**  - this is a table latitude and longitude coordinates for addresses affected by the cholera outbreak. This table also contains the number of deaths at each address.  
* **image.tif** - this is a non-georeferenced image of the map from John Snow's original report on the cholera outbreak of 1854. 
* **Study_Area.shp** - This file is simply a rectangular feature that describes our area of interest.  


#### Additional Files
There is an extra backup data folder that contains versions of files that we will create during the workshop. These files are provided in case any of the steps can't be completed due to software errors or other problems. Welcome to working with open source.  
* **Snow-cholera-map-1_modified** - this is a geo-referenced image of the map from John Snow's original report on the cholera outbreak of 1854.  
* **Water_Pumps.geojson** - this is a spatial data file containing the locations of all of the water pumps recorded in John Snow's original map of the cholera outbreak.  Who woo hoo 

## Getting started on a project  

In this section we will cover starting a new QGIS project. We will create a new map document, go over the basic QGIS interface, customize that interface, add a plug-in and bring a base map into your QGIS project.

### Create a Map Document

1. To create a new map document, Open ArcGIS Pro...
2. On the resulting splash page, select "Start without a template." You will be presented with a blank ArcGIS Pro interface. 
3. Switch to the **Insert** Tab at the top of ArcGIS Pro, if necessary. Click on the **New Map** button to add a basemap and create a view similar to that, below:

![arcgispro_newmap-drop-shadow.png](./media/arcgispro_newmap-drop-shadow.png)

Download Tutorial Data

## Setup

Users should prepare for this workshop by signing up for an ArcGIS online account.

SMU Affiliates with a valid SMU_ID can login to the Enterprise account at: [ArcGIS Online](https://www.arcgis.com/home/index.html) 
Signin [Loging to smudallas](https://www.arcgis.com/sharing/rest/oauth2/authorize?client_id=arcgisonline&display=default&response_type=token&state=%7B%22useLandingPage%22%3Atrue%7D&expiration=20160&locale=en-us&redirect_uri=https%3A%2F%2Fwww.arcgis.com%2Fhome%2Faccountswitcher-callback.html&force_login=true&hideCancel=true&showSignupOption=true&canHandleCrossOrgSignIn=true&signuptype=esri)

### Software

This workshop was created using ArcGIS Pro version 2.4.x. If you are installing for the first time, using the above referenced installer, be sure to log into your Stanford ArcGIS.com account to enable updating of the software to the most recent version.

[https://qgis.org/en/site/forusers/download.html](https://qgis.org/en/site/forusers/download.html)

### Data

The data package for the workshop can be downloaded from [https://github.com/mapninja/QGIS-101/archive/master.zip](https://github.com/mapninja/QGIS-101/archive/master.zip)

The project data folder contains the following datasets:

* **deathAddresses.csv**  - this is a table latitude and longitude coordinates for addresses affected by the cholera outbreak. This table also contains the number of deaths at each address.  
* **snow_map.png.tif** - this is a non-georeferenced image of the map from John Snow's original report on the cholera outbreak of 1854. 
* **Study_Area.shp** - This file is simply a rectangular feature that describes our area of interest.  


#### Additional Files
There is an extra backup data folder that contains versions of files that we will create during the workshop. These files are provided in case any of the steps can't be completed due to software errors or other problems. Welcome to working with open source.  
* **Snow-cholera-map-1_modified** - this is a geo-referenced image of the map from John Snow's original report on the cholera outbreak of 1854.  
* **Water_Pumps.geojson** - this is a spatial data file containing the locations of all of the water pumps recorded in John Snow's original map of the cholera outbreak.  Who woo hoo 

## Getting started on a project  

In this section we will cover starting a new QGIS project. We will create a new map document, go over the basic QGIS interface, customize that interface, add a plug-in and bring a base map into your QGIS project.

### Create a Map Document

1. To create a new map document, Open ArcGIS Pro...
2. On the resulting splash page, select "Start without a template." You will be presented with a blank ArcGIS Pro interface. 
3. Switch to the **Insert** Tab at the top of ArcGIS Pro, if necessary. Click on the **New Map** button to add a basemap and create a view similar to that, below:

![arcgispro_newmap-drop-shadow.png](./media/arcgispro_newmap-drop-shadow.png)
