# Time Series and Machine Learning Analysis

This repository contains comprehensive analyses and machine learning projects centered around two datasets:

1. **Titanic Dataset** - A classic dataset used for binary classification tasks, where the goal is to predict survival based on various passenger attributes.
2. **Apple Stocks Dataset** - Historical stock prices of Apple Inc., used for time series analysis, feature engineering, clustering, anomaly detection, and predictive modeling.

## Table of Contents
- [Project 1: Titanic Dataset Analysis](#project-1-titanic-dataset-analysis)
  - [Exploratory Data Analysis (EDA)](#eda-titanic)
  - [Data Preprocessing](#preprocessing-titanic)
  - [Feature Engineering and Selection](#feature-engineering-titanic)
  - [Model Building and AutoML Integration](#model-building-titanic)
- [Project 2: Apple Stocks Time Series Analysis](#project-2-apple-stocks-time-series-analysis)
  - [Exploratory Data Analysis (EDA)](#eda-apple)
  - [Data Preprocessing](#preprocessing-apple)
  - [Clustering and Anomaly Detection](#clustering-anomaly-apple)
  - [Feature Engineering and Model Building](#feature-engineering-apple)
  - [Model Training with AutoML](#model-building-apple)
- [Conclusions](#conclusions)

---

## Project 1: Titanic Dataset Analysis

### Exploratory Data Analysis (EDA)  
- **Initial Data Overview**: Inspection of data structure, column types, and basic statistics.
- **Visualizations**: Distribution plots, correlation heatmaps, and survival rate breakdowns based on different passenger attributes.

### Data Preprocessing
- **Handling Missing Values**: Filling missing data using techniques like mean imputation or forward-fill.
- **Outlier Detection**: Identification and handling of potential outliers to ensure clean data.
- **Feature Scaling**: Normalizing features where necessary.

### Feature Engineering and Selection
- **Feature Creation**: Creation of new features like family size, age groups, and title extraction.
- **Feature Selection**: Analysis of feature importance using model-based techniques.

### Model Building and AutoML Integration
- **AutoVIML Implementation**: Automated model selection and tuning to find the best-performing model for survival prediction.
- **Performance Metrics**: Reporting accuracy, precision, recall, F1-score, and AUC.

[View Titanic Model Colab](https://github.com/Mohib1402/DataPreparation_EDA_Visualization/blob/main/Titanic/Titanic.ipynb)

## Project 2: Apple Stocks Time Series Analysis

### Exploratory Data Analysis (EDA)  
- **Initial Data Overview**: Loading and inspection of the data for structure, column types, and summary statistics.
- **Visualizations**: Time series plots to highlight trends, seasonality, and volume variations.
- **Correlation Analysis**: Correlation matrix to identify relationships between different stock features.

### Data Preprocessing
- **Date Handling**: Conversion of date columns to datetime format and setting them as the index.
- **Handling Missing Values**: Forward-filling or backward-filling techniques to impute missing values.
- **Anomaly Detection and Elimination**: Isolation Forest or clustering techniques to identify and remove anomalies.

### Clustering and Anomaly Detection
- **Clustering**: K-Means or hierarchical clustering to detect distinct patterns.
- **Anomaly Detection**: Implementing Isolation Forest to find potential anomalies.
- **Elimination**: Removing anomalies and validating data integrity post-cleaning.

### Feature Engineering and Model Building
- **New Feature Creation**: Creation of moving averages, rolling statistics, and lagged features.
- **Feature Selection**: Using RandomForestRegressor to evaluate feature importance.

### Model Training with AutoML
- **H2O AutoML Integration**: Leveraging AutoML for model training, comparison, and selection.
- **Model Evaluation**: Assessing model performance using RMSE, MSE, MAE, R², and other relevant metrics.

[View Apple Stocks Model Colab](https://github.com/Mohib1402/DataPreparation_EDA_Visualization/blob/main/AppleStocks/AppleStocks.ipynb)

## Conclusions
- **Titanic Dataset**: Successfully built and evaluated machine learning models to predict passenger survival.
- **Apple Stocks Dataset**: Applied a robust pipeline for time series analysis, anomaly detection, feature engineering, and predictive modeling, achieving strong performance metrics.


---
