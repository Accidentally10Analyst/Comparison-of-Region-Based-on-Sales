# Comparison-of-Region-Based-on-Sales
This project aims to compare sales performance between two selected regions using the Sample Superstore dataset in Tableau. An interactive Tableau dashboard comparing sales between two selected regions using KPIs, maps, bar and line graphs to help upper management identify performance gaps and suggest improvements.
# 📊 Comparison of Region Based on Sales

This Tableau project helps the director of a leading organization compare sales performance between two selected regions using a dynamic and interactive dashboard.

## 📌 Objective
Create a dashboard to:
- Compare two regions (Primary & Secondary) using parameters.
- Analyze sales performance with key KPIs and visual insights.
- Suggest improvements based on data patterns.

## 📂 Dataset
- **Name:** Sample Superstore
- **Tool Used:** Tableau
- **Data Source:** Orders Sheet

---

## 🛠️ Steps Performed

### 📥 1. Data Preparation
- Imported `Sample Superstore` dataset into Tableau.
- Created a **folder** in the data source to group `Customer Name` and `Order ID`.
- Built a **Location hierarchy** using the `Country` dimension.

### 🎛️ 2. Parameters & Calculated Fields
- Created two parameters:
  - **Primary Region**
  - **Secondary Region**
- Built calculated fields to reflect selected region values.
- Created `First Order Date` using a calculated field.

### 📈 3. KPI Metrics for Each Region
- First Order Date
- Total Sales
- Average Sales per Order
- Number of Customers
- Number of Orders
- Number of Products Sold

### 📊 4. Visualizations
- **Line Graph:** Order Date (weekly) vs. Sales (Sub-Category).
- **Bar Graph:** Sales vs. Sub-Category.
- **Map:** Region-wise Sales using Location hierarchy.
- **Text Tables:** KPIs displayed for each region.

### 🧩 5. Dashboard Creation
- Aligned all sheets in a structured layout.
- Used floating elements as needed.
- Applied filters for Order Date (Year) and selected regions.

---

## 📌 Output Highlights

- **Interactive Selection**: Choose any two regions dynamically using dropdowns.
- **Side-by-Side Comparison**: See KPIs and trends for each region.
- **Actionable Insights**: Identify strong and weak sub-categories.
- **Visualization Types**: Text KPIs, Bar Charts, Line Graphs, and Maps.

---

## ✅ Tools & Features Used

- Tableau Parameters & Calculated Fields
- Custom Hierarchies
- Filtering & Grouping
- Line and Bar Charts
- Dashboard Interactivity

---

## 📁 File Structure (if applicable)
