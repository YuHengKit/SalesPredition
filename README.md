# SalesPredition
Playing around with Kaggle competition https://www.kaggle.com/c/demand-forecasting-kernels-only/notebooks

```SalesPredictionV1.ipynb``` - using LSTM and linear regression model (OLS — Ordinary Least Squares) and calculate the Adjusted R-squared. The algorithm can't predict future data (no any sale record) because the predicted value is sum of the sales and output of model.
Reference: https://towardsdatascience.com/predicting-sales-611cb5a252de

```SalesPredictionV2.ipynb``` - using Light GBM algorithm and able to predict future sales. Reference: https://www.kaggle.com/ashishpatel26/light-gbm-demand-forecasting
