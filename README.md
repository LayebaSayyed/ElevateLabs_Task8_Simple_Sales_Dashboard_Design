📊 TASK 8: Simple Sales Dashboard (Power BI)
🎯 Objective
Create a clean and interactive Sales Dashboard using Power BI to visualize sales performance by month, region, and category.
________________________________________
📁 Dataset
You may use:
•	Superstore_Sales.csv
o	Columns: Order Date, Region, Category, Sales, Profit
•	OR any similar sales dataset
________________________________________
🛠 Tools Used
•	Power BI Desktop
________________________________________
📌 Steps to Complete the Task
1. Import Data
Open Power BI → Get Data → Text/CSV → Load the dataset.
________________________________________
2. Data Preparation
•	Convert Order Date to Date format
•	Create a new calculated column for Month-Year using DAX:
MonthYear = FORMAT('Table'[Order Date], "MMM yyyy")
•	Sort MonthYear by Order Date so the trend displays correctly.
________________________________________
3. Build Visuals
A. Line Chart – Monthly Sales Trend
•	Axis: MonthYear
•	Values: Sales
•	Title: Monthly Sales Trend
B. Bar Chart – Sales by Region
•	Axis: Region
•	Values: Sales
•	Sort: Descending
•	Title: Sales by Region
C. Donut Chart – Sales by Category
•	Legend: Category
•	Values: Sales
•	Title: Sales Contribution by Category
D. KPI Cards
•	Total Sales
•	Total Profit
________________________________________
4. Add Interactivity
•	Add a slicer for Region or Category
•	Ensure visuals interact with each other for dynamic filtering.
________________________________________
5. Formatting & Layout
•	Apply a clean theme (Dark, Light, or Color Blind Safe)
•	Arrange visuals neatly:
o	Line chart at the top
o	Bar and Donut charts below
o	Slicers on one side
o	KPI cards on the right
•	Add proper titles and labels for clarity.
________________________________________
📄 Insights (Example)
1.	Sales show a steady decline after December 2017, indicating a drop in customer demand.
2.	Technology category contributes the highest share of overall sales (~36%).
3.	West region records the highest sales (approx. 0.73M), while South performs the lowest.
4.	The business generated 2.30M in total sales and 286.40K in profit, showing moderate profitability.
________________________________________
📤 Deliverables
✔ Power BI Dashboard Screenshot or PDF Export
✔ README.md (this file)
✔ 3–4 Key Insights
________________________________________
✅ Outcome
By completing this task, you will learn how to:
•	Import and clean data in Power BI
•	Build professional visualizations
•	Use slicers and interactions
•	Present insights visually for business users
________________________________________

