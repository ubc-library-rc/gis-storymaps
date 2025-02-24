---
layout: default
title: Add Data
nav_order: 1
parent: Create a Web Map
---
# Adding Data

Today we will work with commuter data from the city of Vancouver. Adding data requires first finding relevant data and downloading it, then uploading it to your ArcGIS online account. Once uploaded to your "content", you can visualize spatial data in the online mapping tool. You can also load spatial data directly to a webmap in progress. However, make sure your data's visibility is set to public if you want to share your project with others. Even if your webmap or StoryMap visibility is set to public, you will get an error unless the data visibility is *also* set to public. 


## Find Data 
The [Vancouver Open Data Portal](https://opendata.vancouver.ca/pages/home/) is an excellent source for a variety of municipal data, including geographic data layers such as points, lines and polygons (vector data), and aerial imagery (raster data). 

As long as the data you are looking at has a geographic element, you can download it. When downloading from the "Export" tab, make sure to download it as a **GeoJSON** file. This will ensure we can add it as a layer to your ArcGIS Online webmap. 


## Add Data from File
In the sidebar menu of your ArcGIS Online map, click on **Layers**, then on click on the drop down arrow next to **Add layer** to add a layer from a file.

To Do
{: .label .label-purple}
You will find the sample data for this workshop already prepared for you in the workshop folder in the subfolder `geospatial-data`. Take a moment to add each file as a layer to your ArcGIS Online webmap and play around with features.

> - `Vancouver_Commuter_2016.geojson` is a polygon layer with commuter data from the 2016 census joined to local area boundaries (aka neighborhoods).

> - `bikeways.geojson` is a line layer showing Vancouver bike paths.

> - `heritage-sites.geojson` is a point layer showing Vancouver heritage sites.




## Add Data from the Living Atlas
You can also add data from the [Living Atlas](https://livingatlas.arcgis.com/en/home/), a large collection of geographic information compiled and created by Esri.

Click on **Layers**, then click on the **Add** button.

From the dropdown arrow next to **My Content**, select **Living Atlas** and search for layers to add.

*Note: If you only have a public ArcGIS account, you will have access to fewer layers in the Living Atlas.*


## Displaying Layers

You can add as many layers as you want and they will display simultaneously.

Next to the layer name, you will see an eye icon and three dots. Click on the eye to make the layer visible or invisible.

If you click on the three dots next to the layer name, you have the following options:

> - Zoom to layer: Will zoom your map to the layer location
> - Show properties: Displays things like symbology
> - Attribute table: Shows the data in a tabular format
> - Rename and Remove

