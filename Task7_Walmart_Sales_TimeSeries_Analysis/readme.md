# 📊 Task 7: Time Series Breakdown of Retail Sales (Walmart)

This project was created as part of **Task 7** in my internship program. It performs **Time Series Analysis** on Walmart retail sales data to uncover trends, seasonality, and forecast future sales. The analysis also includes revenue breakdowns by store type, store size, and product department.

---

## 📁 Files Included

| File Name                                    | Description                                             |
| -------------------------------------------- | ------------------------------------------------------- |
| `Walmart_Sales_Time_Series_Analysis.ipynb` | Jupyter Notebook with all analysis and forecasting      |
| `Walmart_Sales_Time_Series_Analysis.html`  | Exported HTML version of the notebook                   |
| `train.csv`                                | Weekly sales data (from Kaggle Walmart dataset)         |
| `features.csv`                             | Additional features (temperature, fuel price, holidays) |
| `Store.csv`                                | Store metadata (Type, Size)                             |
| `README.md`                                | Project overview and usage instructions                 |

---

## 📊 Overview

This project analyzes Walmart's retail sales using  **Time Series methods** :

* 📈 **Trends** and **seasonality detection**
* 📊 **Moving averages** for smoothing sales patterns
* 🏬 **Revenue breakdown** by product (departments) and store type
* 🔮 **Forecasting** using  **Exponential Smoothing**

---

## ⚙️ Steps Performed

### 📦 Data Preparation

* Merged multiple datasets: `train.csv`, `features.csv`, and `Store.csv`
* Parsed `Date` column as datetime
* Aggregated weekly sales to **monthly sales**

### 📊 Time Series Analysis

* Plotted overall **sales trend** over time
* Applied **3-month and 6-month moving averages** to detect trends
* Performed **seasonality analysis** using average monthly sales

### 🏬 Revenue Breakdown

* By **Department** (used as Product proxy)
* By **Store Type** (A, B, C)

### 🔮 Forecasting

* Applied **Exponential Smoothing** for more accurate time series forecasting

---

## 📈 Visualizations

* Sales trend and moving averages over time
* Seasonality (sales by month)
* Total sales by:
  * Product Department
  * Store Type

---


## 🛠 Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn (optional, for advanced visualizations)

---
