# Pizza Sales Insights & Analysis Dashboard 🍕📊

An interactive Microsoft Excel Data Analytics portfolio project tracking performance, sales trends, pricing behaviors, and customer preferences for a pizza restaurant dataset. 

The original raw dataset was obtained from [Kaggle](https://www.kaggle.com), preprocessed to ensure data integrity, analyzed utilizing Excel Pivot Tables, and visualized through a dynamic, user-friendly Executive Dashboard.

## 📌 Project Objectives
The primary purpose of this analysis is to evaluate key operational metrics and answer fundamental business questions:
* What is the total revenue, total order volume, and average ticket size?
* Which pizza categories and specific pizza types dominate sales?
* How do sales fluctuate across different months of the year?
* Does pricing distribution structurally impact total sales quantities?

---

## 🛠️ Data Pipeline & Preparation
Data cleaning and transformations were implemented inside the `pizza_sales` source worksheet to transition raw inputs into an analysis-ready structure:
1. **Deduplication & Missing Values:** Screened records to remove duplicate entries and validated data fields to handle blank spaces or null fields.
2. **Standardization & Text Cleaning:** Standardized spelling variations, string formats, text capitalization (such as pizza categories, names, and sizes), and normalized date formats.
3. **Analysis-Ready Formatting:** Configured proper financial currency indicators for prices, integer groupings for ordered quantities, and established clean calculated helper columns where required.

---

## 📈 Key Performance Indicators (KPIs)
Based on the dashboard summary, the business achieved the following results over the analyzed timeline:
* **Total Revenue:** `$881,654`
* **Total Quantity Sold:** `48,620 Pcs`
* **Total Orders:** `21,350`
* **Average Order Value:** `$41.3`
* **Top Performing Pizza:** `The Classic Deluxe Pizza` (`2,416 Pcs`)
* **Top Performing Category:** `Classic` (`$283,447` total value)

---

## 📊 Dashboard Modules & Insights

The dynamic layout is powered entirely by synchronized **Pivot Tables** and interactive **Slicers** for `Order Date` (Monthly timeline selection), `Pizza Category`, and `Pizza Name`.

### 1. Price Analysis (Combo Chart)
* Evaluates unit prices (`Count of quantity`) against the total revenue generated (`Sum of total_price`). 
* Helps pinpoint optimal price thresholds and identify high-revenue premium items.

### 2. Sales & Quantity by Pizza Category (Pie Chart & Treemap)
* **Classic** represents the largest market share (`32%`), closely followed by **Chicken** (`24%`), **Supreme** (`22%`), and **Veggie** (`22%`).
* It highlights that traditional flavors continue to drive core business volume.

### 3. Time Analysis (Line Chart)
* Tracks overall revenue variations month-by-month.
* Shows peak revenue spikes occurring around **May** and **July**, indicating seasonal demand surges where marketing campaigns can be strategically amplified.

### 4. Top 10 Best-Selling Pizzas (Horizontal Bar Chart)
* Visualizes the definitive top-ten menu list based on volume metrics.
* `The Classic Deluxe Pizza`, `The Barbecue Chicken Pizza`, and `The Hawaiian Pizza` rank as the top three pillars of customer demand.

---

## 📂 Repository Structure
* **`Dashboard Pivot 2.xlsx`**: The primary working workbook containing clean data tables (`pizza_sales`), intermediate analytical aggregations (`Sales Total`, `Trend`, `Terlaris`, `sales per category`, `Price Analysis`), and the interactive control dashboard interface (`Sheet1`).
* **`Pizza sales dashboard.jpg`**: A high-resolution layout preview image showcasing the complete interface design, charts, KPI cards, and interactive slicers.

---

## 🚀 How to Explore the Dashboard
1. Download or clone this repository to your local system.
2. Open `Dashboard Pivot 2.xlsx` using Microsoft Excel (Excel 2016 or newer recommended for optimal slicer and chart compatibility).
3. Interact with the **Order Date**, **Pizza Category**, and **Pizza Name** filter panes on the left and right margins to see how cross-filtered metrics re-render automatically.

---
*Developed by [Siti Habibah](https://github.com/sitihabibah/) as part of a Data Analytics Portfolio.*
