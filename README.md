<<<<<<< HEAD
# Illegal Deforestation and Land Encroachment Detection Model
=======
#  Illegal Deforestation & Land Encroachment Detection

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

>>>>>>> 134c7224e8e372b6ab84867a1e3a1bea69557084
