# Cleanup & publication notes

This is a curated copy of the supplied GEOG 676 repository. The original ZIP is unchanged.

## Excluded

- Lab 1 placeholder.
- Labs 2 and 3 introductory Python exercises (retained in the original archive if needed, but not selected as portfolio projects).
- Duplicate/experimental Lab 4 scripts, merge-conflicted README, Excel workbook, redundant CSV exports, and test geodatabases.
- Earlier Lab 5 toolbox versions, duplicate scripts, ArcGIS project, and generated geodatabases.
- ArcGIS Pro temporary folders (`GpMessages`, `ImportLog`, `.backups`, `__pycache__`) and compiled Python files.
- Lab 6 ArcGIS project and geodatabases, which contain machine-specific project dependencies.
- Lab 7 generated raster outputs, including the large slope GeoTIFF.

## Before public release

1. Open each `.py` / `.pyt` project in ArcGIS Pro and replace original absolute Windows paths with paths appropriate to the cloned repository.
2. For the Lab 4 and Lab 5 workflows, connect a properly licensed campus building dataset; it is not redistributed here. Confirm the garage CSV is permitted for public redistribution.
3. Re-run the tools after path changes and update screenshots if outputs differ.
4. Confirm that the scripts' required ArcGIS Pro extensions are available.

The core scripts are preserved from the supplied archive. They have not been refactored or represented as newly tested after relocation.
