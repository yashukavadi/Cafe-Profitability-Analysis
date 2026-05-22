# Cafe Profitability & Business Intelligence Dashboard

## 📌 Project Overview
This project focuses on transforming raw cafe operational data into actionable business insights. Using an end-to-end data analytics workflow, I designed a relational database query logic to analyze menu item profit margins and developed an interactive executive dashboard to track revenue, costs, and overall net performance.

## 🛠️ Tech Stack & Tools Used
* **Database Management:** Oracle SQL / FreeSQL (DDL, DML, Joins, Aggregations, Case Logic)
* **Business Intelligence:** Advanced Excel (Power Query, Data Formatting, Cell Styling, Formulas)
* **Data Visualization:** Interactive Excel Charts & Dynamic Slicers

---

## 💻 SQL Database Logic & Implementation
To calculate exact profitability metrics per item, I executed complex queries linking menu specifications with sales transaction tables. The logic includes:
1. **Financial Aggregations:** Mathematically deriving total revenue and net profit by isolating making costs from selling prices across item quantities sold.
2. **Conditional Categorization:** Implementing `CASE WHEN` conditional logic to dynamically segment products into performance tiers (*'Super Profit'*, *'AVG PROFIT'*, and *'LOW MARGIN'*).

*The complete structured scripts can be viewed in the `Cafe_Queries.txt` file above.*

---

## 📊 Interactive Excel Dashboard Features
After querying the data, I structured the dataset inside Advanced Excel to build a clean corporate dashboard layout featuring:
* **Professional Accounting Formatting:** Applied double-underline summary totals adhering to global financial reporting design standards.
* **Dynamic Data Visualization:** Built a tailored vertical bar chart tracking net profitability across menu items.
* **Interactive Control Filters (Slicers):** Implemented dynamic category buttons allowing users to filter dashboards on the fly between *Drinks* and *Snacks* with zero lag.

---

## 💡 Core Business Insights Derived
* High-margin items were successfully distinguished from low-margin operational bottlenecks to assist in future menu optimization.
* Executive stakeholders can interactively view and filter specific sales distributions instantly to drive seasonal marketing decisions.
