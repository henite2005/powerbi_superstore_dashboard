# 🛒 Superstore Power BI Dashboard

## 📌 Overview

The **Superstore Power BI Dashboard** is an interactive business intelligence report designed to help stakeholders understand key metrics around sales performance, profitability, and operational efficiency within a retail environment. This dashboard visualizes trends, uncovers insights, and supports data-driven decision-making for management and sales teams.

![store_a](https://github.com/user-attachments/assets/f1255c5f-6787-49f1-a775-23e783eebce9)

---

## 🎯 Problem Statement

Despite growing data in Superstore operations, decision-makers often struggle to derive actionable insights quickly. The lack of real-time visibility into region-wise performance, profit drivers, and loss-making categories leads to sub-optimal resource allocation and strategic decisions.

The **goal** of this dashboard is to centralize important metrics, identify key trends, and offer a snapshot of Superstore operations in a clear, visual, and filterable manner.

---

## 💡 Problems the Dashboard Solves

- Identifies **low-performing regions, products, and segments** contributing to losses.
- Highlights **profitable categories and customer segments** for future targeting.
- Analyzes **delivery timelines** and their impact on customer satisfaction and returns.
- Monitors **sales pipeline health**, including **trends and seasonality**.
- Tracks **sales and profit** by key dimensions such as **category, region, and customer segment**.
- Supports **real-time filtering** to drive decision-making at different organizational levels.

---

![store_b](https://github.com/user-attachments/assets/4d77ca2a-0fd7-4271-a4f4-d049fb090fd3)


## 📈 Key KPIs Monitored

| KPI                           | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| **Total Sales**              | Total revenue generated over the selected time period                       |
| **Total Profit**             | Net profit across all transactions                                          |
| **Profit Margin (%)**        | Ratio of profit to sales, highlighting efficiency                          |
| **Total Orders**             | Count of all fulfilled customer orders                                      |
| **Average Discount**         | Mean discount rate across sales, indicating promotional impact              |
| **Returned Orders**          | Orders that were returned, hinting at fulfillment or satisfaction issues    |
| **Top 5 Products by Profit** | Helps isolate key revenue-driving products                                  |
| **Sales by Region/State**    | Visual breakdown of geographical performance                                |
| **Customer Segments**        | Sales and profit by Corporate, Consumer, and Home Office segments           |

---

## 📊 Dashboard Features

### 📍 Interactive Filters
- Region
- Order Date (Calendar Slicer)
- Customer Segment
- Product Category/Sub-Category
- Shipping Mode

### 📍 Visualizations
- KPI Cards (Sales, Profit, Orders)
- Bar and Column Charts (Sales/Profit by Category and Segment)
- Line Chart (Monthly Sales Trend)
- Map Chart (Sales by State)
- Pie Charts (Profit Distribution)
- Matrix Table (Multi-dimensional sales breakdown)
- Scatter Plot (Discount vs Profit impact)

### 📍 Drillthrough & Tooltips
- Drill-through pages for customer details and product-level views
- Hover tooltips to provide instant metric insight

---

## 🧑‍💼 Target Users

- Sales & Marketing Teams
- Regional Managers
- Inventory & Supply Chain Managers
- Executives and Decision Makers

---

## 🏁 How to Use

1. **Download the Superstore Dataset** from [Kaggle](https://www.kaggle.com/datasets) or your internal source.
2. Load the data into Power BI Desktop.
3. Connect visualizations with fields like:
   - `Order Date`
   - `Sales`
   - `Profit`
   - `Region`
   - `Category`
   - `Sub-Category`
   - `Customer Segment`
4. Customize filters based on your needs.
5. Publish to Power BI Service for collaborative access.

---

## 📦 Data Sources Used

- `Orders.csv` (Core dataset)
- `Returns.csv` (Optional, to track returns)
- `People.csv` (Optional, to map salespeople)

---

## 🔧 Enhancements (Optional)

- Integration with SQL or Azure Synapse for larger datasets
- Real-time refresh via Power BI Gateway
- Mobile-optimized version using responsive views
- Custom tooltips and Bookmarks for storytelling

---

## 📜 License

This dashboard was built using open Superstore sample data and is intended for educational analytics purposes.

---

## 🙌 Credits

- Superstore Dataset by Tableau
- Power BI Community
- UI Inspiration from Microsoft Sample Reports
