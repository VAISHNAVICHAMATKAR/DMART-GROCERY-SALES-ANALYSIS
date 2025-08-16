# 📊 DMart Grocery Sales Dashboard \| Power BI Project

## 🔗 Overview

This project presents an interactive **Power BI Dashboard** designed to
analyze and visualize **DMart's Grocery Sales** data. The dataset
comprises transactional-level information, which has been cleaned,
transformed, and visualized to derive insights on **sales**, **profit**,
**customer behavior**, **category performance**, and more.

## 📁 Files Included

-   `DMart_Grocery_Sales_-_Retail_Analytics_Dataset.csv` -- Original raw
    dataset.
-   `DMart Analysis.pbix` -- Power BI dashboard file.
-   `DMART DASHBOARD.png` -- Dashboard screenshot for quick preview.

## ⚙️ Data Cleaning & Transformation

Performed using Power Query in Power BI: - Cleaned null and blank values
in `Quantity`, `Discount`, and `Description`. - Converted incorrect date
formats (MM-DD-YYYY) using **locale settings**. - Created new calculated
columns and measures: - `Month-Year` -
`Total Sales = Quantity * Unit Price` - `Profit = Sales - Cost` -
`Profit Margin = DIVIDE(Profit, Sales)`

## 📌 Key Metrics

-   **Total Sales:** \$6.05M\
-   **Total Orders:** 4042\
-   **Total Profit:** \$1.50M\
-   **Profit Margin:** 25%

## 📊 Visualizations Used

  --------------------------------------------------------------------------
  Visualization         Purpose
  --------------------- ----------------------------------------------------
  **Card** Visuals      Display key KPIs like Sales, Profit, Orders

  **Bar Chart**         Top 5 Sub-categories, Top 10 Cities, Top Customers

  **Donut Chart**       Sales by Category

  **Tree Map**          Sales by Year

  **Clustered Bar       Sales by Region, Sales by Month
  Chart**               

  **Slicers/Filters**   City, Region, Category, Sub-Category -- to make the
                        dashboard interactive
  --------------------------------------------------------------------------

## 🎨 Design & Styling

-   **Theme:** Dark with shades of green (DMart brand colors).
-   **Fonts Used:** Segoe UI / Calibri for readability and alignment
    with Power BI defaults.
-   **Layout:** 16:9 Canvas \| Organized grid layout using horizontal
    and vertical sections.

## 🔍 Insights Gained

-   The **East region** generates the highest revenue.
-   **Soft Drinks** and **Health Drinks** are the top-selling
    sub-categories.
-   **August to November** are peak sales months.
-   Profit margins are consistent across the year with seasonal spikes.

## 📈 Tools & Skills Demonstrated

-   Power BI (Power Query, DAX, Measures, Slicers)
-   Data Cleaning & Transformation
-   KPI Analysis & Dashboarding
-   Data Visualization & Storytelling

## 📬 Contact

**Vaishnavi Chamatkar**\
📧 vaishnavichamatkar@gmail.com\
🔗 [LinkedIn Profile](#)\
📍 Maharashtra, India
