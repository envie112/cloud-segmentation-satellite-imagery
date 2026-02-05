☁️ Cloud Segmentation from Satellite Imagery

📌 Overview

This project implements a pixel-wise cloud segmentation pipeline on Landsat-8 satellite imagery using the 38-Cloud dataset. The goal is to accurately classify satellite image patches into clear, partly cloudy, and cloudy categories to improve downstream satellite image analysis and automation tasks.

🚀 Features

Extracted 40+ features including:

Spectral indices (NDVI, NDWI)

Statistical measures

Texture patterns

Built a classification pipeline achieving ~92% accuracy.

Generated reliable cloud masks for satellite imagery preprocessing.

🛠️ Tech Stack

Programming: Python

Libraries: NumPy, OpenCV, TensorFlow, rasterio, GDAL

Environment: Jupyter Notebook

📂 Project Structure
project-root/
│
├── test/          # Jupyter notebooks for exploration and training
├── results/            # Outputs, plots, and evaluation results
├── README.md
└── .gitignore


⚠️ Note: The dataset is intentionally excluded from this repository due to size constraints.

📊 Results

Accuracy: ~92% on validation set

Successfully segmented cloud regions for improved satellite data usability.

📌 Future Improvements

Extend to real-time satellite data streams.

Explore deep learning segmentation models (e.g., U-Net, DeepLab).

Integrate with geospatial pipelines for climate and environmental monitoring.

👩‍💻 Author

Ramya
