# End-to-End ML Regression Price Prediction

## Project Goal
The primary objective of this project is to develop a machine learning model that accurately predicts car prices based on various influencing factors. By leveraging historical data, the model aims to provide insights into how different attributes, such as engine size, mileage, brand, and transmission type, contribute to the pricing of vehicles.

This predictive capability will assist stakeholders, including dealerships and potential buyers, in making informed decisions regarding car purchases and sales.

---

## Project Evaluation Metric: RMSE

The performance of the models will be assessed using **Root Mean Squared Error (RMSE)** as the primary evaluation metric. RMSE quantifies the average prediction error, providing a clear indication of how closely the model’s predictions align with actual prices.

$$
\text{RMSE} = \sqrt{\frac{1}{n} \sum_{i=1}^{n}(y_i - \hat{y}_i)^2}
$$

Where:

- **n** = total number of observations  
- **y_i** = actual values  
- **\(\hat{y}_i\)** = predicted values
