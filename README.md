
# Illegal Deforestation and Land Encroachment Detection Model

A computer vision-based project that detects illegal deforestation and land encroachment using satellite imagery and temporal change detection.


##  Objective

This project aims to:
- Monitor changes in forest cover over time using satellite imagery
- Detect unauthorized deforestation and land encroachment
- Generate visual reports and spatial alerts for authorities or NGOs



##  Dataset

We use open satellite data from:
- [Google Earth Engine (GEE)](https://earthengine.google.com/)
- [Sentinel-2](https://scihub.copernicus.eu/)
- [Landsat-8](https://landsat.gsfc.nasa.gov/)
- [ISRO Bhuvan](https://bhuvan.nrsc.gov.in/) (India-specific)



##  Techniques Used

- Satellite Image Preprocessing (`rasterio`, `geemap`, `earthengine-api`)
- Temporal Change Detection
- Semantic Segmentation using Deep Learning (e.g., UNet)
- Visualization with `matplotlib`, `folium`, and `QGIS`
- Geo-tagged Alert Reports


## Folder Structure
IllegalDeforestation-and-LandEnchroachment-Detection/
│
├── data/ -Raw and preprocessed satellite images
├── notebooks/ -EDA and experimentation
├── src/ -Core codebase (preprocessing, models, inference)
├── scripts/ -Training and inference scripts
├── models/ -Trained model weights
├── reports/ -Visual results and logs
├── requirements.txt -Python dependencies
├── README.md -You're reading it
└── .gitignore -Ignore unnecessary files


## Status
*Project folder initialized*  
*Phase 1: Dataset collection and preprocessing*

## Roadmap
1. Dataset Collection (Satellite images + Encroachment labels)
2. Preprocessing (Image slicing, normalization, georeferencing)
3. Model Training (Object Detection or Semantic Segmentation)
4. Model Evaluation (Accuracy, Precision, Recall, IOU)
5. Deployment or Visualization

##  Contribution
Open to collaborators! Reach out via [LinkedIn](https://www.linkedin.com/in/yash-nabde/) or raise an issue.

