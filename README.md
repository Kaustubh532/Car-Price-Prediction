# Car-Price-Prediction
# 🚗 Car Price Prediction using Machine Learning

Predict the selling price of used cars using a machine learning model trained on historical car listings. This project demonstrates the use of data preprocessing, feature engineering, and model evaluation to deliver reliable price predictions.

## 📌 Project Overview

This machine learning model takes in car features such as year, kilometers driven, fuel type, and more to estimate its current market value. Ideal for both car sellers and buyers to make informed pricing decisions.

## 📂 Dataset Features

| Feature         | Description                              |
|----------------|------------------------------------------|
| `Year`         | Year the car was purchased               |
| `Present_Price`| Original showroom price of the car       |
| `Kms_Driven`   | Total distance driven in kilometers      |
| `Fuel_Type`    | Type of fuel (Petrol/Diesel/CNG)         |
| `Seller_Type`  | Individual/Dealer/Trustmark Dealer       |
| `Transmission` | Manual or Automatic                      |
| `Owner`        | Number of previous owners                |

> Target Variable: `Selling_Price`

## ⚙️ Machine Learning Workflow

- **Data Cleaning:** Outlier removal and handling missing values
- **Feature Engineering:** Encoding categorical variables and deriving car age
- **Modeling:** Random Forest Regressor
- **Evaluation Metrics:**  
  - MAE (Mean Absolute Error): ₹96,537  
  - RMSE (Root Mean Squared Error): ₹139,127  

## 📈 Model Performance

The model shows good performance with minimal overfitting and strong generalization on test data. It can be enhanced further using hyperparameter tuning or models like XGBoost or LightGBM.

