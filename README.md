# 🔋 Hourly Energy Consumption Forecasting

This project focuses on analyzing and forecasting hourly energy consumption using machine learning techniques. The dataset used provides over a decade of hourly energy consumption data, allowing for good predictive modeling and insights. The project includes various visualizations and analysis to identify patterns and trends, followed by forecasting.

## 🌟 Features

- **Time-Series Analysis**: Implementation of machine learning models to predict future energy consumption.
- **Data Visualization**: Charts and plots to visualize consumption patterns and forecast results.
- **Feature Engineering**: Creation of new features from the existing data to improve model performance.
- **Modeling**: XGBoost regressor used for accurate and efficient predictions.
- **Feature Importance Analysis**: Visualization of feature importance based on model training.

## 📁 Dataset

The dataset used for this project is publicly available on Kaggle:

- **[Hourly Energy Consumption Dataset](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)**

This dataset contains hourly consumption data across multiple years.

## ⚙️ Technologies Used

- **Python**: Programming language.
- **Pandas & NumPy**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For static and interactive data visualizations.
- **XGBoost**: Machine learning library for efficient and accurate predictions.
- **Scikit-learn**: For model training, evaluation, and calculating RMSE.

## 🤖 Machine Learning Techniques Used

This project employs the following machine learning techniques and steps:

- **Feature Engineering**: Creation of time-based features (e.g., hour, day, month) from the raw dataset to capture patterns in energy consumption.
- **XGBoost Regressor**: A powerful gradient boosting algorithm used for predicting future hourly energy consumption.
- **Train-Test Split**: The data was split into training and testing sets for model validation and error evaluation.
- **Feature Importance**: After model training, the importance of various features was analyzed and compared to determine their impact on the predictions.


## 📊 Visualizations Available

- **Energy Consumption Over Time**: Line plots displaying the historical energy usage.
- **Feature/Target Relationship**: Visualizations of the relationships between created features and the target variable (energy consumption).
- **Feature Importance Comparison**: Bar charts displaying the relative importance of each feature based on the trained XGBoost model.
- **Forecast Results**: Plots showing the predicted values compared with actual consumption.

