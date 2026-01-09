# Ridge Regression – Boston Housing Price Prediction

## Project Overview
This project predicts Boston house prices using Ridge Regression. The goal is to handle multicollinearity and improve model generalization through regularization.

## Dataset
- Boston Housing Dataset
- 506 samples, 13 features
- Target variable: Median house price (medv)

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
