# Houseprice_Prediction
End-to-end ML project for predicting house prices using regression techniques and data analysis
## Project Overview
This project predicts house prices using machine learning based on features like size, number of rooms, and house condition.

## Dataset
- Source: Kaggle Housing Dataset
- Total Records: 4600
- Cleaned Records: 4502
- Features Used: 13

## Problem Statement
The goal is to build a model that predicts house prices based on input features such as:
- Square footage
- Bedrooms & bathrooms
- Year built
- House condition

## Steps Performed

### Data Cleaning
- Removed invalid data (price = 0)
- Removed outliers (price > $2M)
- Dropped irrelevant columns:
  - date, street, city, statezip, country
### Feature Engineering
- Created new features:
  - house_age
  - total_area
### Model Building
- Linear Regression (baseline model)
- Random Forest Regressor (final model)
## Model Performance

| Model | MAE |
|------|------|
| Linear Regression | ~210,000 |
| Random Forest | ~134,000 |

Final Model Error:
**Mean Absolute Error ≈ $134,000**

## Key Insights
- 'sqft_living' is the most important feature (~60% importance)
- House size impacts price more than number of bedrooms
- Model performs well for average-priced houses but struggles with high-value properties
  
## Visualization
- Actual vs Predicted Price Scatter Plot
- Feature Importance Graph

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## How to Run

```bash
git clone https://github.com/sushmareddy2/Houseprice_Prediction.git
cd Houseprice_Prediction
