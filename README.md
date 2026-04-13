# 🚗 Car Price Prediction (cars.xls)

## 📌 Overview
This project focuses on predicting car prices using various machine learning regression models. The dataset contains information about different car features such as mileage, engine specifications, and additional attributes.

The goal is to build a high-performing regression model and analyze the impact of different features on car prices.

---

## 📊 Dataset Information

The dataset includes **804 records** with the following features:

- **Price** (Target variable)
- **Mileage**
- **Make, Model, Trim, Type**
- **Cylinder, Liter**
- **Doors**
- **Cruise, Sound, Leather**

---

## ⚙️ Project Workflow

1. **Data Loading**
   - Loaded data from `.xls` file

2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
   - Heatmaps
   - Scatter plots
   - Outlier detection

3. **Feature Engineering**
   - Encoding categorical variables
   - Handling multicollinearity
   - Using domain knowledge

4. **Data Preprocessing**
   - Normalization / Scaling
   - Train-test split (80/20)

5. **Model Training**
   - Tested **21 regression models**
   - Compared performance using:
     - **R² Score**
     - **RMSE**

---

## 📈 Model Performance

| Model        | R² Score | RMSE |
|-------------|---------|------|
| CatBoost     | 0.995   | Best |
| Linear Models| ~0.99   | Strong |
| Random Forest| ~0.98   | Good |
| SVR          | Poor    | High Error |

👉 **Best Model: CatBoost Regressor**

---

## 🧠 Key Concepts

- Regression Modeling
- Feature Engineering
- Multicollinearity
- Normalization
- Residual Analysis
- Model Evaluation

---

## 📏 Evaluation Metrics

- **R² Score** → Measures how well the model explains variance  
- **RMSE** → Measures prediction error  
- **Residuals** → Difference between actual and predicted values  

---

## 🔥 Key Insights

- Mileage has a strong impact on price  
- High correlation (>0.90) indicates redundant features  
- Feature engineering significantly improves model performance  
- Ensemble models outperform basic models  

---

## 🚀 Results

- Achieved **R² > 99%**
- Model successfully predicts car prices with high accuracy
- Outperformed baseline significantly

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Seaborn
- Matplotlib
