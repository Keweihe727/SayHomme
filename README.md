# House Price Prediction Using XGBoost

## Project Overview
This project builds a **house price prediction model** using **XGBoost**, a powerful machine learning algorithm. The model utilizes various features of houses (like square footage, location, number of bedrooms, etc.) to accurately estimate their prices. The predictions are log-transformed to improve accuracy, and SHAP values are employed to interpret the feature importance for individual predictions.

## Objectives
- Predict house prices using advanced machine learning techniques.
- Improve prediction accuracy through **feature engineering** and **hyperparameter tuning**.
- Provide **explanations** for individual predictions using **SHAP values**.
- Build a reusable and scalable model that can be deployed for real-time predictions.

---

## Tech Stack
- **Python**: Data processing and model building.
- **XGBoost**: Machine learning model.
- **SHAP**: Model interpretability.
- **Pandas & NumPy**: Data manipulation.
- **Matplotlib**: Visualization of feature importance.
- **Joblib**: Model serialization.

---

## Dataset
The dataset contains various features relevant to house prices, including:
- **Structural Features**: Number of bedrooms, bathrooms, floors, etc.
- **Location Features**: Latitude, longitude, proximity to waterfront.
- **Property Size**: Square footage of living area and lot.
- **Quality and Condition**: Construction grade, view, condition, and renovation year.

### Example of Key Features:
```text
bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, view, condition, grade, ...
