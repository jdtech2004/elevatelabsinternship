🧹 Cleaned Customer Data

This repository contains a cleaned version of customer data, ready for use in data analysis, machine learning, or business intelligence applications.

---

## 📁 File Included

- cleaned_customer_data (3).xlsx — Excel file with preprocessed and enhanced customer data.

---

## ✅ Cleaning Summary

| Cleaning Task              | Status       |
|---------------------------|--------------|
| Missing Values            | ✅ None found |
| Duplicate Records         | ✅ Removed     |
| Consistent Data Types     | ✅ Confirmed   |
| Standardized Date Format  | ✅ Done (dt_customer) |
| Derived Columns Added     | ✅ age, total_children, total_spending |
| Final Dataset Size        | ✅ 2,240 rows × 32 columns |

---

## 🧾 Column Descriptions

| Column               | Description |
|----------------------|-------------|
| id                 | Unique Customer ID |
| year_birth         | Year of Birth |
| education          | Education Level |
| marital_status     | Marital Status |
| income             | Annual Household Income |
| kidhome            | Number of Children (0–12 yrs) |
| teenhome           | Number of Teenagers (13–19 yrs) |
| dt_customer        | Customer Registration Date |
| recency            | Days since last purchase |
| mntwines to mntgoldprods | Monthly spending in each product category |
| numdealspurchases to numwebvisitsmonth | Purchase behavior and web activity |
| acceptedcmp1 to acceptedcmp5 | Accepted marketing campaigns |
| complain           | Customer complaint flag |
| z_costcontact      | Marketing cost |
| z_revenue          | Revenue from marketing |
| response           | Response to last campaign |
| age                | Customer age (derived from year_birth) |
| total_children     | Sum of kidhome and teenhome |
| total_spending     | Total monthly product spending (sum of mnt* columns) |

---

## 📊 Use Cases

This cleaned dataset can be used for:

- Customer segmentation
- Lifetime value prediction
- RFM (Recency-Frequency-Monetary) analysis
- Targeted marketing modeling
- Dashboard creation using BI tools

---
 Project Author

Maintained by [Jay Dhamankar]