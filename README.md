# Ridge Regression – Boston Housing Price Prediction

## Project Overview
This project predicts Boston house prices using Ridge Regression. The goal is to handle multicollinearity and improve model generalization through regularization.

## Dataset
- Boston Housing Dataset
- 506 samples, 13 features
- Target variable: Median house price (medv

## Dataset Columns Description
**Column**     **Description**
crim         - Per capita crime rate by town
zn	         - Proportion of residential land zoned for large lots
indus	       - Proportion of non-retail business acres
chas	       - Charles River dummy variable (1 = near river, 0 = otherwise)
nox	         - Nitric oxide concentration (pollution level)
rm	         - Average number of rooms per dwelling
age	         - Proportion of houses built before 1940
dis	         - Distance to employment centers
rad	         - Accessibility to highways
tax	         - Property tax rate
ptratio	     - Student–teacher ratio
black	       - Population demographic index
lstat	       - Percentage of lower-income population
medv         – Median house value (in $1000s)

## Approach
- Train-Test Split
- Ridge Regression
- Hyperparameter tuning using GridSearchCV
- Model evaluation using RMSE and R²
- Feature importance analysis

## Results
- RMSE ≈ 4.73
- R² ≈ 0.68
- Most important features: NOX, RM, CHAS

## Key Insights
- Environmental quality and house size strongly influence prices
- Ridge regression provides stable and interpretable coefficients

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Conclusion
Ridge Regression effectively reduced overfitting and provided reliable predictions for housing prices.
