# E-Commerce Sales Forecasting with Linear Regression

## Project Overview

This project focuses on analyzing Amazon e-commerce sales data and predicting sales amounts using a Linear Regression machine learning model.

---

## Dataset

The dataset used in this project is the Amazon Sale Report.csv dataset.


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Project Workflow

### 1. Data Loading and Exploration

The dataset is loaded and explored using Pandas.


### 2. Data Cleaning

The following preprocessing steps are performed:

- Removed duplicate rows.
- Removed unnecessary columns.
- Handled missing values.
- Converted the Date column into datetime format.

---

### 3. Exploratory Data Analysis

#### Monthly Sales Trend

This graph shows the total sales amount for each month.

<img width="499" height="336" alt="image" src="https://github.com/user-attachments/assets/17db7ab6-e879-467d-9c65-85bd881d4e62" />

#### Top 10 Product Categories by Sales

This graph shows the top product categories based on sales amount.

<img width="499" height="325" alt="image" src="https://github.com/user-attachments/assets/8dc3eb76-9866-4ad7-a8b2-bf09b324c5fb" />

#### Order Status Distribution

This pie chart shows the distribution of different order statuses.

<img width="503" height="414" alt="image" src="https://github.com/user-attachments/assets/16962ffa-9bfa-4151-adda-31346995d326" />

#### Quantity Distribution

This histogram shows the distribution of quantities ordered.

<img width="498" height="335" alt="image" src="https://github.com/user-attachments/assets/b1bc24ca-18bf-4834-9c80-0227857eb2f6" />

---

## Machine Learning Model

A Linear Regression model is used to predict sales amounts.

### Features Used

- Quantity (`Qty`)
- Month (`Month`)
- Day (`Day`)

### Target Variable

- Sales Amount (`Amount`)

---

## Model Training

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

The Linear Regression model is trained using the training dataset.


---

## Model Evaluation

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Example results:

- MAE: 207.41
- MSE: 70778.41
- RMSE: 266.04
- R² Score: 0.0036

---

## Actual vs Predicted Sales

This scatter plot compares the actual sales amounts with the predicted sales amounts.

<img width="493" height="386" alt="image" src="https://github.com/user-attachments/assets/5191c9cb-d666-4033-81c7-f65b7e9fc83d" />


---

## Conclusion

This project demonstrates the complete machine learning workflow for e-commerce sales analysis and prediction.

The Linear Regression model provides a basic prediction approach. However, additional features and advanced machine learning algorithms can be used to improve prediction accuracy.

---

## Future Improvements

- Add more important features.
- Perform advanced feature engineering.
- Encode categorical variables.
- Compare multiple machine learning algorithms.
- Perform hyperparameter tuning.
- Improve sales forecasting accuracy.

---


