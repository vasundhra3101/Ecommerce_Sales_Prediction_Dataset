# 🛒 E-Commerce Sales Forecasting using Linear Regression

## 📌 Project Overview

This project focuses on predicting e-commerce sales using Machine Learning. A Linear Regression model is built to analyze historical sales data and forecast sales amounts based on order information such as quantity sold and purchase date.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, prediction, and evaluation.

---

## 🎯 Objectives

- Analyze historical e-commerce sales data.
- Clean and preprocess the dataset.
- Perform exploratory data analysis (EDA).
- Build a Linear Regression model to forecast sales.
- Evaluate model performance using regression metrics.
- Visualize actual vs. predicted sales.

---

## 📂 Dataset

**Dataset Name:** Amazon Sale Report Dataset

The dataset contains information such as:

- Order ID
- Date
- Product Category
- Quantity (Qty)
- Sales Amount
- Order Status
- Fulfilment
- Sales Channel
- Customer Location
- B2B Orders
- Courier Status

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📊 Machine Learning Workflow

1. Import Dataset
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Linear Regression Model
8. Model Prediction
9. Model Evaluation
10. Data Visualization

---

## 📈 Features Used

The model uses the following features:

- Quantity (Qty)
- Month
- Day

**Target Variable**

- Amount (Sales)

---

## 📉 Model

Algorithm Used:

- Linear Regression

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📷 Visualizations

The project includes:

- Monthly Sales Trend
- Top Product Categories
- Order Status Distribution
- Quantity Distribution
- Actual vs Predicted Sales Scatter Plot

---

## 📁 Project Structure

```
E-Commerce-Sales-Forecasting/
│
├── dataset/
│   ├── Amazon Sale Report.csv
│
├── notebooks/
│   └── sales_forecasting.ipynb
│
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.

```
git clone https://github.com/yourusername/E-Commerce-Sales-Forecasting.git
```

2. Open the project in Google Colab or Jupyter Notebook.

3. Install dependencies.

```
pip install pandas numpy matplotlib scikit-learn
```

4. Upload the dataset.

5. Run all notebook cells sequentially.

---

## 📌 Results

The Linear Regression model was trained on the Amazon Sales dataset and evaluated using standard regression metrics. The project demonstrates how machine learning can be applied to analyze historical sales data and generate sales predictions.

---

## 🚀 Future Improvements

- Use Random Forest Regressor for better accuracy.
- Implement XGBoost for improved forecasting.
- Add sales forecasting dashboard using Streamlit.
- Deploy the model as a web application.
- Include real-time sales prediction.
