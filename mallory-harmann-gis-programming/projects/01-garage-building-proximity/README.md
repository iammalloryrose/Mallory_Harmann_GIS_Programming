# Garage–Building Proximity Analysis

**Tools:** Python, ArcPy, ArcGIS Pro, File Geodatabase

This script automates a proximity workflow for garage point locations and campus building footprints. The workflow creates a file geodatabase, converts XY coordinates to point features, reprojects points to match the building layer, buffers the points, intersects the buffers with buildings, and exports the resulting table.

## Source

- `garage_building_proximity.py` — final coursework script
- `data/garages.csv` — input XY table from the coursework archive
- `screenshots/intersection-results.png` — captured output from the completed workflow

## Configuration required

The original script uses absolute Windows paths and expects a campus building feature class in a local geodatabase. Update the workspace, input CSV, and campus geodatabase paths for your own ArcGIS Pro environment before running. The campus geodatabase is not included in this public-facing package because its redistribution rights were not established.
