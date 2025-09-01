# Machine Learning Projects – Housing Price Prediction  

*A set of regression models applied on Boston and California housing datasets to predict house prices.*  

---

## 📌 Projects  

### 1. Boston Housing Price Prediction  
A regression project using the **Boston Housing dataset**, predicting median house values based on features such as crime rate, number of rooms, and property tax.  

- **Dataset**: [Boston Housing Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/housing)  
- **Models Tested**:  
  - Linear Regression  
  - Support Vector Regression (SVR)  
  - K-Nearest Neighbors (KNN)  
- **Evaluation Metrics**: MAE, MSE, RMSE, R² score  
- **Results**:  
  - Linear Regression achieved reasonable baseline performance.  
  - SVR and KNN provided competitive results after hyperparameter tuning.  

---

### 2. California Housing Price Prediction  
A regression project using the **California Housing dataset**, predicting median house values based on demographic and geographic features.  

- **Dataset**: [California Housing Dataset (Scikit-learn)](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)  
- **Models Tested**:  
  - Linear Regression  
  - Support Vector Regression (SVR)  
  - K-Nearest Neighbors (KNN)  
- **Evaluation Metrics**: MAE, MSE, RMSE, R² score  
- **Results**:  
  - KNN performed well on capturing local variations in housing prices.  
  - SVR offered strong performance after GridSearchCV tuning.  

---

## 📈 Results Summary  

| Dataset     | Model               | Notes                           |
|-------------|---------------------|---------------------------------|
| Boston      | Linear Regression   | Baseline, interpretable results |
| Boston      | SVR                 | Improved after tuning           |
| Boston      | KNN                 | Competitive with SVR            |
| California  | Linear Regression   | Baseline, limited fit           |
| California  | SVR                 | Strong with parameter tuning    |
| California  | KNN                 | Good at local price variations  |

---
