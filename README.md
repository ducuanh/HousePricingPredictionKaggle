🏡 House Price Prediction in Poland

This project demonstrates a full machine-learning workflow for predicting house prices in Poland using a structured dataset of property listings.
It is implemented in a Jupyter Notebook: HousePredictionPoland.ipynb.

📌 Project Overview

The goal of this project is to build predictive models that estimate real-estate prices based on property characteristics such as:

City

Area (m²)

Number of rooms

Floor level

Building age / construction year

Additional features (balcony, elevator, etc.)

The notebook walks through data processing, visualization, model training, and evaluation.

✅ Features & Workflow
Step	Description
Data Loading	Load CSV housing dataset
EDA	Visualize distributions & correlations
Data Cleaning	Handle missing values & format columns
Feature Engineering	Encode categorical data & create useful features
Model Training	Train multiple ML models
Model Evaluation	Compare model performance
Prediction	Test model predictions on example inputs
🧠 Models Used

Linear Regression

Random Forest Regressor

XGBoost Regressor

The notebook compares their performance to identify the best model.

📊 Visualizations

The project includes:

Histograms

Scatter plots

Boxplots by city

Correlation heatmap

Actual vs predicted price comparison

These visuals help understand market behavior and feature importance.

📂 File Structure
├── HousePredictionPoland.ipynb   # Main notebook
├── Houses.csv                    # Housing dataset (not included here)
└── README.md                     # Project documentation

🧰 Technologies Used
Tool	Purpose
Python	Base language
pandas, NumPy	Data processing
Matplotlib, Seaborn	Visualization
scikit-learn	ML models & evaluation
XGBoost	Advanced ML model
🚀 How to Run
# Clone repository
git clone <repo-link>

# Install dependencies
pip install -r requirements.txt

# Start Jupyter Notebook
jupyter notebook HousePredictionPoland.ipynb


⚠️ Ensure Houses.csv is placed in the same directory as the notebook.

🔮 Future Improvements

Add geospatial features (GPS coordinates, neighborhood data)

Deploy as a web app (Streamlit / Flask / FastAPI)

Hyperparameter tuning for improved accuracy

Include rental price prediction option

🏁 Conclusion

This notebook provides a complete Polish real-estate price prediction pipeline and serves as a foundation for more advanced data-science real-estate applications.
