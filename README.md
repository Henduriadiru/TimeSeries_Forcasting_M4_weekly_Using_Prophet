# TimeSeries_Forcasting_M4_weekly_Using_Prophet
📈 Time Series Forecasting on M4 Weekly Dataset using Facebook Prophet  This project showcases time series forecasting using Facebook Prophet on weekly data from the M4 competition. The goal is to predict future values for selected variables (V2, V3, and V4), with clear visualizations and confidence intervals to support interpretation.

📊 Forecasting Weekly Time Series Data (M4 Dataset) using Facebook Prophet

This project applies Facebook Prophet to perform univariate time series forecasting on selected variables (V2, V3, V4) from the M4 Weekly dataset. The dataset is split into training and test sets. Prophet is used to:

- Fit time series models on the test dataset columns

- Forecast the next 12 weekly periods for each series

- Visualize predictions along with upper and lower uncertainty intervals (yhat, yhat_lower, yhat_upper)

- Compare forecasts across multiple variables in a unified plot

- Annotate each forecasted value to enhance interpretability

- The main goal is to demonstrate how Prophet can be used effectively for short-term forecasting and produce interpretable visual outputs that capture trends and seasonality.

This project is suitable for:

- Practicing multivariate forecast visualization

- Learning Prophet's workflow on multiple time series

- Demonstrating uncertainty bounds in forecasts

  ---
  🧪 Dataset Description
Weekly-train.csv: Contains the training set used to train the Prophet models.

Weekly-test.csv: Used as the basis for forecasting (V2, V3, V4).

Each row is a weekly data point; columns represent different time series.

  ---

---
⚙️ How It Works
Drop missing columns from training and testing data.

Use Prophet for univariate time series forecasting.

Create a custom function prophet_for_some_column to train and forecast each variable.

Visualize predictions with confidence intervals using seaborn.

---

---
📊 Forecasting Results
🔁 Combined Forecast (V2, V3, V4)

🔍 Individual Forecasts
Variable V2

Variable V3

Variable V4

---

---
📌 Interpretation
yhat: Estimated forecast value

yhat_lower: Lower bound (uncertainty interval)

yhat_upper: Upper bound (uncertainty interval)

These bounds help assess the confidence in the forecasts.

---

---
📁 How to Run the Notebook
Clone the repository

Place the dataset CSV files inside a data/ directory

Open time_series_forecasting_M4_weekly.ipynb in Jupyter

Run all cells to train and generate forecasts with Prophet

---

---
🧠 Future Work
Include RMSE or MAPE evaluation on predictions

Extend model with external regressors

Use multivariate or deep learning models (e.g., LSTM)

---

---
🤝 Contributing
Feel free to fork, improve, and submit pull requests.

---

---
📜 License
This project is licensed under the MIT License.
---
