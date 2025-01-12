# Comprehensive Retail Sales Analysis and Reporting

Welcome to my final project: **Comprehensive Retail Sales Analysis and Reporting**, which leverages **Python, SQL, Excel, and Power BI**. This project focuses on understanding customer behavior and enhancing sales performance for a retail business. The goal is to turn raw data into actionable insights to support better decision-making.

---

## Table of Contents

- 🌟 [Project Overview](#project-overview)
- [The Problem](#the-problem)
- [Questions and Answers](#questions-and-answers)
  1. [What is the structure of the sales data?](#1-what-is-the-structure-of-the-sales-data)
  2. [How do we clean and prepare the data for analysis?](#2-how-do-we-clean-and-prepare-the-data-for-analysis)
  3. [Who are our top customers?](#3-who-are-our-top-customers)
  4. [What are the sales trends over time?](#4-what-are-the-sales-trends-over-time)
  5. [How can we classify customers for targeted strategies?](#5-how-can-we-classify-customers-for-targeted-strategies)
  6. [Can we predict future sales and retention?](#6-can-we-predict-future-sales-and-retention)
- [Visualizing the Insights](#visualizing-the-insights)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Conclusion](#conclusion)

---

## 🌟 Project Overview

This project addresses key questions that every retail business faces:

- **How can we identify our top customers?**
- **What are our sales trends over time?**
- **Which customer segments drive the most revenue?**
- **How can we predict future sales and customer retention?**

By using a combination of tools and techniques, I have created a data-driven approach to answer these questions and provide valuable insights for business growth.

---

## The Problem

Retail businesses often struggle with:

1. **Understanding Customer Behavior:** Who are our most valuable customers, and how do they interact with our business?
2. **Optimizing Sales Performance:** How can we identify trends and areas for improvement in our sales strategy?
3. **Predicting Future Performance:** Can we forecast future sales and customer retention rates?

To address these challenges, I analyzed a retail dataset and provided clear, actionable solutions.

---

## Questions and Answers

### 1. What is the structure of the sales data?

**Question:** What data do we have, and how is it organized?

**Answer:**
- The data consists of two tables:
  - **Transactions Table:** Contains customer transactions, including dates, amounts, and customer IDs.
  - **Responses Table:** Includes customer responses and feedback.

Steps taken:
- Created a database called `Retail_db`.
- Queried and reviewed data to confirm structure.

---

### 2. How do we clean and prepare the data for analysis?

**Question:** What steps are needed to prepare the data for analysis?

**Answer:**

Key steps:
- **Indexed Customer IDs:** Improved query performance by adding an index.
- **Handled Missing Values:** Updated missing transaction amounts to `0` to avoid skewed results.
- **Removed Outliers:** Used the **Interquartile Range (IQR)** method to eliminate extreme values.
- **Date Extraction:** Extracted day, month, and year components to enable time-based analysis.

---

### 3. Who are our top customers?

**Question:** How can we identify our most valuable customers?

**Answer:**
- Calculated total spending per customer.
- Identified the top 5 high-value customers.
- Insights: These customers contribute significantly to overall sales and should be prioritized in marketing efforts.

---

### 4. What are the sales trends over time?

**Question:** How have sales changed over the years and months?

**Answer:**
- Aggregated sales data by year and month.
- Visualized trends using line charts in Power BI.

**Insights:**
- Peak sales occurred during specific months, suggesting seasonal demand.
- Steady year-over-year growth was observed.

---

### 5. How can we classify customers for targeted strategies?

**Question:** How do we group customers based on their value to the business?

**Answer:**
- Implemented **RFM Analysis**:
  - **Recency:** Days since the last transaction.
  - **Frequency:** Number of transactions.
  - **Monetary:** Total spending.

**Results:**
- Customers were segmented into categories like "Best Customers," "Loyal Customers," and "At-Risk Customers."

---

### 6. Can we predict future sales and retention?

**Question:** What can we learn about future performance?

**Answer:**
- **Cohort Analysis:** Tracked customer retention based on their first purchase date.
- **Time Series Forecasting:** Predicted future sales using historical trends.

**Outcome:**
- Retention rates were highest for customers acquired during promotional campaigns.
- Predicted growth opportunities for the upcoming year.

---

## Visualizing the Insights

### Power BI Dashboard

Snapshot of the Power BI dashboard created to visualize the sales data:

![Screenshot 2024-08-28 000355](https://github.com/user-attachments/assets/1f381293-1e75-48e0-8b27-11c3727fbfb1)

![Screenshot 2024-08-28 000415](https://github.com/user-attachments/assets/59cf7209-a23e-4864-a808-c76c86c80a52)

### Excel Dashboard

Snapshot of the Excel dashboard created to visualize the sales data:

![Screenshot 2024-08-30 161244](https://github.com/user-attachments/assets/b7f4549e-2514-4dff-84d4-e06022568ed3)

![Screenshot 2024-09-19 225730](https://github.com/user-attachments/assets/8e3cd63f-b05a-4c5c-ae00-49798af65c52)

---

## Tools and Technologies Used

- **Python:** For data manipulation and statistical analysis.
- **SQL:** To query and prepare data efficiently.
- **Excel:** For detailed calculations and dashboards.
- **Power BI:** For creating interactive visualizations and sharing insights.

---

## Conclusion

This project demonstrates the value of combining data analytics tools to solve real-world business problems. By addressing key questions about customer behavior and sales performance, I have provided actionable recommendations for improving marketing strategies, optimizing inventory, and driving growth.

---

**Contact**  
Ayush Uprety  
📧 [ayushuprety1@gmail.com](mailto:ayushuprety1@gmail.com)



