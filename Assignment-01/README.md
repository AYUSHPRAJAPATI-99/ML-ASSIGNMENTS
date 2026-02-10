  # *This is our Assignment No. 1.*


# Ecommerce Sales Prediction using Simple Linear Regression

## Objective
The objective of this assignment is to perform an end-to-end analysis of an ecommerce sales dataset and apply Simple Linear Regression to study the relationship between product quantity and sales.

This project is intended as a baseline regression analysis with emphasis on model understanding, interpretation, and evaluation.

---

## Dataset Description
- Dataset: ecommerce_sales_data.csv  
- Domain: Ecommerce / Retail Analytics  
- Type: Transaction-level data  

### Key Columns
- Quantity – Number of units sold per order (Independent Variable)  
- Sales – Total revenue generated from the order (Target Variable)  

Other columns such as Product, Category, Region, and Order Date were explored during exploratory data analysis but were not included in the simple linear regression model.

---

## Tools and Technologies
- Python  
- Jupyter Notebook / Google Colab  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
The following steps were performed to understand and prepare the data:
- Dataset loading and inspection
- Summary statistics generation
- Missing value and duplicate row checks
- Outlier detection using boxplots
- Data visualization and correlation analysis

### 2. Feature Selection
To satisfy the definition of Simple Linear Regression, only one independent variable was selected:
- Quantity → Sales

### 3. Model Building
- The dataset was split into training (80%) and testing (20%) sets
- A Simple Linear Regression model was trained using `LinearRegression` from scikit-learn

---

## Model Evaluation
The model performance was evaluated using standard regression metrics:

- Mean Squared Error (MSE): 3,373,973.04  
- Root Mean Squared Error (RMSE): 1836.84  
- R² Score: 0.46  

## Interpretation
- An R² score of 0.46 indicates that approximately 46% of the variance in sales is explained by quantity.
- The RMSE value represents the average prediction error in sales.
- These results suggest a moderate linear relationship between quantity and sales.

Since only one feature was used, the model serves as a baseline for understanding sales behavior.

---

## Performance Analysis and Scope for Improvement
The moderate performance of the model is expected due to the use of a single independent variable. Sales are influenced by multiple factors, including:
- Product type
- Category
- Region
- Pricing and discounts
- Seasonal effects

Model performance can be improved by applying Multiple Linear Regression, where additional relevant features are incorporated to explain a greater portion of sales variability.

This highlights the importance of feature selection and model choice in real-world regression problems.

---

## Conclusion
This project demonstrates the application of Simple Linear Regression to ecommerce sales data. While quantity alone provides useful insights, improved predictive accuracy can be achieved by extending the analysis to multiple regression models. The current model establishes a baseline for further exploration and comparison.

---
