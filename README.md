# Air Quality Prediction using OpenAQ Dataset

## Project Overview
This project aims to predict air quality using data from the OpenAQ dataset. We implement various machine learning models to forecast Air Quality Index (AQI) based on pollutant levels. The project includes data preprocessing, feature engineering, model development, and evaluation.

## Key Features
1. Data preprocessing and cleaning of OpenAQ dataset
2. Imputation of missing values for countries
3. AQI calculation based on pollutant levels
4. Feature scaling and selection
5. Implementation of multiple machine learning models
6. Model evaluation using various metrics
7. Cluster analysis of air quality data

## Data Source
- OpenAQ dataset (with over 50,000 entries)

## Methodology

### Data Preprocessing
1. Loading and cleaning the OpenAQ dataset
2. Imputing missing values for countries
3. Calculating AQI based on pollutant levels (PM2.5, PM10, O3, NO2, SO2, CO)
4. Handling outliers and anomalies

### Feature Engineering
1. Feature scaling (e.g., StandardScaler, MinMaxScaler)
2. Feature selection techniques (e.g., correlation analysis, feature importance)

### Model Development
Implemented machine learning models:
1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor
4. Support Vector Regression

### Model Evaluation
Metrics used for evaluation:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R²)
- Root Mean Squared Error (RMSE)

### Cluster Analysis
- Implementing K-means clustering on air quality data
- Analyzing patterns and groupings in air quality across different regions


## Technologies Used
- Python
- Pandas for data manipulation
- Scikit-learn for machine learning models and preprocessing
- Matplotlib and Seaborn for data visualization

## Future Work
- Incorporate weather data for more accurate predictions
- Implement time series analysis for temporal patterns
- Develop a web application for real-time air quality predictions


This project demonstrates the application of machine learning techniques in predicting air quality, potentially contributing to environmental monitoring and public health initiatives.
