# 🛒 Blinkit Sales Trend Analysis & Revenue Forecasting

## 📌 Project Overview

This project presents an **end-to-end data analytics and machine learning pipeline** for analyzing Blinkit sales data and forecasting future revenue. The analysis integrates multiple datasets including **orders, products, customers, inventory, and customer feedback** to generate actionable business insights.

Through **exploratory data analysis, feature engineering, customer segmentation, and predictive modeling**, the project identifies key drivers of sales performance such as pricing effects, stock efficiency, and customer sentiment.

The final machine learning model predicts **future sales revenue**, helping businesses make **data-driven operational and pricing decisions**.

---

## 🎯 Project Objectives

* Analyze **sales trends and seasonal patterns**
* Understand **customer purchasing behavior**
* Perform **customer segmentation using RFM analysis**
* Evaluate **inventory efficiency and pricing impact**
* Build a **machine learning model to forecast revenue**

---

## 📂 Dataset

The project uses multiple datasets related to Blinkit operations:

* `blinkit_orders.csv` – Order transaction details
* `blinkit_order_items.csv` – Item-level order information
* `blinkit_products.csv` – Product details and pricing
* `blinkit_inventory.csv` – Inventory and stock movement
* `blinkit_customers.csv` – Customer demographic information
* `blinkit_customer_feedback.csv` – Customer reviews and sentiment data

---

## 🔎 Exploratory Data Analysis

Sales data was analyzed to uncover important business insights such as:

* Monthly and yearly **sales trends**
* **Order volume patterns**
* **Delivery performance**
* Store performance comparison
* Payment method distribution

These insights help understand **operational efficiency and customer demand patterns**.

---

## 👥 Customer Segmentation (RFM Analysis)

Customers were segmented using **RFM Analysis**:

* **Recency** – Days since last purchase
* **Frequency** – Number of purchases made
* **Monetary** – Total spending by customer

Customer segments include:

* **High Value Customers** – Loyal and frequent buyers
* **Mid Value Customers** – Regular customers
* **Low Value Customers** – Infrequent buyers

This segmentation helps identify **loyal customers and potential churn risks**.

---

## 📈 Feature Engineering

Several business-driven features were created to improve predictive performance:

* Revenue per order
* Revenue growth rate
* Rolling revenue mean (7 days)
* Rolling revenue standard deviation
* Stock-to-revenue ratio
* Price effect gap
* Customer sentiment score
* Time-based features (month, day, weekday)

These features capture **business dynamics, operational signals, and customer behavior**.

---

## 🤖 Machine Learning Model

A **XGBoost Regressor** model was implemented to predict future sales revenue.

### Model Development Steps

1. Data merging from multiple datasets
2. Data preprocessing and feature engineering
3. Train-test split
4. Hyperparameter tuning using GridSearchCV
5. Model evaluation

### Evaluation Metrics

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

---

## 🛠️ Tech Stack

**Programming Language**

* Python

**Data Analysis**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

**Machine Learning**

* Scikit-learn
* XGBoost
* Category Encoders

---

## 📁 Project Structure

```
Blinkit-Sales-Analysis/
│
├── 01_BlinkitOrderAnnalysis.ipynb
├── 02_BlinkitProductAnnalysis.ipynb
├── 03_SalesPrediction.ipynb
│
├── datasets/
│   ├── blinkit_orders.csv
│   ├── blinkit_order_items.csv
│   ├── blinkit_products.csv
│   ├── blinkit_inventory.csv
│   ├── blinkit_customers.csv
│   └── blinkit_customer_feedback.csv
│
└── README.md
```

---

## 🚀 Future Improvements

* Implement **time series forecasting models (ARIMA / Prophet)**
* Build an **interactive dashboard using Streamlit or Power BI**
* Deploy the model for **real-time sales forecasting**
* Add **deep learning models for advanced forecasting**

---

## ⭐ Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Customer Segmentation (RFM)
* Machine Learning Model Development
* Business Data Analysis

---

## 📌 Conclusion

This project demonstrates how **data analytics and machine learning can be applied to retail business data** to uncover insights and forecast revenue. It highlights the importance of **data-driven decision making in improving operational efficiency and customer engagement**.

