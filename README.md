# Superstore_Sales_Data_Analysis
Ent-to-end data analysis project _ SQL + Power BI
# 📊 Superstore Sales Data Analysis — End-to-End Project
### Real-World Business Intelligence | Excel • SQL • Power BI

---

## 📋 Project Overview
This project demonstrates a complete data analysis pipeline — from raw data preparation to an interactive dashboard — using real-world sales data. Every step was performed manually to ensure accuracy, data integrity, and professional presentation.

---

## 🛠️ Tools Used
- **Microsoft Excel** → Data cleaning, formatting, and validation
- **MySQL / SQL** → Database design, table relationships, and data storage
- **Power BI Desktop** → Data modelling, DAX calculations, and interactive visualisations

---

## 📁 Dataset
- **Source**: Superstore Sales Dataset
- **Files**: `customers.csv`, `orders.csv`, `products.csv`, `locations.csv`, `superstore_sales.csv`
- **Records**: Multiple tables connected through key fields
- **Timeframe**: Multi-year sales performance

---

## 🔧 Step 1 — Data Preparation & Formatting in Excel
Before importing any data, I ensured every file was clean and properly formatted:

### Date Formatting
- Standardised all **date columns** (`Order Date`, `Ship Date`) to a consistent format (`YYYY-MM-DD`)
- Removed inconsistent text-based date entries
- Verified date ranges to ensure logical chronological order
- Saved files in CSV format with comma delimiters for cross-platform compatibility

### Column & Data Type Validation
- **Text fields** (`Customer Name`, `Region`, `Category`, `Product Name`) → trimmed extra spaces, removed special characters, ensured consistent capitalisation
- **Numeric fields** (`Sales`, `Profit`, `Quantity`, `Discount`) → converted from text to proper number format, removed currency symbols, verified decimal places
- **Key / ID columns** (`Customer ID`, `Order ID`, `Product ID`) → ensured uniqueness, no duplicates, consistent naming across tables
- **Geographic data** (`Country`, `State`, `City`, `Region`) → standardised spelling and abbreviations for accurate filtering and mapping

### Final Export
- Saved each cleaned worksheet as a separate CSV file
- Verified no data loss during export
- Confirmed column headers matched across related tables

---

## 🔧 Step 2 — Database Design & Import in SQL
- Created a structured database `retail_analysis`
- Designed tables with appropriate data types:
  - `VARCHAR` for text and identifier fields
  - `INT` for quantities and keys
  - `DECIMAL` for financial values (sales, profit)
  - `DATE` for all date fields
- Established **table relationships**:
  - `orders` ↔ `customers` (via `Customer ID`)
  - `orders` ↔ `products` (via `Product ID`)
  - `orders` ↔ `locations` (via geographic/region fields)
- Imported all cleaned CSV files into their respective tables
- Validated row counts and sample data to confirm successful import

---

## 🔧 Step 3 — Data Modelling in Power BI
- Connected Power BI directly to the MySQL database
- Verified all table relationships: **One-to-Many** cardinality, active connections
- Created calculated columns and measures using **DAX**:
  - Total Sales, Total Profit, Profit Margin
  - Yearly and Quarterly Sales Trends
  - Regional Performance Metrics
- Ensured consistent formatting across all visuals

---

## 🔧 Step 4 — Dashboard Design & Insights
Designed an interactive dashboard featuring:
- 📈 **Sales Trend Over Time** — Line chart showing performance across the period
- 📊 **Sales by Region** — Clustered column chart comparing geographic performance
- 🥧 **Profit by Customer Segment** — Donut chart showing segment contribution
- 📍 **Regional Distribution** — Map visual (and decomposition tree) for geographic breakdown
- 📋 **Key Metrics Cards** — At-a-glance totals for Sales, Profit, and Quantity
- 🔍 **Interactive Filters / Slicers** — By year, region, and category for dynamic exploration

### Key Business Insights Identified
- Top-performing regions and product categories
- Seasonal sales patterns and growth trends
- Profitability variations across customer segments
- Opportunities in underperforming areas

---

## 🎬 Project Walkthrough
- Full video demo available on LinkedIn:
  🔗 [https://lnkd.in/p/eNQvAKHT]

---

## ✅ Project Status
| Stage | Status |
|---|---|
| Data cleaning & formatting in Excel | ✅ Complete |
| CSV export & validation | ✅ Complete |
| SQL database design & import | ✅ Complete |
| Power BI connection & data modelling | ✅ Complete |
| DAX measures & calculations | ✅ Complete |
| Dashboard design & visualisation | ✅ Complete |
| GitHub documentation | ✅ Complete |

---

## 💡 Key Learnings
- **Data validation** at every step prevents problems later
- Consistent **naming and formatting** across files is critical for successful joins
- Understanding **data types** ensures accurate calculations and relationships
- Iterative refinement — checking, adjusting, and rechecking — produces professional results

---

*Built with dedication and a passion for data analysis. Continuously learning, improving, and building real-world skills.* 🚀
---
**Shumaila**
*Aspiring Data Analyst*
United Kingdom 🇬🇧
