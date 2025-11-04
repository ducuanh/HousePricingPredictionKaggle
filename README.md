House Price Prediction in Poland

This project demonstrates a full machine-learning workflow for predicting house prices in Poland using a structured dataset of property listings.
It is implemented in a Jupyter Notebook: HousePredictionPoland.ipynb.

Project Overview

The goal of this project is to build predictive models that estimate real-estate prices based on property characteristics such as:

City

Area (m²)

Number of rooms

Floor level

Building age / construction year

Additional features (balcony, elevator, etc.)

The notebook walks through data processing, visualization, model training, and evaluation.

Features & Workflow
Step	Description
Data Loading	Load CSV housing dataset
EDA	Visualize distributions & correlations
Data Cleaning	Handle missing values & format columns
Feature Engineering	Encode categorical data & create useful features
Model Training	Train multiple ML models
Model Evaluation	Compare model performance
Prediction	Test model predictions on example inputs
Models Used

Linear Regression

Random Forest Regressor

XGBoost Regressor

The notebook compares their performance to identify the best model.

Visualizations

The project includes:

Histograms

Scatter plots

Boxplots by city

Correlation heatmap

Actual vs predicted price comparison

These visuals help understand market behavior and feature importance.


Technologies Used
Tool	Purpose
Python	Base language
pandas, NumPy	Data processing
Matplotlib, Seaborn	Visualization
scikit-learn	ML models & evaluation
XGBoost	Advanced ML model


🏁 Conclusion

This notebook provides a complete Polish real-estate price prediction pipeline and serves as a foundation for more advanced data-science real-estate applications.
