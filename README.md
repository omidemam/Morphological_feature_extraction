# Morphological Feature Extraction

This repository demonstrates **watershed delineation** and **morphological feature extraction** from a Digital Elevation Model (DEM) using WhiteboxTools.

## What this repo does

- Loads a DEM  
- Generates **flow direction** and **flow accumulation** rasters  
- **Delineates a watershed** from a pour point or threshold  
- Computes key **morphometric features**, including:
  - Average slope
  - Longest flow path length
  - Longest flow path slope

> Core workflow is implemented in `c_profile_watershed_delineation_code`
