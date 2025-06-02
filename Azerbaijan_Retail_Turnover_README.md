
# Azerbaijan Retail Turnover Analysis

This Power BI project explores the evolution of Azerbaijan's **retail trade**, **paid services**, and **catering** sectors from a **time-series perspective**, with additional insights into **market share** and **annual turnover indexes**. The dataset is structured with a Calendar table and supports interactive filtering for custom analysis.

---

## 📊 Report Pages

### 🔹 1. Main

Provides a clean interface to navigate to the report's analytical pages:

- **Go to Overview**
- **Go to Trends**
- **Go to Structure & Share**
- **Go to Indexes**

---

### 🔹 2. Overview

An executive-level summary of retail turnover components by year.

#### Visuals:

- **Retail vs Paid Services vs Catering (Column Chart)**

  - X-axis: Year
  - Y-axis: Volume in million AZN for each sector
  - Displays overall volume dynamics

- **Consumer Market Breakdown (Donut Chart)**

  - Shows the proportional share of each sector in the consumer market

- **Total Turnover Trend (Line Chart)**

  - Tracks the overall consumer market volume across years

---

### 🔹 3. Trends

Highlights **annual turnover trends** by sector.

#### Visuals:

- **Retail Trade Trend (Line Chart)**

  - Y-axis: Retail_Trade_Volume_Mln

- **Paid Services & Catering Trends (Line Chart)**

  - Y-axis: Paid_Services_Volume_Mln and Catering_Volume_Mln

- **Date Slicer** (Calendar Table)

- **Navigation Buttons**: Go to Overview / Go to Structure & Share

---

### 🔹 4. Structure & Share

Focuses on the **sectoral share** of retail, paid services, and catering within the consumer market.

#### Visuals:

- **Service Share (%) Over Time (Line Chart)**

  - Shows year-over-year share percentage for each sector

- **Service Share (%) Over Time (Stacked Area Chart)**

  - Emphasizes cumulative sector share visually

- **Date Slicer** (Calendar Table)

- **Navigation Buttons**: Go to Trends / Go to Indexes

---

### 🔹 5. Indexes

Analyzes how turnover **indexes** have changed relative to the previous year.

#### Visuals:

- **Indexes Compared to Previous Year (Line Chart)**

  - Retail, Catering, Paid Services Index (% change)

- **Min/Max Index by Sector (Clustered Bar Chart)**

  - Highlights best and worst performing years per sector

- **Date Slicer** (Calendar Table)

- **Navigation Buttons**: Go to Structure & Share / Go to Main

---

## 🗂️ Data Model Summary

- `Retail_Services_Volume`: Turnover volumes in million AZN
- `Retail_Services_Share`: Market share (%) per sector
- `Retail_Services_Indexes`: Index values comparing year-over-year change
- `Calendar`: Includes Year, Date, Month, MonthNumber, Quarter
- `Sectors`: Used in min/max index comparison

---

Prepared by: *Your Name*
Date: 2025
Repository: `Azerbaijan_Retail_Turnover_Analysis`
