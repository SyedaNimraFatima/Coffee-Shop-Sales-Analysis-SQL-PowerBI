# Coffee-Shop-Sales-Analysis-SQL-PowerBI
This project showcases a fully interactive and dynamic **Power BI dashboard** developed to perform sales analysis for a fictional chain of coffee shops operating across New York City. The report provides comprehensive insights into sales performance, customer purchasing behavior, and product demand — aimed at empowering business stakeholders to make data-driven decisions quickly and confidently.

---
## Project Overview
This analysis is created by **Syeda Nimra Fatima** as a portfolio project to demonstrate proficiency in **Power BI**, data cleaning, DAX measures, and storytelling through visual analytics.
The report answers key business questions such as:
- Which product categories and store locations are generating the most revenue?
- What are the weekly and hourly sales patterns?
- How do weekends compare to weekdays in terms of performance?
- What items are the top sellers, and when do they peak?

---
## Business Objectives
- **Monitor** total sales, orders, and quantities sold over time  
- **Compare** performance across multiple store locations  
- **Understand** temporal sales patterns by week, weekday, and hour  
- **Identify** top-performing product categories and items  
- **Analyze** month-over-month and day-part performance (AM vs PM)  
- **Spot** declining or underperforming segments for improvement  

---
## Tools & Techniques
- **Power BI Desktop** for interactive visualizations and KPIs
- **Microsoft Excel** for data preprocessing
- **Data Modeling** using star schema and relationships
- **DAX Measures** for time intelligence, KPIs, and custom calculations
- **Custom visuals** (stacked bar, clustered column, cards, etc.)

---
## Dashboard Highlights  
| Metric             | Value        |  
|--------------------|--------------|  
| Total Sales      | **$698,812**  |  
| Total Orders     | **149,116**   |  
| Quantity Sold    | **214,470**   |  

### Performance Insights  
This report includes multiple **custom visual objects** and layout elements built from scratch to ensure maximum clarity, performance benchmarking, and storytelling. Below are the key visual components included:
- **KPI Cards**: Display Total Sales, Total Orders, and Quantity Sold along with percentage and absolute difference vs the previous month. Sparkline visuals are embedded to show trend fluctuations.
- **Sales by Product Category**: A horizontal bar chart categorizing all sales into core segments like Coffee, Tea, Bakery, etc. Custom color-coding and dynamic tooltips are used for performance comparison and drill-ins.
- **Top 7 Selling Items**: A ranked bar chart that shows top-performing individual product types based on total sales. Includes dynamic data labels and delta indicators for performance change.
- **Sales by Store Location**: A custom bar chart comparing revenue from three store locations — Astoria, Hell’s Kitchen, and Lower Manhattan — with variance indicators for monthly comparison.
- **Sales by Weekend/Weekday**: A donut chart clearly shows how sales are distributed between weekdays and weekends. Labels, inner text, and comparative values are customized for clarity.
- **Hour-Wise Sales Heatmap**: A matrix heatmap visual representing hourly sales across all days of the week. Color gradients highlight peak sales hours (e.g., 9–11 AM), offering valuable day-part insights.
- **Sales Trend Over Period**: A vertical column chart showing daily sales trends for February 2023, with a reference line marking the average sales level ($2,719). Hover tooltips provide precise day-wise values.
- **Calendar Layout**: A stylized week-based date grid for February 2023 enables intuitive navigation and temporal understanding of the report's date scope.
- **Month Filter Panel**: Clickable slicers allow users to switch across months (Jan–Jun), enabling interactivity and future expansion with real-time filters.
Each of these objects is fully customized with:
- Visual level and page level filters
- Advanced formatting options (tooltips, labels, interactions)
- Color consistency aligned to brand theme
- Custom measures using DAX for prior month comparison and running totals
This level of customization ensures that the report is not only visually appealing but also highly functional for business intelligence use cases.

---
## Dataset Scope
- Date Range: **January – February 2023**
- Data Dimensions:
  - Product Category & Product Type
  - Store Location
  - Date, Week, Month, and Hour
- Source File: `Coffee Shop Sales.xlsx`

---
## Files in this Repository
| File                             | Description                                |
|----------------------------------|--------------------------------------------|
| `Coffee Shop Sales.xlsx`         | Raw dataset used for the Power BI model     |
| `Coffee_Shop_Sales_Analysis.pdf` | PDF export of the interactive dashboard     |
| `MANHATTAN.png`                  | Store map/graphic used in presentation      |
| `README.md`                      | Project documentation and explanation       |

---
## Possible Future Enhancements
- Add **predictive models** using Python or R integration
- Include **geospatial mapping** with ArcGIS or filled maps
- Add **customer segmentation** and RFM analysis
- Enable **live data refresh** using Power BI Service + SQL
