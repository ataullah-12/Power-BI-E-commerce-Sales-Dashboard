# 🛒 E-Commerce Sales Analytics Dashboard (Power BI)

## 📌 Project Overview

This project presents an interactive **E-Commerce Sales Analytics Dashboard** built using **Microsoft Power BI**. The goal of this dashboard is to transform raw order and transaction data into meaningful business insights that help analyze sales performance, profitability, customer spending patterns, and payment preferences.

The dashboard provides a clear overview of key business metrics and enables dynamic filtering to explore trends across different time periods and regions.

---

# 🎯 Business Objectives

The dashboard answers key business questions such as:

• What is the total revenue generated from e-commerce sales?
• Which product subcategories generate the highest profit?
• Which customers contribute the most to revenue?
• How do profits vary across months?
• What payment methods are most commonly used?
• How does product category distribution affect sales quantity?

---

# 🧰 Tools & Technologies

| Tool                    | Purpose                                   |
| ----------------------- | ----------------------------------------- |
| **Power BI Desktop**    | Data visualization and dashboard creation |
| **Power BI DAX**        | Calculated metrics and aggregations       |
| **Excel / CSV Dataset** | Source data                               |
| **GitHub**              | Project portfolio showcase                |

---

# 📂 Dataset Description

This dashboard uses two datasets:

### **1️⃣ Orders Dataset**

Contains order level information such as:

* Order ID
* Order Date
* State
* Customer Name

---

### **2️⃣ Details Dataset**

Contains transaction details including:

* Order ID
* Product Category
* Sub Category
* Quantity
* Amount
* Profit
* Payment Mode

Both datasets were **connected using Order ID** to enable relational analysis.

---

# 📊 Dashboard Features

The dashboard includes multiple visualizations to analyze business performance.

---

## 1️⃣ KPI Metrics (Cards)

Key performance indicators are displayed using **Power BI card visuals**:

* **Total Sales (Sum of Amount)**
* **Total Quantity Sold**
* **Total Profit**
* **Average Order Value (AOV)**

These KPIs provide a quick summary of overall business performance.

---

## 2️⃣ Profit by Sub-Category and State

**Horizontal Bar Chart**

Displays profit contribution by product **sub-category and state**, helping identify high-performing product segments and regions.

---

## 3️⃣ Monthly Profit Trend

**Vertical Column Chart**

Shows profit distribution across months to identify **seasonal sales patterns and profit fluctuations**.

---

## 4️⃣ Top 5 Customers by Revenue

**Vertical Bar Chart**

Highlights the **top 5 customers generating the highest revenue**, helping businesses identify valuable customers.

---

## 5️⃣ Category-wise Quantity Distribution

**Donut Chart**

Shows percentage distribution of product quantity across different **product categories**.

---

## 6️⃣ Payment Mode Distribution

**Donut Chart**

Displays the percentage of transactions by **payment mode**, helping understand customer payment preferences.

---

# 🎛 Interactive Filters

The dashboard includes interactive filters for dynamic analysis.

### Quarter Filter (Dynamic Tiles)

Users can filter data by:

* **Q1**
* **Q2**
* **Q3**
* **Q4**

This allows quick comparison of quarterly performance.

---

### State Filter

A **dropdown filter** allows users to analyze sales and profit performance for specific states.

---

# 📈 Key Insights

The dashboard enables insights such as:

• Identification of the most profitable product subcategories
• Recognition of top revenue generating customers
• Understanding of seasonal profit trends
• Analysis of payment method popularity
• Category-wise product demand distribution

---

# 📷 Dashboard Preview

*<img width="596" height="331" alt="E Sales Dashboard Sreenshot" src="https://github.com/user-attachments/assets/0f55fee2-5246-4c46-bbbf-af0795b19cef" />
*

Example:

```
/screenshots/dashboard.png
```

---

# 📁 Project Structure

```
powerbi-ecommerce-dashboard

│
├── dataset
│   ├── Orders.csv
│   └── Details.csv
│
├── dashboard
│   └── Ecommerce_Dashboard.pbix
│
├── screenshots
│   └── dashboard_preview.png
│
└── README.md
```

---

# 🚀 How to Reproduce

1. Download the datasets
2. Open **Power BI Desktop**
3. Import the **Orders and Details datasets**
4. Create relationships using **Order ID**
5. Create calculated measures and visualizations
6. Build dashboard visuals and filters
7. Save the Power BI file (.pbix)

---

# 💡 Skills Demonstrated

• Data Visualization
• Business Intelligence
• Dashboard Design
• Data Modeling
• KPI Analysis
• Interactive Data Exploration

---

# 👤 Author

**Mohd Ataullah (Atah)**

Business Analyst |Automation Developer | Data Analytics Enthusiast

Skills: Python • AWS • Power BI • Data Analytics • BI Dashboards

---

⭐ If you found this project useful, consider giving it a star!
