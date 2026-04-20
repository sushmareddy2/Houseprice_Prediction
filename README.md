# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using machine learning techniques based on property features such as size, number of rooms, and condition. It demonstrates an end-to-end ML workflow including data cleaning, feature engineering, model training, and evaluation.

---

## 📊 Dataset

* Source: Kaggle Housing Dataset
* Total Records: 4600
* Cleaned Records: 4502
* Features Used: 13

---

## 🧠 Problem Statement

Build a predictive model to estimate house prices using key attributes such as:

* Square footage
* Number of bedrooms and bathrooms
* Year built
* Property condition

---

## ⚙️ Steps Performed

### 🔹 Data Cleaning

* Removed invalid entries (price = 0)
* Removed outliers (price > $2M)
* Dropped irrelevant columns:

  * date, street, city, statezip, country

---

### 🔹 Feature Engineering

* Created new features:

  * `house_age`
  * `total_area`

---

### 🔹 Model Building

* Linear Regression (baseline model)
* Random Forest Regressor (final model)

---

## 📈 Model Performance

| Model             | MAE      |
| ----------------- | -------- |
| Linear Regression | ~210,000 |
| Random Forest     | ~134,000 |

👉 **Final Model Error:**
**Mean Absolute Error ≈ $134,000**

---

## 🔍 Key Insights

* `sqft_living` is the most influential feature (~60% importance)
* Property size impacts price more than number of bedrooms
* Model performs well for mid-range houses but struggles with high-value properties

---

## 📊 Visualization

* Actual vs Predicted Price Scatter Plot
* Feature Importance Analysis

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🚀 How to Run

```bash
git clone https://github.com/sushmareddy2/Houseprice_Prediction.git
cd Houseprice_Prediction
```

Open:

```
notebook/house_price.ipynb
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* Use advanced models (XGBoost)
* Include location-based features
* Deploy as a web application

---

## 👩‍💻 Author

Sushma Reddy

