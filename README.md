 🛰️ Land Cover Classification & Change Detection Using Machine Learning 

This project was developed during a geospatial hackathon. The goal was to classify land cover using satellite images from 2017 and 2018 through machine learning models and perform change detection to quantify land use/cover transitions.

 🔁 Workflow Overview

  A[Satellite Images (2017, 2018)] --> B[Preprocessing (Stacking, FCC)]
  B --> C[Machine Learning Models]
  C --> D1[Classified Map 2017]
  C --> D2[Classified Map 2018]
  D1 --> E[Change Detection]
  D2 --> E
  E --> F[Gain and Loss Analysis]

📦 Models Used
🔹 SVM (Support Vector Machine)

🔹 Random Forest

🔹 LightGBM

🔹 MLP Neural Network

🔹 XGBoost

📥 Input Data
Satellite images for the years 2017 and 2018

Manually labeled training and testing sample points

Spectral bands and derived indices

⚙️ Processing Steps
Band Stacking and False Color Composite (FCC) generation

Sample Splitting (Train/Test)

Model Training and Prediction

Classification Output Maps

Change Detection and Gain/Loss Summary

📊 Outputs
classified_map_2017.tif – ML-based classification for 2017

classified_map_2018.tif – ML-based classification for 2018

change_matrix.csv – Class transition matrix

gain_loss.csv – Summary of gain and loss per land class

🛠️ Tools & Libraries
Python (scikit-learn, xgboost, lightgbm, keras)

Numpy, Pandas, Matplotlib

Rasterio, GDAL

QGIS (for training sample generation and visualization)
