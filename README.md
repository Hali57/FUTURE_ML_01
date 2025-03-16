# FUTURE_ML_01
- This repository will contain completed Machine Learning tasks  .
- I used a Prophet() ML forecasting model that predicts future sales trends, and provides 
   visualizations of forecast accuracy and seasonality.

## Key Results
### RMSE (Root Mean Squared Error): 0.792724260584282

- What it is: RMSE measures the average magnitude of the errors in your predictions. It's the square root of the average of the squared differences between the predicted and actual values.
  - Interpretation: An RMSE of 0.7927 means that, on average, the model's predictions are about 0.79 units away from the actual values. Lower RMSE values indicate better model performance.
    
### MAE (Mean Absolute Error): 0.5685192942092205

- What it is: MAE measures the average magnitude of the errors in your predictions, but it uses the absolute differences between the predicted and actual values instead of squared differences.
  - Interpretation: An MAE of 0.5685 means that, on average, the model's predictions are about 0.57 units away from the actual values. Like RMSE, lower MAE values are better.
  
### MAPE (Mean Absolute Percentage Error): 5.721456834679205

- What it is: MAPE measures the average percentage error of the predictions. It's the average of the absolute percentage differences between the predicted and actual values.
  - Interpretation: A MAPE of 5.72% means that, on average, the model's predictions are about 5.72% away from the actual values. MAPE is useful for understanding the relative size of the errors.

## Putting it Together

- The graphs(Forecast, Trend, yearly , Weekly seasonality curves) show that the data has a clear upward trend, weekly seasonality, and yearly seasonality.
- The error metrics (RMSE, MAE, MAPE) give you an idea of how well the model is fitting the data. The MAPE provides a percentage-based measure of accuracy.
