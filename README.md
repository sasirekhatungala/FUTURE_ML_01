# 📈 Sales Forecasting Using Linear Regression

## 📌 Project Overview

Sales forecasting is an important business process that helps organizations estimate future sales based on historical data. Accurate sales predictions support inventory planning, budgeting, and strategic decision-making.

In this project, historical sales data is analyzed and a Linear Regression model is developed to forecast future sales trends. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and future sales prediction.

---

## 🎯 Project Objectives

- Analyze historical sales data.
- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Build a Linear Regression forecasting model.
- Evaluate model performance using regression metrics.
- Forecast future sales for the next 30 days.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

## 📂 Dataset Description

The dataset contains historical sales records with the following information:

- Date
- Sales Value

The date column is converted into datetime format to perform time-series analysis and forecasting.

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

### 1. Data Loading
- Imported dataset using Pandas.

### 2. Data Inspection
- Checked dataset structure.
- Reviewed data types.
- Generated summary statistics.

### 3. Missing Value Analysis
- Verified the presence of null values.
- Confirmed data completeness.

### 4. Duplicate Value Check
- Identified and removed duplicate records.

### 5. Date Conversion
- Converted date column into datetime format.

### 6. Sales Aggregation
- Aggregated sales values by date.

### 7. Feature Engineering
- Created a numerical time feature called **Day_Number** for model training.

---

# 📊 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand sales patterns, trends, and distributions.

---

## Daily Sales Trend

This visualization illustrates how sales change over time and helps identify trends and fluctuations.

![Daily Sales Trend](images/daily_sales_trend.png)

---

## Monthly Sales Trend

Monthly sales aggregation helps reveal long-term patterns and seasonal variations.

![Monthly Sales Trend](images/monthly_sales_trend.png)

---

## Sales Distribution

The distribution plot shows the spread and frequency of sales values.

![Sales Distribution](images/sales_distribution.png)

---

# 🤖 Machine Learning Model

## Algorithm Used

### Linear Regression

Linear Regression is a supervised machine learning algorithm used to model the relationship between an independent variable and a dependent variable.

In this project:

- Input Feature: Day_Number
- Target Variable: Sales

The model learns the sales trend over time and predicts future values.

### Model Training

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
```

---

# 📈 Model Evaluation

The model performance was evaluated using the following metrics:

### Mean Absolute Error (MAE)

Measures the average absolute prediction error.

### Mean Squared Error (MSE)

Measures the average squared prediction error.

### Root Mean Squared Error (RMSE)

Provides the error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variance in the data.

---

## Actual vs Predicted Sales

The graph below compares actual sales values with model predictions.

![Actual vs Predicted](images/actual_vs_predicted.png)

---

# 🔮 Future Sales Forecasting

After training, the model was used to forecast sales for the next 30 days.

The forecasting process includes:

- Creating future day values.
- Predicting future sales.
- Visualizing forecasted trends.

---

## Future Sales Forecast

The graph below displays historical sales data along with future predictions.

![Future Forecast](images/future_forecast.png)

---

# 📋 Results and Findings

- Historical sales data was successfully analyzed.
- Data preprocessing improved data quality.
- EDA provided insights into sales behavior.
- Linear Regression successfully captured the overall sales trend.
- Future sales predictions were generated for business planning purposes.
- The model demonstrated the practical use of machine learning for forecasting applications.

---

# 🚀 Future Enhancements

The project can be improved by implementing more advanced forecasting techniques such as:

- Random Forest Regressor
- XGBoost Regressor
- Prophet
- ARIMA
- LSTM Neural Networks

Additional features such as:

- Seasonal effects
- Holidays
- Promotions
- Marketing campaigns

can further improve prediction accuracy.

---


# 👩‍💻 Author

**Sasi Rekha Tungala**

Machine Learning Internship Project

---

# 📜 License

This project is developed for educational and internship learning purposes.
