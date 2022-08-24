# Basic geoprocessing in python
In this repository you'll find some common techniques that we use for managing geospatial datasets.  
- `merge`: Sometimes we have a dataset with information of our inteest and want to represent it spatially, in a map. In this folder you'll learn how to merge the information contained in a csv with a shapefile, using a common name. For this example, I used a shapefile of the counties of São Paulo and a csv with the historical sugarcane yield (2016-2020). I merged both datasets by their common column: the countie's numerical code.  
- `centroids`: Extract the central coordinates (latitude and longitude in SIRGAS 2000) of each county from the state of São Paulo. The shapefile used is the same hosted in the `merge` folder.  
- `clipping`: Examples of how to clip, mask or crop a raster stack using the geometries of a shapefile. In this example, I had a raster stack with 19 climatic variables for the entire planet dowloaded from the WorldClim platform. I wanted just the pixel covering the São Paulo State, and therefore, I used a shapefile to clip it.
- `Polygon to raster`: Transform a shapefile into a raster, using another raster as example. 
