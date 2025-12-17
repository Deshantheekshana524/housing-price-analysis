# 🏠 California Housing Price Prediction

## 📌 Project Overview
This project focuses on predicting median house values in California using the California Housing dataset.
The workflow is structured into three notebooks to ensure clarity, reproducibility, and meaningful model evaluation.

## 📘 Notebook Description
### 1️⃣ Exploratory Data Analysis (EDA)
### 2️⃣ Modeling with Original Features
### 3️⃣ Feature Engineering & Enhanced Modeling


## 📊 Model Performance Comparison

### 🔹 Baseline Models (Original Features)
| Model	                 | RMSE       | R² |
|-----------------------|-------------|----|
| Linear Regression	    | 70,317 	  | 0.636 |
| Random Forest	        | 60,477	   | 0.731 |
| XGBoost	              | 59,593	   | 0.738 |
| LightGBM              | 59,523       | 0.739 |

### 🔹 Models with Engineered Features
| Model	                 | RMSE       | R² |
|-----------------------|-------------|----|
| Linear Regression	    | 67,640	  | 0.663 |
| Random Forest	        | 58,284	   | 0.750 |
| XGBoost	              | 57,634	   | 0.755 |
| LightGBM              | 57,555       | 0.756 |

