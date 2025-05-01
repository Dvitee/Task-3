# 🏡 Task 3: House Price Prediction using Linear Regression

This project demonstrates how to implement and evaluate both simple and multiple linear regression models using a housing dataset.

---

## 📂 Dataset Used

- [Housing Price Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Contains features like area, number of bedrooms, bathrooms, parking, and amenities.

---

## ✅ What I Did

### 🔹 Simple Linear Regression
- Used `area` as the only feature to predict `price`.
- Visualized the regression line over actual test data.

### 🔹 Multiple Linear Regression
- Used all relevant features, including:
  - Numerical: `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
  - Binary Categorical: `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`
  - Multi-Class Categorical: `furnishingstatus` (converted via one-hot encoding)
- Evaluated the model using MAE, MSE, and R² Score.

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| **MAE** | ₹970,043 |
| **MSE** | ₹1,754,318,687,330 |
| **R² Score** | 0.65 |

---

## 📈 Key Insights

- More `bathrooms`, `airconditioning`, and `hotwaterheating` had the highest positive impact on price.
- `Unfurnished` homes significantly reduced the price.
- `Area` had a moderate effect — higher area generally leads to higher prices but isn't the only important factor.

---

## 📦 Technologies Used

- Python, Pandas, Matplotlib
- Scikit-learn (LinearRegression, model evaluation)

---
