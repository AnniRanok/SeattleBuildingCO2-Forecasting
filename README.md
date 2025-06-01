# Seattle Building CO2 Forecasting

##  Project Overview

This project supports the City of Seattle’s mission to become carbon-neutral by 2050.  
Using structural building data (such as year built, building type, size, energy sources, and location),  
we aim to build a machine learning model that predicts:

- Total CO₂ emissions
- Total energy consumption

Our predictions reduce the need for costly annual energy audits by providing automated estimations for unmeasured buildings.

The project also evaluates the relevance of the **ENERGY STAR Score** as a predictor of emissions — currently a labor-intensive metric.

##  Data

-  [2016 Building Energy Benchmarking dataset](https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy)
- Data includes: Building ID, year built, energy source proportions, ENERGY STAR Score, total GHG emissions, etc.

##  Objectives

- Exploratory Data Analysis (EDA)
- Feature engineering (e.g., extracting insights from address, log transformation of skewed variables)
- Test multiple regression models
- Hyperparameter tuning and cross-validation
- Estimate performance (R², RMSE, MAE)
- Assess the usefulness of ENERGY STAR Score

##  Modeling Approaches

- Linear Regression
- Random Forest Regressor
- Gradient Boosting (XGBoost, LightGBM)
- Ridge / Lasso Regression
- Ensemble models

##  Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Cross-validated grid search

##  Project Structure
```
SeattleBuildingCO2-Forecasting/
├── data/ # Raw and cleaned data
├── notebooks/ # EDA and modeling notebooks
├── models/ # Saved models and hyperparameters
├── utils/ # Helper functions
├── reports/ # Visualizations and evaluation reports
└── README.md
```

##  Future Improvements

- Integrate recent datasets (post-2016)
- Deploy model as API for city use
- Automate ENERGY STAR Score estimation
- Geospatial feature extraction from building addresses



