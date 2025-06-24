# 🛒 Retail Vendor Intelligence Dashboard

A data-driven, interactive dashboard solution built to analyze and optimize vendor performance, inventory turnover, and profitability in the retail industry using Python, SQL, and Power BI.

---

## 📝 Short Description / Purpose

The **Retail Vendor Intelligence Dashboard** is a comprehensive Power BI report designed to uncover hidden trends in sales, purchasing behavior, profit margins, and stock turnover. It transforms raw retail data into business-critical insights that support strategic decisions in vendor management, pricing, and inventory control.

---

## ⚙️ Tech Stack

This project uses the following technologies and tools:

- 🐍 **Python** – Used for data loading, cleansing, and ingestion.
- 🛢️ **SQL (SQLite)** – Backend database storing structured retail data.
- 📊 **Power BI Desktop** – Main tool for building dashboards and visualizations.
- 🔍 **Power Query (M)** – For data shaping and transformation within Power BI.
- 🧮 **DAX (Data Analysis Expressions)** – For calculated fields and KPIs.
- 💾 **File Formats** – `.pbix` for dashboard, `.ipynb` for EDA, `.db` for database.

---

## 📂 Data Source

The dataset consists of multiple CSV files related to vendor sales, inventory, purchases, and profitability.

- Loaded and structured using a Python script (`load_to_sqlite.py`)
- Ingested into a local **SQLite database** (`inventory.db`)
- Used for downstream visual analysis in Power BI

Each CSV is saved as a table in the database with its filename as the table name.

---

## ✨ Features & Highlights

### ✅ Business Problem

Retail businesses often struggle with underperforming brands, inefficient stock turnover, and over-reliance on key vendors. Without clear insights, profitability is impacted due to pricing inefficiencies, bulk ordering mishaps, and operational delays.

### 🎯 Dashboard Goal

To build an interactive Power BI dashboard that:

- Identifies underperforming vendors and brands
- Reveals inventory inefficiencies
- Analyzes the impact of bulk purchases
- Detects profit margin variations
- Provides actionable insights for better vendor and pricing strategies

---

### 📊 Key Visuals

| Visual | Description |
|--------|-------------|
| **KPIs** | Track metrics like total gross profit, average unit cost, unsold inventory, and vendor count |
| **Top Vendors by Sales & Purchases** | Bar charts highlighting major contributors to revenue and purchase volume |
| **Profit Margin Analysis** | Box plots comparing high- vs low-performing vendors |
| **Brand Performance Scatter Plot** | Plots sales vs. profit margin to identify promotion opportunities |
| **Stock Turnover Visuals** | Showcases inventory inefficiencies and slow-moving stock |
| **Bulk Purchase Impact** | Analyzes unit cost reduction with higher order volume |

---

## 📈 Business Impact & Insights

- 💰 **Bulk Purchase Cost Savings**: 72% lower unit cost for large orders
- 🧾 **Vendor Concentration Risk**: Top 10 vendors contribute ~66% of purchases
- 📦 **Inventory Inefficiency**: $2.71M in unsold inventory
- 📉 **Profit Margin Imbalance**:
  - Top Vendors: ~31% average profit margin
  - Low Vendors: ~41% margin but low sales
- 📌 **Actionable Strategies**:
  - Promote high-margin but low-sales brands
  - Diversify vendor base
  - Optimize bulk purchase decisions
  - Improve stock movement and cash flow

---

## 🧪 Hypothesis Testing

- **Null Hypothesis (H₀)**: No significant difference in profit margins between top and low-performing vendors
- **Alternative Hypothesis (H₁)**: Significant difference exists
- **Result**: H₀ rejected – vendors follow different profitability models

---

## 🖼️ Screenshots

### 📊 Power BI Dashboard
![Retail Vendor Power BI Dashboard](screenshots/dashboard.png)

*Alt text: Interactive dashboard showing vendor analysis with KPIs, bar charts, and scatter plots.*

---

## 📁 Folder Structure


