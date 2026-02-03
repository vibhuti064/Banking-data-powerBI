# Banking Customer Churn Analysis

## 📌 Project Overview

This repository contains a Power BI Dashboard designed to help a banking institution identify why customers are leaving (churning). By analyzing demographic and financial data, this project provides actionable insights to improve customer retention and service quality.

---

## 📊 Dashboard Link

[View Live Dashboard](https://app.powerbi.com/groups/me/reports/9940eda6-e480-4500-8979-8fe2d8c1f636/1dba3915586acc017c26?experience=power-bi)

---

## ❓ Problem Statement

The bank is facing an increasing rate of customer attrition. This dashboard was developed to:

- Identify high-risk customer segments based on **Age**, **Geography**, and **Credit Score**.
- Analyze the impact of **Active Membership** on retention.
- Understand if **Product Diversity** (number of products) prevents churn.
- Help the bank move from a reactive to a **proactive retention strategy**.

---

## 🛠️ Tech Stack & Steps Followed

| Tool | Details |
|------|---------|
| **Platform** | Power BI Desktop |
| **Data Source** | Banking Customer Dataset (CSV) |
| **Calculations** | DAX (Calculated Columns and Measures) |

### Development Process

1. **Data Cleaning** – Used Power Query Editor to check column distribution and quality.
2. **ETL** – Performed profiling based on the entire dataset to ensure data integrity.
3. **DAX Calculations:**
   - **Age Groups:** Categorized customers into `0-25`, `25-50`, `50-75`, and `75-100`.
   - **Total Customers:** Created a measure `COUNT(Bank_Data[ID])`.
   - **Churn Rate:** Created a measure to calculate the percentage of exited customers.
4. **UI/UX Design** – Applied a professional theme, inserted the bank logo, and utilized shapes for a structured header.

---

## 🔍 Key Insights

From the analysis of **10,000+ customers**, the following inferences were drawn:

### 1. Demographics

- **Age:** The 25–50 age group makes up the majority of the customer base (**52.44%**).
- **Geography:** Customers in **Germany** show higher churn rates compared to France or Spain.
- **Gender:** Female customers have a slightly higher churn percentage than males.

### 2. Behavioral Patterns

- **Active Members:** 81.69% of returning customers are active, while first-time or non-active members are higher risks.
- **Travel Type:** Business travelers (69.06%) show different loyalty patterns than personal travelers.

---

## 📸 Screenshots

### Dashboard Overview

![Dashboard Overview](https://github.com/vibhuti064/Banking-data-powerBI/blob/main/Screenshot%20(1085).png)

### Calculated Columns (DAX)

![DAX Columns](Replace_with_your_image_URL)

---

## 🚀 How to Use

1. Clone this repository.
```bash
   git clone <your_repository_URL>
```
2. Open the `.pbix` file in **Power BI Desktop**.
3. Refresh the data source if necessary.
