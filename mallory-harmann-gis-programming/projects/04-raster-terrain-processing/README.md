# Raster Terrain Processing

**Tools:** Python, ArcPy, ArcGIS Pro, Spatial Analyst

A raster-processing workflow that combines four raster bands into a multiband composite and derives terrain products from a digital elevation model, including hillshade and slope in degrees.

## Files

- `raster_terrain_processing.py` — coursework ArcPy script
- `screenshots/processing-results.png` — captured output from the completed workflow

## Input data and configuration

The script expects four input bands (`band1.tif` through `band4.tif`) and `DEM.tif` in a local source folder. Update the original absolute Windows workspace path before running. The generated GeoTIFFs (including a 53 MB slope raster) were excluded to keep the repository focused and lightweight; regenerate them from the source rasters in ArcGIS Pro.
