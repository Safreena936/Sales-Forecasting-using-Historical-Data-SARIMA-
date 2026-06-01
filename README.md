Sales Forecasting Using Historical Data (SARIMA)

📌 Project Overview

This project predicts future sales using historical sales data and the SARIMA (Seasonal AutoRegressive Integrated Moving Average) time series forecasting model. The system analyzes past sales trends and seasonal patterns to forecast future monthly sales.


🎯 Objectives

* Analyze historical sales data.
* Identify trends and seasonal patterns.
* Build a SARIMA forecasting model.
* Predict future sales values.
* Evaluate model performance using MAE and RMSE.


 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* Scikit-learn


 📂 Dataset

The dataset contains historical sales records with:

* Date
* Sales

Example:

| Date       | Sales |
| ---------- | ----- |
| 2019-01-01 | 250   |
| 2019-02-01 | 300   |
| 2019-03-01 | 275   |


🔍 Exploratory Data Analysis (EDA)

* Dataset inspection
* Missing value analysis
* Duplicate record check
* Monthly sales aggregation
* Sales trend visualization
* Stationarity testing using ADF Test

⚙️ Methodology

1. Data Preprocessing

* Convert Date column to datetime format
* Sort data by date
* Set Date as index

2. Monthly Aggregation

* Resample sales data monthly

3. Visualization

* Monthly Sales Trend Plot

4. Stationarity Check

* Augmented Dickey-Fuller (ADF) Test

5. Model Building

* SARIMA Model
* Order = (1,1,1)
* Seasonal Order = (1,1,1,12)

6. Forecasting

* Forecast next 6 months
* Forecast future 12 months

 7. Evaluation

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)


 📊 Results

The SARIMA model successfully forecasts future sales by capturing historical trends and seasonal patterns.

Sample Output

* MAE: Calculated based on test data
* RMSE: Calculated based on test data
* Future Sales Forecast: Next 12 months predicted sales


 🚀 Deployment Method

The model is implemented and executed using Jupyter Notebook, where users can upload historical sales data and generate future sales forecasts.


 📈 Future Enhancements

* Deploy as a web application using Streamlit.
* Add real-time sales data integration.
* Compare SARIMA with machine learning models.
* Improve forecasting accuracy using parameter tuning.
