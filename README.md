# Simulated Ecommerce Dataset

## Overview
This repository contains a clean, structured e-commerce dataset designed for data analysis, machine learning, and business intelligence projects. It simulates real-world e-commerce transactions, providing an excellent foundation for exploring sales trends, customer purchasing behavior, marketing efficiency, and product performance.

## File Information
- **File Name:** `Simulated Ecommerce Dataset 1.xlsx`
- **Format:** Excel Workbook (.xlsx)
- **Status:** Cleaned and ready for immediate analysis (no missing values or structural errors).

## 📈 Dashboard & Key Insights Summary

This section provides a high-level overview of the simulated e-commerce performance based on the dataset's dashboard and pivot table aggregations.

### Executive KPIs
* **Total Revenue:** 95,894,557
* **Gross Profit:** 30,563,209.48
* **Total Marketing Spend:** 2,068,719.07
* **Total Orders:** 1,812
* **Overall Return on Ad Spend (ROAS):** 46.35

### Acquisition Channel Performance
* **Top Revenue Driver:** WhatsApp is the highest-performing channel, generating the most revenue (19,279,810.95), the highest Net Contribution (5,809,270.24), and the highest Average Order Value (AOV) of 57,897.33. 
* **Most Efficient Spend:** Organic Search delivers the highest ROAS at a staggering 184.43, costing only 82,671.85 to generate 15,247,186.20 in revenue. This indicates highly effective SEO or strong brand recognition.
* **Underperforming Channels:** Instagram has the lowest ROAS (35.18) and the lowest AOV (47,424.07), despite accounting for the highest marketing spend (396,221.16). 

### Regional Highlights
* **Strongest Markets:** Rivers, Kano, and Enugu show strong localized Return on Ad Spend (ROAS exceeding 46 in each region) alongside high gross margins.
* **Volume vs. Efficiency:** Lagos and Abuja drive consistent order volumes but exhibit slightly lower ROAS compared to the top-performing regions, suggesting higher customer acquisition costs or increased market competition in major metropolitan areas. 

### Strategic Recommendations
* **Reallocate Marketing Budget:** Shift marketing spend away from lower-efficiency channels like Instagram and redirect it toward scaling WhatsApp marketing and capturing more Organic Search traffic.
* **Regional Targeting:** Replicate the high-efficiency marketing tactics currently used in Rivers and Kano across lower-performing regions like Lagos to improve overall profit margins.

## 🚀 Potential Use Cases
This dataset is highly versatile and can be used for various analytical tasks, including:
- **Exploratory Data Analysis (EDA):** Uncover seasonal sales trends, top-performing product categories, and regional revenue distribution.
- **Marketing Analytics:** Deep dive into ROAS by channel to optimize marketing budgets.
- **Customer Segmentation:** Apply RFM (Recency, Frequency, Monetary) analysis to identify high-value and at-risk customers.
- **Dashboard Creation:** Seamlessly import the file into BI tools like Tableau, Power BI, or Looker Studio to build interactive reports.

## 💻 Getting Started (Python Example)
To begin exploring this dataset using Python and Pandas, you can use the following code snippet:

```python
import pandas as pd

# Define the file path
file_path = 'BoyCodeAfrica Simulated Ecommerce Dataset 1.xlsx'

# Load the dataset
df = pd.read_excel(file_path)

# View the first 5 rows
print(df.head())

# Get summary statistics to verify metrics like Total Revenue and Marketing Spend
print(df.describe())
```
