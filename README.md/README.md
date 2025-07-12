# Earth Observation - Delhi Airshed

This repository contains the full pipeline for land use classification and pollution source analysis in the Delhi NCR region using Sentinel-2 imagery, ESA WorldCover 2021 data, and deep learning models such as ResNet18.

## Structure

- `Data/` - Sentinel-2 RGB image patches  
- `Dataset/` - train/test CSV files  
- `scripts/` - Jupyter Notebooks, code logic  
- `models/` - Trained CNN models (e.g., ResNet)  
- `Visualizations/` - Graphs, maps, and results  
- `requirements.txt` - Python package dependencies

## Summary

The pipeline includes:
- Spatial gridding of Delhi NCR
- Image filtering using shapefile masks
- Label assignment from ESA WorldCover
- Train-test split and class balance visualization
- CNN model training (ResNet18) and F1 score evaluation
