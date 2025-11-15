# Superstore Sales Dashboard - Power BI
## Project OverView
This project is a part of a Data Analyst Internship Task focused on **Data Visualization & Storytelling**.
Using Power BI, I created on interactive dashboard to analyze Superstore sales performance across states, categories, and time.

## Data Cleaning & Preparation
- Loaded the **Superstore dataset** into **Power BI**
- Used **Power Query** for initial cleaning:
 -Verified correct data types
 -Removed unnecessary columns
 -Ensuredd *Order Date* was in proper Date format
 -Checked for null or missing values
  
- Created new data columns using **DAX**:
 - **MonthName** = FORMAT([Order Date],"MMM")
 - **MonthNumber** = MONTH([Order Date])
 - **Year** = YEAR([Order Date])
 - **Avg Order Value** = [Sales]/[Total Orders]
These fields were later used for slicer and time-series visuals.

## Dashboard Features
### KPIs (Top cards)
- Total Sales
- Total Profit
- Total Quantity
- Average Order Value

### Visualizations
- **Sales by Month** (Line Chart)
- **Sales by Category** (Bar Chart)
- **Profit by Sub-Category** (Horizontal Bar Chart)
- **Sales by State** (Map or Alternative Chart)
- **Sales by Year** (Column Chart)

### Slicers Added
- Year  
- Month Number  
- Category  
- State  

## Insights
- Identified top-performing and low-performing product categories  
- Analyzed profit distribution by sub-category  
- Observed monthly and yearly sales trends  
- Compared regional sales using geographic data  

---

##  Files in This Repository
- 'Superstore dashboard.pdf' → Exported Power BI dashboard  
- 'dataset.csv' → Superstore dataset used  
- 'README.md' → Project explanation  
- Screenshot folder (optional)

## Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**

## Conclusion
This Superstore Sales Dashboard project demonstrates my ability to transform raw data into actionable insights using Power BI.
It highlights skills in data cleaning, modeling, visualization, and storytelling, making it a strong example for internship applications or showcasing in a portfolio.

## Summary
This project covers the complete workflow of data analysis using Power BI, from data cleaning to interactive dashboard creation.
Key highlights include:
Transforming raw data into actionable business insights
Building KPIs and meaningful visualizations
Using DAX for calculated columns and measures
Enabling interactive analysis with slicers
The dashboard effectively supports business decision-making and showcases skills suitable for internship or job applications.
