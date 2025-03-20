# Precision Agriculture Using Machine Learning

## Project Overview
Precision Agriculture is a revolutionary approach that integrates Machine Learning (ML) to optimize farming practices. This project aims to enhance agricultural productivity by recommending suitable crops and predicting crop yields based on soil properties, climatic conditions, and geographical data.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Results](#results)

## Introduction
Agriculture plays a vital role in the Indian economy, yet traditional farming methods often lead to inefficiencies. This project leverages ML techniques to analyze soil and climate data, providing farmers with data-driven crop recommendations and yield predictions to maximize productivity and sustainability.

## Features
- **Crop Recommendation System**: Suggests the best crop based on soil nutrients, weather, and geographical conditions.
- **Yield Prediction System**: Predicts expected crop yield based on climatic factors, soil properties, and pesticide usage.
- **User-Friendly Interface**: A web-based dashboard for users to input data and receive recommendations.
- **Performance Analytics**: Evaluates model accuracy using classification metrics for crop recommendations and regression metrics for yield prediction.

## Technologies Used
- **Programming Languages**: Python, HTML, CSS, JavaScript
- **Frameworks & Libraries**: Flask, Scikit-learn, Pandas, NumPy
- **Machine Learning Models**: Random Forest Classifier for crop recommendation, Decision Tree Regressor for yield prediction
- **Database**: CSV-based dataset for model training

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/precision-agriculture.git
   ```
2. Navigate to the project directory:
   ```bash
   cd precision-agriculture
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and access the application at `http://127.0.0.1:5000/`.

## Usage
1. **Crop Recommendation:**
   - Enter soil parameters like Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.
   - Click "Predict" to get crop suggestions.

2. **Yield Prediction:**
   - Enter environmental conditions like rainfall, temperature, pesticide usage, and soil details.
   - Click "Predict" to get the estimated yield in hectograms per hectare.

## Dataset
- **Crop Recommendation Data**: Contains soil nutrient levels, climate details, and crop suitability.
- **Yield Prediction Data**: Includes regional climate data, historical yield records, and farming parameters.

## Model Details
- **Crop Recommendation**:
  - Model: Random Forest Classifier
  - Accuracy: 99.32%
  - Features: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall

- **Yield Prediction**:
  - Model: Decision Tree Regressor
  - Accuracy: 96.95%
  - Features: Rainfall, Temperature, Pesticide usage, Area, Crop type

## Results
- Improved crop selection, leading to better yields and sustainability.
- Data-driven recommendations, minimizing financial risks for farmers.
- Accurate yield predictions, aiding better planning and resource management.

