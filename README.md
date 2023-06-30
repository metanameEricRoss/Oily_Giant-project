# Oily Giant - Project

## Intrduction
In this project, the goal was to analyze and suggest the most potentially profitable region among three options. The analysis involved using a linear regression model to make predictions and evaluate the RMSE metric. Additionally, the top 200 most profitable locations were identified based on the predicted values and compared with the actual values to gain insights into the peak profits of each region. Lastly, bootstrap sampling was applied to assess the risk of losses.

## Project Overveiw 

1. Linear Regression Model:
  - A linear regression model was developed to predict the potential profitability of the three regions.
  - The model was trained using available historical data on oil production and other relevant features.
  - The performance of the model was evaluated using the Root Mean Squared Error (RMSE) metric.
  - The lower the RMSE value, the better the model's predictive accuracy.

2. Profitability Analysis:
   - The predicted values from the linear regression model were used to identify the top 200 most profitable locations.
   - Actual values were compared with the predicted values to gain insights into the potential peak profits of each region.
   - This analysis helped in determining the region with the highest profit potential.
3. Risk Assessment:
  - Bootstrap sampling was applied to assess the risk of losses in each region.
  - By resampling the data and recalculating the profitability metrics, a distribution of potential outcomes was obtained.
  - This allowed for a better understanding of the risk associated with each region and provided insights for decision-making.
## Conclusion 

Through the analysis and evaluation of the linear regression model, comparison of actual and predicted values, and risk assessment using bootstrap sampling, valuable insights were gained to determine the most profitable region among the three options. This project served as a guide for decision-making and provided a systematic approach to assess the potential profitability and risks associated with each region.
