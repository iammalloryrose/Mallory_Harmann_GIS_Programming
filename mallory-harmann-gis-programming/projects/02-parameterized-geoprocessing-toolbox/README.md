# Parameterized Garage–Building Geoprocessing Toolbox

**Tools:** Python, ArcPy, ArcGIS Pro Python Toolbox (`.pyt`)

A custom ArcGIS Pro Python toolbox that exposes the garage-to-building proximity workflow through configurable tool parameters. The tool accepts user-selected workspace, geodatabase name, garage CSV, layer name, campus building source, and buffer distance.

## Files

- `GarageBuildingProximity.pyt` — selected final toolbox source
- `data/garages.csv` — coursework input table
- `screenshots/tool-execution.png` — successful execution screenshot

## Configuration required

The source includes an output path tied to the original coursework folder and requires a campus building dataset. Update local paths and verify the output destination in ArcGIS Pro before running in another environment. The campus geodatabase and intermediate generated geodatabases are intentionally excluded from this curated repository.
