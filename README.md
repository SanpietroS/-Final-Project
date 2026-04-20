Car Price Prediction Project
Overview
This project builds and evaluates machine learning models to predict vehicle MSRP using a dataset of car specifications. Two models were developed and compared: a Random Forest Regressor and a Neural Network. The goal was to determine which model provides the most accurate and reliable predictions.

Final Results
Random Forest Performance
MAE: 4,123

RMSE: 11,991

R²: 0.974

Neural Network Performance
MAE: 4,956

RMSE: 16,717

R²: 0.949

Summary of Results
The Random Forest model achieved lower error values and a higher R² score, indicating stronger predictive accuracy and better overall fit compared to the Neural Network.

Key Insights
Model Behavior
The Random Forest’s predictions closely follow actual prices, with only larger deviations occurring for high‑priced luxury vehicles.

Residuals remain centered around zero, showing the model is not biased toward over‑ or under‑prediction.

The Neural Network consistently produced larger errors and struggled more with extreme price values.

Feature Importance
The most influential features were hp_per_year, Engine Cylinders, Engine HP, and indicators for luxury models.

The model relies heavily on performance‑related attributes and high‑end brand identifiers to determine price.

Sample Prediction Review
A small set of predictions was examined to compare actual values with model outputs.

This sample helped highlight where each model performs well and where errors increase, especially for expensive vehicles.

Recommendation
The Random Forest model is the recommended choice for MSRP prediction. It provides higher accuracy, more stable residuals, and better interpretability than the Neural Network.

Setup Instructions
1. Install Dependencies
    pip install -r requirements.txt
2. Open Final Project.ipynb in Jupyter Notebook
3. Execute all cells from top to bottom to reproduce the results.
