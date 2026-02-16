  # *This is our Assignment No. 1.*


## Collaborators
Aryan Yadav 281 <br>
Ayush Kumar Prajapati 282 <br>
Neeraj Gupta 295 <br>
Rahul Yadav 317 <br>

# Ecommerce Sales Revenue Prediction 

# Linear Regression Models Analysis

## Objective
The objective of this assignment is to implement, analyze, and compare different Linear Regression models using a dataset containing multiple input features and a continuous target variable.

This study focuses on understanding regression techniques, model interpretation, and performance evaluation.

Models implemented:
1. Simple Linear Regression
2. Multiple Linear Regression
3. Polynomial Regression
4. Regularization Ridge and Lasso
---

## Dataset Description
[Link](https://github.com/AYUSHPRAJAPATI-99/ML-ASSIGNMENTS/blob/main/Assignment-01/ecommerce_sales_data.csv)
- Dataset used for regression analysis
- Contains multiple input features
- Continuous target variable
- Used for predicting numerical outcomes

The dataset was explored and cleaned before model development.

---

## Tools and Technologies Used
- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology
[Link](https://github.com/AYUSHPRAJAPATI-99/ML-ASSIGNMENTS/blob/main/Assignment-01/EDA_Simple_PolynomialRegression.ipynb)
### Part A – Exploratory Data Analysis (EDA)
The following steps were performed:
- Dataset loading and inspection
- Summary statistics generation
- Missing value checking
- Outlier detection
- Feature distribution visualization
- Correlation analysis using heatmap

EDA helps understand relationships and data quality before modeling.

---

## Part B – Simple Linear Regression
[Link](https://github.com/AYUSHPRAJAPATI-99/ML-ASSIGNMENTS/blob/main/Assignment-01/EDA_Simple_PolynomialRegression.ipynb)
A single independent feature is used to predict the target variable.

Steps performed:
- Feature selection
- Train-test split
- Model training
- Regression line plotting
- Interpretation of slope and intercept

### Evaluation Results
- MSE: **3,212,598.77**
- RMSE: **1,792.37**
- R² Score: **0.4335**

Observation:
The model explains around 43% of the variation in the target variable and serves as a baseline.

---

## Part C – Multiple Linear Regression
[Link](https://github.com/AYUSHPRAJAPATI-99/ML-ASSIGNMENTS/blob/main/Assignment-01/multiple_linear_regression.ipynb)
Multiple input features are used to improve prediction accuracy.

Steps performed:
- Selection of multiple features
- Train-test split
- Model training
- Evaluation using metrics
- Coefficient interpretation

### Evaluation Results
- MSE: **1,754,854.76**
- RMSE: **1,324.71**
- R² Score: **0.7203**
- Adjusted R²: **0.7188**
- Train R²: **0.7572**
- Test R²: **0.7203**

Observation:
Multiple features significantly improve prediction performance.

---

## Part D – Polynomial Regression
[Link](https://github.com/AYUSHPRAJAPATI-99/ML-ASSIGNMENTS/blob/main/Assignment-01/EDA_Simple_PolynomialRegression.ipynb)
Polynomial regression captures non-linear relationships.

Steps performed:
- Polynomial feature transformation
- Model training
- Prediction comparison
- Visualization of polynomial curve

### Evaluation Results

**Polynomial Regression**
- MSE: **3,372,895.41**
- RMSE: **1,836.54**
- R² Score: **0.4624**

Observation:
Polynomial regression provides only slight improvement in this dataset.

---

## Next Steps in Assignment
Following parts include:

### Part E – Regularization
[Link](https://github.com/AYUSHPRAJAPATI-99/ML-ASSIGNMENTS/blob/main/Assignment-01/ridge_lasso_regression.ipynb)
- Apply Ridge Regression
- Apply Lasso Regression
- Compare coefficients and feature impact


### Part F – Model Diagnostics
- Residual analysis
- Validation of regression assumptions
- Model reliability checking

## Observations
1. Simple regression provides baseline understanding.
2. Multiple regression significantly improves prediction accuracy.
3. Polynomial regression helps capture non-linear patterns but improvement depends on data.
4. Feature selection plays a major role in performance.

---

## Summary of Model Comparison

| Model Type | Complexity | Performance | Use Case |
|-------------|-----------|------------|-----------|
| Simple Linear Regression | Low | Moderate | Baseline analysis |
| Multiple Linear Regression | Medium | High | Practical prediction |
| Polynomial Regression | Medium | Slight improvement | Non-linear modeling |

Multiple Linear Regression performs best for this dataset.

---

## Conclusion
This assignment demonstrates implementation and comparison of regression models. Model performance improves as more relevant features and appropriate modeling techniques are applied.

Understanding regression behavior and evaluation metrics is essential for real-world machine learning applications.

---

## Result
The regression models were successfully implemented, evaluated, and compared. The experiment provides practical knowledge of regression modeling and performance evaluation.

---

---

## Assignment Reference
This project follows the procedure defined in Assignment-1: Comprehensive Study of Linear Regression Models. :contentReference[oaicite:0]{index=0}
