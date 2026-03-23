# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts house prices using Machine Learning techniques based on various features such as bedrooms, bathrooms, square footage, and location.

## 📊 Dataset
- Contains housing data including:
  - bedrooms
  - bathrooms
  - sqft_living
  - city
  - year built, etc.

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Exploratory Data Analysis
- Top 10 cities with highest prices
- Bedrooms vs Price
- Bathrooms vs Price
- Age vs Price

## 🧠 Models Used
- Linear Regression
- Ridge Regression
- Decision Tree Regressor

## 📈 Results
- Initial model gave poor performance (R² ≈ -0.01)
- Improved using:
  - Feature Engineering (Age)
  - One-hot encoding
  - Proper scaling

## 📌 Key Insights
- `sqft_living` is the most important feature
- Location (city) significantly affects price
- Older houses tend to have lower prices

## 🚀 Future Improvements
- Use Random Forest / XGBoost
- Hyperparameter tuning
- Deployment using Flask/Streamlit
