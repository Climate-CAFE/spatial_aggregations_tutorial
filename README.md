![image](https://github.com/user-attachments/assets/32d68b98-6b60-4633-8bcf-bb255dd628b0)


# spatial_aggregations_tutorial
Walk through on all-things spatial aggregations. The main focus is aggregating climate/exposure variables over (raster) grids into (GIS vector) polygons. 

____

This tutorial focuses on:

1. **Frequently asked questions**

* What is the difference between gis vector data and rasters?
* What is the difference between overlay vs rasterize?
* What are multiple rasterization strategies?
* What is the difference between downscaling and upsampling?
* What are computationally efficient options for spatial aggregations?
* How can I perform discrete variable aggregations?

2. **Example scripts and end-to-end pipelines for spatial aggregations**

* Python example script for spatial aggregations using rasterization (`rasterstats` package)
* Python example script for discrete variable aggregations: climate types on the USA
* Blazing fast end-to-end pipelines for spatial aggregations


_____

Resources: 
* vector vs raster
  - https://community.alteryx.com/t5/Data-Science/Vector-and-Raster-A-Tale-of-Two-Spatial-Data-Types/ba-p/336141
  - https://www.e-education.psu.edu/geog160/node/1935
  - https://r.geocompx.org/raster-vector
* overlay vs rasterize
  - https://en.wikipedia.org/wiki/Rasterisation
  - https://en.wikipedia.org/wiki/Vector_overlay
  - https://pygis.io/docs/e_raster_rasterize.html
  - https://pygis.io/docs/e_vector_overlay.html
* rasterization
  - https://docs.qgis.org/3.34/en/docs/user_manual/processing_algs/gdal/vectorconversion.html#rasterize-vector-to-raster
  - https://www.ecologi.st/spatial-r/old-raster-gis-operations-in-r-with-raster.html#rasterizing-1
  - vector aggregation vs raster aggregation 
  - https://desktop.arcgis.com/en/arcmap/latest/tools/spatial-analyst-toolbox/how-aggregate-works.htm
* vector overlay vs raster overlay 
  - https://saylordotorg.github.io/text_essentials-of-geographic-information-systems/s12-01-basic-geoprocessing-with-raste.html
  - http://www.gitta.info/Suitability/en/html/unit_BoolOverlay.html
* downscaling
  - https://www.researchgate.net/publication/335651129_An_Overview_of_Theoretical_and_Practical_Issues_in_Spatial_Downscaling_of_Coarse_Resolution_Satellite-derived_Products#pf2
 
Additional GIS resources: https://mapping.share.library.harvard.edu/
