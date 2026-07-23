# 📦 Supply Chain & Delivery Performance Analysis

## 📌 Project Overview

This project analyzes a real-world e-commerce supply chain dataset to identify delivery bottlenecks, evaluate shipment profitability, and uncover operational inefficiencies. Using Python, the project follows an end-to-end data analytics workflow, including data cleaning, feature engineering, exploratory data analysis (EDA), visualization, and predictive modeling.

The objective is to help businesses improve delivery performance, reduce delays, optimize shipping operations, and support data-driven decision-making.

---

## 🎯 Business Problem

A global e-commerce company experiences inconsistent delivery performance, where actual shipping times often differ from scheduled timelines. These delays reduce customer satisfaction and impact overall profitability.

---

## 🎯 Objectives

- Analyze delivery performance across orders
- Measure shipment delays and processing time
- Identify factors contributing to delayed deliveries
- Analyze profit and loss associated with delivery delays
- Detect operational bottlenecks
- Predict delayed shipments using Machine Learning

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset:** DataCo Supply Chain Dataset

The dataset contains information about:

- Customer Details
- Product Information
- Order Details
- Shipping Information
- Delivery Status
- Profit & Sales Data

---

## 📊 Project Workflow

### 1️⃣ Data Cleaning
- Removed unnecessary and redundant columns
- Handled missing values
- Converted date columns to datetime format
- Filtered cancelled orders

### 2️⃣ Feature Engineering
Created new business metrics such as:

- Order Processing Time
- Delivery Delay
- Delay Flag
- Profitability Flag
- Order Month
- Order Day
- Order Hour

### 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis on:

- Delivery delays
- Profitability distribution
- Shipping modes
- Customer segments
- Product categories
- Geographic performance
- Time-based trends

### 4️⃣ Business KPIs

Calculated key metrics including:

- Total Orders
- Late Deliveries
- On-Time Delivery Rate
- Late Delivery Rate
- Total Profit
- Profit Loss Due to Delays

### 5️⃣ Predictive Modeling

Built a **Random Forest Classifier** to predict delayed shipments based on historical order information.

---

## 📈 Key Insights

- Majority of orders were delivered within 0–2 days of scheduled delivery.
- Shipment delays significantly reduced overall profitability.
- Certain shipping modes experienced higher delay rates.
- Delivery performance varied across different regions and product categories.
- Predictive modeling successfully identified high-risk delayed orders.

---

## 📁 Project Structure

```
Supply_Chain_Analysis/
│
├── supply_chain_analysis.ipynb
├── DataCoSupplyChainDataset.csv
├── DescriptionDataCoSupplyChain.csv
├── README.md
```

---

## 🚀 Future Improvements

- Build an interactive Power BI dashboard
- Deploy the prediction model using Streamlit
- Automate reporting with scheduled data refresh
- Optimize model performance using hyperparameter tuning

---

## 📸 Project Preview

Add screenshots of:

- Profitability Distribution
- Delay Distribution
- Profit Analysis by Delay
- Shipping Mode Analysis
- Correlation Heatmap
- Machine Learning Results

---

## 📬 Contact

**Nasrin Khatoon**

- GitHub: https://github.com/nasrin567
- LinkedIn: *(Add your LinkedIn profile link)*

---

⭐ If you found this project useful, consider giving it a star!
