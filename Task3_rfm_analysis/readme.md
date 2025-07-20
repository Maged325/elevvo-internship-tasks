# 🧠 RFM Customer Segmentation with Python

This project performs **Customer Segmentation** using **RFM Analysis** (Recency, Frequency, Monetary) on an online retail dataset.

## 📁 Files Included

| File Name                           | Description                                  |
| ----------------------------------- | -------------------------------------------- |
| `RFM_Customer_Segmentation.ipynb` | Jupyter Notebook with all EDA & RFM analysis |
| `RFM_Customer_Segmentation.html`  | Exported HTML version of the notebook        |
| `OnlineRetail.csv`                | Sales dataset (from UCI via Kaggle)          |
| `README.md`                       | Project overview and usage instructions      |

---

## 📊 Overview

RFM analysis segments customers based on their:

- **Recency (R):** Days since last purchase
- **Frequency (F):** Total number of purchases
- **Monetary (M):** Total amount spent

These are then scored from 1 (lowest) to 5 (highest) to create segments like `"555"` or `"311"`.

---

## ⚙️ Steps Performed

1. **📦 Data Cleaning**

   - Removed missing `CustomerID`
   - Filtered only positive `Quantity` and `UnitPrice`
   - Parsed `InvoiceDate` to datetime
2. **📐 RFM Metrics Calculation**

   - Aggregated Recency, Frequency, and Monetary value per customer
   - Used latest date (`max(InvoiceDate)`) as reference point
3. **🔢 RFM Scoring & Segmentation**

   - Used quantiles to assign scores for R, F, M
   - Created `RFM_Score` and defined customer groups
4. **📈 Visualizations**

   - Bar chart of segment distribution

---



## 💡 Marketing Ideas

| Segment       | Strategy                               |
| ------------- | -------------------------------------- |
| Champions     | Offer loyalty rewards                  |
| At Risk       | Send personalized re-engagement emails |
| Hibernating   | Discounts to encourage comeback        |
| New Customers | Welcome emails & onboarding            |

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib

---

## 📸 Sample Output

![1753045749144](image/readme/1753045749144.png)

---

## ✍️ Author

* #### Maged (Elevvo Internship Project - Task 3)

---
