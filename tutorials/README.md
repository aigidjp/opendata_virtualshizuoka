# Tutorials

## Overview

There are various methods for visualizing 3D point cloud data. One option is to use dedicated applications, while another is to leverage web-based libraries for browser visualization.

Popular software for displaying 3D point clouds includes [CloudCompare](https://www.danielgm.net/cc/) and [QGIS](https://qgis.org). For web browsers, libraries like  [three.js](https://threejs.org) and [deck.gl](http://deck.gl/) are commonly used.

If you need to perform advanced processing of point cloud data within a program, you can utilize the [PDAL (Point Data Abstraction Library)](https://pdal.io/).

Additionally, point cloud data can be visualized in a browser using a format called [3DTiles](https://cesium.com/why-cesium/3d-tiles/). LAS format data can be converted to 3DTiles for this purpose.

## Application

The las file can be obtained by downloading and extracting the zip file of the point cloud data.

### CloudCompare

CloudCompare allows you to display point cloud data by simply dragging and dropping las files.

![CloudCompare_Dialog_OpenLasFile](/images/CloudCompare_openlasfile.png)

![CloudCompare_Dialog_ShiftScale](/images/CloudCompare_shiftscale.png)

![CloudCompare_Kakegawa_Castle](/images/CloudCompare_Kakegawa_castle.png)

### QGIS

QGIS also allows you to display point cloud data by simply dragging and dropping las files. If a dialog for specifying the CRS appears, please select EPSG:6676.

![QGIS_Dialog_CRS](/images/QGIS_CRS_EPSG6676.png)

![QGIS_MtFujiSummit](/images/QGIS_MtFuji.png)

![QGIS_Kakegawa_Castle](/images/QGIS_Kakegawa_castle.png)