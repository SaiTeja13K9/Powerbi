# Power BI Sales Dashboard - Portfolio Project

This project is a comprehensive end-to-end Power BI portfolio project for a fictional company called The Chocolatee Factory, focusing on advanced data modeling, KPI development, and dashboard design using a rich chocolate-themed dataset. It follows the full life cycle from data modeling to GitHub publication.

## 🔍 Project Overview

This dashboard delivers business insights across key performance indicators like:

- Total Sales
- Total Costs
- Total Profit & Profit %
- Total Boxes Shipped
- Total Shipments
- Low Box Shipments & %

The dashboard includes dynamic MoM change tracking, conditional formatting, tooltips, bookmarks, field parameters, and interactive drilldowns for both product and salesperson views.

## 📁 Dataset Details

**Fact Table:** Shipments

**Dimensions:**

- Salesperson
- Product (with Cost per Box)
- Geography
- Calendar

## ⚙️ Features Implemented

- Star Schema Data Modeling in Power BI
- DAX Measures for:
  - KPIs (Sales, Profit, Cost, etc.)
  - MoM % change using time intelligence
  - Low box shipment calculations (< 50 boxes)
- Advanced Card Visuals (with icons, reference labels, conditional formatting)
- Slicers for product categories & geographies
- Drilldowns with bookmarks (Salesperson vs Product details)
- Trend Analysis with Field Parameters
- Conditional Icons & Data Bars in Tables
- Custom Layout using PowerPoint Wireframing

## 📊 Dashboard Layout

- **Top Bar:** KPI Cards with icons and MoM changes
- **Left Side:** Logo + Filters (Product Category, Geography)
- **Main Section:**
  - Line chart with field parameter (switch between KPIs)
  - Gauge visual for Profit % and Low Box %
  - Histogram for shipment sizes
  - Dynamic table for Salesperson/Product details

## 🧠 Learning Outcomes

- Full-cycle Power BI dashboard creation
- Writing clean and modular DAX code
- Building dynamic interactivity with bookmarks and parameters
- Formatting for executive-level reporting

![image](https://github.com/user-attachments/assets/81b20547-68f7-4d01-badb-b8f51e28e6c3)

![image](https://github.com/user-attachments/assets/3511f8ba-da55-49e3-940f-4d2d211b405d)


## 🧾 Requirements

- Power BI Desktop
- Sample Excel Dataset (provided in video description)

## 📌 How to Use

1. Download the PBIX file from the repo.
2. Replace the Excel dataset if needed.
3. Explore KPI cards, slicers, and toggle bookmarks.
4. Review DAX measures in the _Measures table.
