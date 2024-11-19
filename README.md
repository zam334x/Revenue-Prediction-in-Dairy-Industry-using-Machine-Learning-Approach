# Revenue Prediction in the Dairy Industry Using Machine Learning

This repository contains my MSc dissertation project from **Queen's University Belfast**, titled **"Revenue Prediction inDairy  Industry Using Machine Learning Approach."** The project explores machine learning techniques to predict revenue in the dairy industry with high accuracy and reliability.

---

## 📘 **About the Project**

The dairy industry faces challenges like fluctuating prices, seasonal variations, and complex market dynamics. This project applies advanced machine learning models to address these challenges and enhance revenue prediction accuracy. 

**Dataset:** A Kaggle dataset with 4,326 rows and 23 columns, containing features such as farm size, product type, pricing, sales data, and customer demographics.

---

## 🛠️ **Models Used**

Eight machine learning models were implemented and evaluated:
- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor (GBR)
- XGBoost Regressor
- K-Nearest Neighbors (KNN)
- Support Vector Regressor (SVR)

**Evaluation Metrics:**  
- R² Score  
- RMSE (Root Mean Square Error)
- MSE (Mean Square Error)  
- MAE (Mean Absolute Error)  
- MAPE (Mean Absolute Percentage Error)  
- Explained Variance  

---

## 🔑 **Key Findings**

- **Best Model:** Gradient Boosting Regressor (GBR)
  - **R² Score:** 0.9981
  - **RMSE:** 557.84
  - **MAPE:** 3.36%
- **Insights:** 
  - SHAP analysis identified "Quantity Sold" and "Price per Unit" as key revenue drivers.
  - Ensemble models like GBR and Random Forest showed strong generalization with minimal overfitting.
- **Limitations:** 
  - Dataset constraints (geographic and temporal scope).
  - Computational complexity of ensemble models.

---

## 📊 **Data Analysis and Visualizations**

1. **Exploratory Data Analysis (EDA):**
   - Histograms, density plots, and scatter plots to understand data distribution and relationships.
   - Correlation matrix to identify feature interactions.
2. **Learning Curves and Residual Plots:** 
   - Evaluated model performance and generalization.
3. **SHAP Analysis:** 
   - Feature importance analysis to interpret model predictions.

---


