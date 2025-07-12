 
# Earth Observation - Delhi Airshed 🌍🛰️

This repository presents a complete geospatial machine learning pipeline to classify land use patterns and assess pollution sources in the Delhi NCR airshed using Sentinel-2 imagery and ESA WorldCover 2021 data.

## 📁 Project Structure
earth-observation-delhi-airshed/
├── Data/
│ ├── delhi_ncr.geojson
│ ├── delhi_airshed.geojson
│ ├── worldcover_bbox_delhi_ncr_2021.tif
│ └── rgb/
│ └── ... image patches
├── Visualizations/
│ ├── grid_overlay.png
│ ├── class_distribution.png
│ ├── confusion_matrix.png
├── scripts/
│ └── assignment case 1.ipynb
├── README.md
├── requirements.txt
└── report.pdf


## ✅ Tasks Completed

- Spatial Gridding of Delhi-NCR
- Image Filtering using shapefiles
- Labeling using WorldCover
- Train-Test Splitting
- CNN Model (ResNet18) Training
- Evaluation: Confusion Matrix + F1 Score

## 🔧 Tech Used

- Python
- Torch, torchvision
- Rasterio, GeoPandas
- Matplotlib, Seaborn


