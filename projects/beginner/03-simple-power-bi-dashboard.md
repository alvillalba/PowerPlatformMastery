# Project 3: Simple Power BI Dashboard

## 📋 Overview

Create a Power BI dashboard from Excel data to visualize sales information. This project covers Power BI Desktop, data import, visualization creation, and dashboard publishing.

## 🎯 Learning Objectives

- Import data from Excel
- Create visualizations (charts, tables)
- Build a dashboard
- Publish to Power BI Service
- Share dashboards

## 📚 Prerequisites

- Power BI Desktop (free download)
- Power BI account (free)
- Excel file with sample data

## 🛠️ Step-by-Step Instructions

### Step 1: Prepare Sample Data

1. Create an Excel file named "SalesData.xlsx"
2. Create a sheet with columns:
   - **Date** (Date)
   - **Product** (Text: Product A, Product B, Product C)
   - **Region** (Text: North, South, East, West)
   - **Sales** (Number)
   - **Quantity** (Number)
3. Add 20-30 rows of sample data

### Step 2: Import Data to Power BI Desktop

1. Open **Power BI Desktop**
2. Click **Get Data** → **Excel**
3. Browse and select "SalesData.xlsx"
4. Select your sheet
5. Click **Load**

### Step 3: Create Visualizations

#### Visualization 1: Sales by Region (Bar Chart)

1. Click on **Bar chart** icon
2. Drag **Region** to **Axis**
3. Drag **Sales** to **Values**
4. Format: Add title "Sales by Region"

#### Visualization 2: Sales Trend (Line Chart)

1. Click on **Line chart** icon
2. Drag **Date** to **Axis**
3. Drag **Sales** to **Values**
4. Format: Add title "Sales Trend Over Time"

#### Visualization 3: Product Performance (Pie Chart)

1. Click on **Pie chart** icon
2. Drag **Product** to **Legend**
3. Drag **Sales** to **Values**
4. Format: Add title "Sales by Product"

#### Visualization 4: Sales Table

1. Click on **Table** icon
2. Add fields: **Date**, **Product**, **Region**, **Sales**, **Quantity**
3. Format table appearance

### Step 4: Create Calculated Column

1. Right-click on your table → **New column**
2. Name: `SalesPerUnit`
3. Formula: `SalesPerUnit = Sales[Sales] / Sales[Quantity]`
4. Format as currency

### Step 5: Add Slicers

1. Click **Slicer** icon
2. Add **Region** slicer
3. Add **Product** slicer
4. Test filtering across all visualizations

### Step 6: Format Report

1. Click **View** → **Page View** → **Fit to page**
2. Arrange visualizations nicely
3. Add report title: "Sales Dashboard"
4. Format colors and fonts

### Step 7: Publish to Power BI Service

1. Click **Home** → **Publish**
2. Sign in to Power BI account
3. Select workspace (My workspace)
4. Click **Select**
5. Wait for upload to complete

### Step 8: Create Dashboard

1. Go to [Power BI Service](https://app.powerbi.com)
2. Navigate to your workspace
3. Open your report
4. Click **Pin to dashboard** on visualizations
5. Create new dashboard: "Sales Overview"
6. Pin selected visuals

### Step 9: Share Dashboard

1. Open your dashboard
2. Click **Share**
3. Enter email addresses
4. Set permissions (View or Edit)
5. Add message (optional)
6. Click **Share**

## ✅ Success Criteria

- [ ] Data imported successfully
- [ ] At least 4 visualizations created
- [ ] Slicers work and filter data
- [ ] Report published to Power BI Service
- [ ] Dashboard created and shared

## 🔗 Related Resources

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- [Getting Started with Power BI](https://learn.microsoft.com/power-bi/fundamentals/desktop-getting-started)
- [Visualization Types](https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-types-for-reports-and-dashboards)

## 💡 Next Steps

- Add more data sources
- Create calculated measures
- Add drill-through pages
- Set up scheduled data refresh
- Create mobile-optimized layout

---

**Estimated Time**: 2-3 hours  
**Difficulty**: ⭐⭐ (Beginner)

