# 📊 Financial Sales Dashboard (Power BI + Tableau)

## Project Overview
This repository contains a comprehensive financial sales analysis built using both **Power BI** and **Tableau Public**. The analysis tracks **$118.73M in Total Revenue** and **$16.89M in Total Profit** across global markets, optimizing visibility into product performance, regional growth, and profit margins.

Both dashboards are designed with an **executive dark theme layout**, ensuring clear visual hierarchy and an intuitive user experience for corporate stakeholders and business analysts.

---

## ⚡ Power BI Dashboard

### 🚀 Special & Advanced Features

#### 1. Multi-Page Seamless Navigation
Instead of cluttered single-view reports, this project splits the financial story into two dedicated strategic views, accessible via an interactive sidebar navigation menu:
- **Sales Analysis Dashboard:** Focuses on macro-level volume, identifying revenue engines, regional sales distributions, and timeline trend scales.
- **Profit Analysis Dashboard:** Focuses strictly on financial health, breaking down margins, cost-impact ratios, and identifying high-performing versus underperforming segments.

#### 2. Dynamic Cross-Filtering & Interactive Slicers
- **Year Slicer (`2013` vs. `2014`):** Instantly filters historical performance to evaluate year-over-year operational growth.
- **Segment Multi-Select Slicer:** Toggles views across key business verticals: Government, Small Business, Enterprise, Midmarket, and Channel Partners.

#### 3. Advanced Visual Selection & KPI Card Layouts
- **Waterfall Chart Integration:** Utilized for Profit Margin % by Product to showcase cumulative margins clearly.
- **Donut Chart Percentage Slices:** Represents Profit by Segment with exact dollar margins and contribution percentages.
- **High-Contrast Minimalist KPI Blocks:** Positioned at the top for instantaneous baseline awareness.

### 📈 Key Metrics & Data Insights
- **Top Revenue Product:** Paseo leads global sales at $33M, followed by VTT at $21M.
- **Top Profit Engine:** Paseo drives the highest net profit at $4.8M, while Carretera lags at $1.8M.
- **Highest Profit Margin:** Amarilla commands 16%, followed by VTT and Paseo at 15%.
- **Dominant Segment:** Government sector contributes $11.39M (65.04%) to total profit.
- **Geographic Performance:** USA and Canada lead at $27M each, followed by France ($26M), Germany ($25M), Mexico ($23M).

### 🛠️ Tech Stack
- **Tool:** Microsoft Power BI Desktop
- **Data Transformation:** Power Query (ETL, data cleaning, type conversion)
- **Calculations:** DAX (custom KPI measures, time intelligence, margin calculations)
- **UI/UX:** Custom Canvas Grid Layout, Executive Dark Mode, Synchronized Slicers, Page Navigation

---

## 🎨 Tableau Dashboard (Bonus)

### Overview
An additional interactive dashboard built in **Tableau Public** using the same Financial Sample dataset, showcasing Tableau-specific features and a different analytical perspective.

### 📊 Visualizations Built
- **KPI Banner:** Total Sales, Total Profit, Total Units Sold, Profit Margin % — displayed as summary cards
- **Product Portfolio Margin Analysis:** Color-coded heatmap showing Profit Margin % by Product × Segment (red = negative, green = positive)
- **Discount Strategy vs Revenue Impact:** Bubble/scatter chart analyzing how discount bands affect Gross Sales
- **Monthly Sales Trend:** Line chart showing Sales movement across 2013–2014
- **Segment Sales & Profitability:** Horizontal bar chart comparing Sales across all business segments

### ⚡ Interactive Features
- **Segment Filter:** Multi-select checkbox filter (All, Channel Partners, Enterprise, Government, Midmarket, Small Business)
- **Year of Date Filter:** Toggle between 2013, 2014, or both
- Both filters apply across all worksheets simultaneously

### 🛠️ Tech Stack
- **Tool:** Tableau Public (Free)
- **Data:** Microsoft Financial Sample (700 rows, 16 columns)
- **Theme:** Dark executive layout consistent with Power BI dashboard

---

## 📁 Repository Structure
├── TASK 4-Dashboard.pbix          → Power BI dashboard file
├── Financial Sales dataset.xlsx   → Raw dataset (Excel)
├── Financial Sales & Profitability Summary.pptx  → 5-slide PPT summary
├── Tableau/
│   ├── Financial_Sales_Analysis.twbx  → Tableau workbook file
│   └── dashboard_screenshot.png       → Tableau dashboard screenshot
└── README.md                      → Project documentation

