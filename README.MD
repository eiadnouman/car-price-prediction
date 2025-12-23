# 🚗 Car Price Prediction

This project presents an end-to-end machine learning pipeline for predicting used car prices.
It covers data cleaning, exploratory data analysis (EDA), feature engineering, and model training.

---

## 📊 Dataset Overview
The dataset contains detailed information about used car sales, including:
- Car specifications (make, model, trim, body type)
- Usage metrics (odometer, condition)
- Sale details (price, date, location)

---

## 🧹 Data Preprocessing
- Handling missing values
- Removing duplicates
- Normalizing categorical features
- Outlier handling using IQR clipping
- Feature engineering from sale dates

---

## 📈 Exploratory Data Analysis (EDA)
- Price and mileage distributions
- Sales trends over years and months
- Most common brands, models, and body types
- Relationship between condition, mileage, and price

---

## 🤖 Modeling
The following models were trained and evaluated:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor (best performing)

Techniques used:
- Pipelines
- Target Encoding for categorical features
- Cross-validation
- Hyperparameter tuning (GridSearchCV)

---

## 📌 Evaluation Metrics
- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

The final XGBoost model achieved strong generalization performance on the test set.

---

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Seaborn, Matplotlib  

---

## 📁 Files
- `Car_Price_Prediction.ipynb` → Full analysis and modeling notebook

---

## 📦 Dataset Access
The dataset used in this project is relatively large, so it is hosted externally.

🔗 **Google Drive Link
https://drive.google.com/uc?export=download&id=1q33u6GkHghQUHVxkyaVALw3_pDCDDv45

After downloading, place the dataset in the same directory as the notebook before running it.

---

## ✍️ Author
Eهad Nouman
