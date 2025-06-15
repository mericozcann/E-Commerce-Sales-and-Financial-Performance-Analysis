# 🛒 E-Commerce Order and Financial Analysis Project

This project aims to analyze sales data from an e-commerce platform to uncover key business insights and evaluate financial performance.

The study is structured in two parts:
- 📊 **General Order Analysis** – Conducted using **Excel**
- 🧮 **Financial Analysis** – Conducted using **Python**

---

## 📁 Project Overview

### 1. General Order Analysis (Excel)

Basic data exploration and visualization were conducted in Excel to answer the following business questions:

#### ✅ Easy-Level Questions
- What is the total number of orders?
- Which cities have the highest number of orders?
- What are the most sold products?
- Which brands received the most orders?
- How are the orders distributed monthly?

#### ⚙️ Medium-Level Questions
- What is the status distribution of the orders (completed, canceled, in delivery)?
- Who are the top ordering customers?
- Are there any orders with missing or invalid tracking numbers?
- What is the average selling price of the products?
- How do brands contribute to total sales?

#### 🔍 Hard-Level Questions
- How do order trends change seasonally?
- What is the average order value per city?
- What are the delivery durations across different cities?
- Which products or cities have higher cancellation rates?

> 📌 *Tools used:* Pivot Tables, Filtering, Bar Charts, Boxplots, and Seasonal Trend Visualizations.

---

### 2. Financial Analysis (Python)

In-depth financial metrics and customer value analysis were performed using Python.

#### ✅ Easy-Level Questions
- What is the total revenue?
- How does monthly revenue vary?
- Which products generate the most revenue?
- Which cities contribute the most to total revenue?

#### ⚙️ Medium-Level Questions
- How is the revenue distributed across brands?
- What is the average spending per customer?
- Who are the high-value customers?
- What is the average price per product?
- What is the financial impact of canceled orders?

#### 🔍 Hard-Level Questions
- How can customers be segmented based on purchasing behavior?
- Which products are the most profitable based on unit price and quantity?
- Are high-value orders more likely to have tracking issues?
- What products or brands will likely be popular in the future?
- Should pricing strategies be customized per city?

#### 📊 Reporting & Results
- The Excel dashboard offers a user-friendly overview of product, city, and monthly order performance.

- The Python analysis allows for data cleaning, automation, and deeper insights into revenue, customer value, and profitability.

- Seasonal trends and cancellation hotspots were identified.

- High-value customer segments were successfully detected.

- Revenue-driving products and underperforming cities were clearly visualized.

#### 🧠 Key Learnings
- Excel is excellent for fast visual exploration and summary statistics, especially when working with stakeholders or non-technical users.

- Python offers superior control for complex analysis, segmentation, financial evaluation, and scaling for larger datasets.

- Data quality (e.g., missing tracking numbers) and feature engineering (e.g., season, holidays) play a crucial role in generating actionable insights.

- Creating a multi-layered question framework (easy-medium-hard) is highly effective in guiding business problem-solving.

#### 🔧 Future Improvements
- 📈 Integrate forecasting models (e.g., ARIMA, Prophet) to predict future demand.

- 🗂 Add automated dashboards using tools like Power BI or Tableau.

- 🤖 Include clustering techniques (K-Means, DBSCAN) for advanced customer segmentation.

- 🧪 Perform A/B testing simulations to test pricing strategies across cities or brands.

- 🔄 Build an automated ETL pipeline for real-time reporting and updates.

#### Data Source: https://blog.excel751.com/

#### 🧰 Python Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
