# E-Commerce Sales Forecasting with Linear Regression

## Project Overview

This project focuses on analyzing Amazon e-commerce sales data and predicting sales amounts using a Linear Regression machine learning model.

The project includes data loading, data cleaning, exploratory data analysis, data visualization, feature selection, model training, prediction, and model evaluation.

## Objectives

* Load and explore the Amazon sales dataset.
* Identify and handle missing values.
* Remove duplicate and unnecessary data.
* Convert and extract useful date features.
* Analyze sales trends and product categories.
* Visualize order status and quantity distribution.
* Build a Linear Regression model.
* Predict sales amounts.
* Evaluate model performance using regression metrics.

## Dataset

The dataset used in this project is the **Amazon Sale Report.csv** dataset.

The dataset contains information such as:

* Order ID
* Date
* Order Status
* Fulfilment
* Sales Channel
* Product Category
* Product Size
* Quantity
* Sales Amount
* Shipping City
* Shipping State
* Shipping Country

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## Project Workflow

### 1. Data Loading

The dataset is loaded using the Pandas library.

```python
df = pd.read_csv("Amazon Sale Report.csv")
```

### 2. Data Exploration

The dataset is explored using:

* `df.head()`
* `df.info()`
* `df.describe()`
* `df.isnull().sum()`

### 3. Data Cleaning

The following preprocessing steps are performed:

* Removed duplicate rows.
* Removed the unnecessary `Unnamed: 22` column.
* Removed rows with missing sales amounts.
* Converted the `Date` column into datetime format.

### 4. Feature Engineering

The following features are extracted from the date:

* Year
* Month
* Day

These features are used for further analysis and machine learning.

### 5. Exploratory Data Analysis

The following visualizations are created:

* Monthly Sales Trend
* Top 10 Product Categories by Sales
* Order Status Distribution
* Quantity Distribution

### 6. Machine Learning Model

A Linear Regression model is used for sales prediction.

#### Features Used

* Quantity (`Qty`)
* Month (`Month`)
* Day (`Day`)

#### Target Variable

* Sales Amount (`Amount`)

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

### 7. Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

The model generates predictions for sales amounts based on the selected features.

Example evaluation metrics:

* **MAE:** 207.41
* **MSE:** 70778.41
* **RMSE:** 266.04
* **R² Score:** 0.0036

The low R² score indicates that the selected features alone do not explain most of the variation in sales amount. This suggests that additional features such as product category, price, fulfilment method, customer location, and order status could improve the prediction performance.

## Visualizations

The project generates the following visualizations:

1. Monthly Sales Trend
2. Top 10 Product Categories by Sales
3. Order Status Distribution
4. Quantity Distribution
5. Actual vs Predicted Sales

## Conclusion

This project demonstrates the complete machine learning workflow for e-commerce sales analysis and prediction.

The Linear Regression model provides a basic prediction approach. However, the model performance can be improved by using additional relevant features and advanced machine learning algorithms such as:

* Decision Tree Regression
* Random Forest Regression
* Gradient Boosting
* XGBoost

This project provides a foundation for developing a more accurate e-commerce sales forecasting system.

## Future Improvements

* Add more important features to the model.
* Perform advanced feature engineering.
* Handle categorical variables using encoding techniques.
* Compare multiple machine learning algorithms.
* Perform hyperparameter tuning.
* Improve sales forecasting accuracy.
* Deploy the model as a web application.

