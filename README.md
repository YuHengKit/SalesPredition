# SalesPredition
Playing around with Kaggle competition https://www.kaggle.com/c/demand-forecasting-kernels-only/notebooks Repeating other's works to understand the algorithm and analysis.

```SalesPredictionV1.ipynb``` - using LSTM and linear regression model (OLS — Ordinary Least Squares) and calculate the Adjusted R-squared. The algorithm can't predict future data (no any sale record) because the predicted value is sum of the sales and output of model.
Reference: https://towardsdatascience.com/predicting-sales-611cb5a252de

```SalesPredictionV2.ipynb``` - using Light GBM algorithm & XGBoost and able to predict future sales. Reference: https://www.kaggle.com/ashishpatel26/light-gbm-demand-forecasting
https://www.kaggle.com/sarath1341993/simple-xgboost
