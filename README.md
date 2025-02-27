# HealthVision AI

Welcome to HealthVision AI, an advanced health prediction and cell segmentation web application powered by cutting-edge machine learning models.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)

## About
HealthVision AI is designed to provide personalized healthcare insights using state-of-the-art machine learning models. The application covers various health prediction systems, including diabetes, chronic kidney disease, breast cancer, heart disease, Parkinson's disease, and more. Additionally, it offers tools for COVID-19 prediction, endoscopic image classification, diabetic retinopathy detection, Alzheimer's brain classification, and cell segmentation.

## Features
- **Health Prediction Systems:** Predict the likelihood of various health conditions based on user-provided data or uploaded medical images.
- **COVID-19 Prediction:** Input symptoms and relevant details to receive predictions about the likelihood of COVID-19.
- **Endoscopic Image Classification:** Classify endoscopic images into categories such as dyed-lifted-polyps, esophagitis, and more.
- **Diabetic Retinopathy Detection:** Predict the presence of diabetic retinopathy in retinal images.
- **Alzheimer's Brain Classification:** Predict the likelihood of Alzheimer's disease based on brain images.
- **Cell Segmentation:** Visualize cell structures by uploading medical images and viewing segmented cell boundaries.

## Installation
To run the HealthVision AI application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/HealthVision-AI.git

2. Navigate to the project directory:

   ```bash
   cd HealthVision-AI

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

## Usage

1. Run the streamlit app
   
    ```bash
   streamlit run main.py

2. Open your web browser and navigate to http://localhost:8501 to access the HealthVision AI web application.

3. Explore different sections using the sidebar menu and follow the instructions on each page to input data or upload images.

## Models
HealthVision AI uses various machine learning models for predictions. Here are some of the key models:

- Diabetes Prediction: Random Forest Classifier
- Chronic Kidney Disease Prediction: Random Forest Classifier
- Breast Cancer Prediction: Custom Breast Cancer Prediction Model
- Parkinson's Disease Prediction: Random Forest Classifier
- COVID-19 Prediction: k-Nearest Neighbors (kNN) Classifier
- Endoscopic Image Classification: ResNet50-based Model
- Diabetic Retinopathy Detection: Custom Convolutional Neural Network (CNN)
- Alzheimer's Brain Classification: Custom CNN-based Model
- Cell Segmentation: UNet Segmentation Model
