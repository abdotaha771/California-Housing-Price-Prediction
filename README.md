# California-Housing-Price-Prediction
Description:

This project investigates machine learning techniques for predicting California housing prices using the California Housing Dataset from scikit-learn. We explore Linear Regression and XGBoost models, perform feature scaling and selection, and evaluate their performance using cross-validation.

Key Features:

Data exploration and visualization
Feature scaling with StandardScaler
Feature selection with Recursive Feature Elimination (RFE)
Model training and evaluation using Linear Regression and XGBoost
Cross-validation for robust performance assessment
Model performance comparison using R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE)
Installation:

Clone this repository: git clone https://github.com/<your-username>/california-housing-price-prediction.git
Install required libraries: pip install numpy pandas matplotlib seaborn scikit-learn xgboost
Usage:

Navigate to the project directory: cd california-housing-price-prediction
Run the script: python california_housing_prediction.py
Results:

The script will output model performance metrics, including R², MSE, and MAE for both Linear Regression and XGBoost models. Visualization of these metrics will also be generated. Additionally, the script produces scatter plots comparing actual vs. predicted prices and a residual plot to assess model assumptions.

Future Work:

This project provides a solid foundation for housing price prediction. Here are some areas for future exploration:

Hyperparameter tuning for improved model performance
Feature engineering and creation of new features
Integration with a web application for real-time predictions
Ensembling techniques to combine multiple models
