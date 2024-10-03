# 🔋 Hourly Energy Consumption Forecasting

This project focuses on analyzing and forecasting hourly energy consumption using time-series analysis techniques. The dataset used provides over a decade of hourly energy consumption data, allowing for robust predictive modeling and insights. The project includes various visualizations and analysis to identify patterns and trends.

## 🌟 Features

- **Time-Series Analysis**: Implementation of time-series forecasting models to predict future energy consumption.
- **Data Visualization**: Charts and plots to visualize consumption patterns and forecast results.
- **Modeling**: Comparison of models like ARIMA, SARIMA, and others to find the best-performing forecasting model.
- **Train-Test Split**: Data split into training and test sets for model validation.

## 📁 Dataset

The dataset used for this project is publicly available on Kaggle:

- **[Hourly Energy Consumption Dataset](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)**

This dataset contains hourly consumption data across multiple years, providing a comprehensive view of energy usage.

## ⚙️ Technologies Used

- **Python**: Core programming language.
- **Pandas & NumPy**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For static visualizations of the data.
- **Plotly**: For interactive data visualizations.
- **Statsmodels**: For implementing time-series models.
- **Streamlit**: For building an interactive UI.
- **Heroku**: For deploying the application.

## 🤖 Machine Learning Techniques Used

The project utilizes several machine learning and time-series forecasting techniques to predict energy consumption, including:

- **ARIMA (AutoRegressive Integrated Moving Average)**: A popular statistical model used for forecasting time series data.
- **SARIMA (Seasonal ARIMA)**: An extension of ARIMA that supports seasonality in data.
- **Exponential Smoothing (ETS)**: A method for smoothing time series data to make short-term forecasts.
- **Prophet**: A forecasting tool developed by Facebook for predicting time-series data with daily seasonality, holidays, and trend changes.

## 📊 RMSE Scores

The models were evaluated using **Root Mean Squared Error (RMSE)** to compare their performance. Here are the RMSE scores for the different models:

- **ARIMA RMSE**: _Add ARIMA RMSE score here_
- **SARIMA RMSE**: _Add SARIMA RMSE score here_
- **ETS RMSE**: _Add ETS RMSE score here_
- **Prophet RMSE**: _Add Prophet RMSE score here_

## 📊 Visualizations Available

- **Energy Consumption Over Time**: Line plots displaying the historical energy usage.
- **Train/Test Split Visualization**: Visual representation of the data split for model training and testing.
- **Forecast Results**: Plots showing the model's predicted values compared with actual consumption.

## 📄 License

This project is licensed under the MIT License.
