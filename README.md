# Coffee-Shop-Analysis



## Project Overview

This project analyzes transactional sales data from Bright Coffee Shop to uncover key revenue drivers, customer purchasing behavior, and time-based sales trends. The goal is to support the CEO in making data-driven decisions to grow revenue and improve product performance.

---

## 🎯 Business Objectives

* Identify products generating the highest revenue
* Determine peak sales periods during the day
* Analyze sales trends across product categories and time intervals
* Provide actionable recommendations to improve overall performance

---

## 🛠️ Tools & Technologies

* Databricks (SQL & Data Processing)
* Microsoft Excel (Data Analysis & Visualization)
* Miro (Project Planning & Architecture)
* Canva (Presentation Design)
* GitHub (Version Control)

---

## 🔄 Project Methodology & Workflow

This project followed a structured, end-to-end analytics workflow:

1. **Project Planning (Miro)**

   * Designed the data flow and architecture diagram
   * Mapped how data moves from source → processing → storage → analysis

2. **Project Scheduling (Gantt Chart)**

   * Created a timeline to manage project phases efficiently
   * Structured tasks into planning, processing, analysis, and presentation

3. **Data Processing (Databricks)**

   * Converted Excel dataset into CSV format
   * Loaded data into Databricks
   * Performed SQL transformations and calculations

4. **Data Analysis & Visualization (Excel)**

   * Built pivot tables and dashboards
   * Analyzed revenue, product performance, and time-based trends
   * Created charts to visualize insights

5. **Presentation (Canva)**

   * Designed a professional presentation for the CEO
   * Included insights, visuals, and business recommendations

---

## 🏗️ Data Architecture

**Source → Processing → Storage → Analysis → Presentation**

* Source: Excel dataset (Bright Coffee Shop Sales)
* Processing: Databricks (SQL transformations)
* Storage: Databricks tables
* Analysis: Excel dashboards
* Presentation: Canva

---

## ⚙️ Data Processing (Key Transformations)

The dataset was cleaned and transformed using SQL in Databricks. Key transformations include:

Created transaction_time_bucket using CASE statements to group transactions into time intervals (e.g., morning, afternoon, evening or 30-minute/3-hour buckets)
Created day_type classification using CASE statements:
Weekday
Weekend

---

## 📊 Key Insights

* Coffee products are the **top-performing category**, contributing the highest share of revenue 
* Sales peak during specific time intervals 
* Some product categories consistently underperform
* Customer purchasing patterns show strong demand for selected items

---

## 📉 Underperforming Areas

* Certain products generate low revenue and sales volume
* Possible reasons:

  * Low demand
  * Ineffective pricing
  * Lack of promotion

---

## 💡 Business Recommendations

* Increase marketing during **low-sales time periods**
* Focus inventory on **top-performing products (coffee items)**
* Introduce **product bundling strategies** (e.g., coffee + pastry deals)
* Promote underperforming products through discounts or campaigns

---

## 📊 Data Visualization

The analysis was presented using Excel dashboards, including:

* Revenue by product category
* Sales by time intervals
* Quantity sold by product type
* Best-selling products

---

## 📂 bright-coffee-analysis/
│── sql/
│   └── coffee_analysis.sql
│
│── dashboard/
│   └── excel_dashboard.xlsx
│
│── presentation/
│   └── final_presentation.pdf
│
│── planning/
│   ├── miro_board.pdf
│   └── gantt_chart.pdf
│
│── README.md
```


## 📌 Conclusion

This project demonstrates how data analytics can be used to uncover insights into product performance and customer behavior. The findings provide a strong foundation for improving sales strategies and driving business growth.

---
