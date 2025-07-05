# Objective
Analyze coffee sales data and derive actionable insights on customer behavior, product performance, and sales trends by leveraging advanced Excel techniques. The goal was to transform raw order data into a dynamic, interactive dashboard that supports informed business decisions through clear visualizations and summarized metrics.

# Techniques and Implementation Details

1. XLOOKUP
	•	Used the XLOOKUP function to dynamically retrieve customer and product details from respective datasets.
	•	Linked the Customer ID from the orders table to the customer dataset to populate fields such as customer name, email, and country.

2. INDEX MATCH
	•	Applied the INDEX MATCH formula for advanced lookups that required more flexibility than XLOOKUP.
	•	For instance, retrieved unit prices based on multiple conditions like coffee type, size, and roast type.

3. Multiplication Formula for Sales
	•	Calculated total sales by multiplying quantity ordered with the unit price for each product.
	•	Used the formula: =Quantity * Unit Price to populate the sales column in the dataset.

4. Multiple IF Functions
	•	Used nested IF functions to classify orders into categories like “High Sales,” “Medium Sales,” and “Low Sales.”
	•	This provided a better understanding of order performance at a glance.

5. Date Formatting
	•	Standardized date formats across all datasets to enable consistent analysis and time-based filtering.
	•	Reformatted Order Date fields to a clear and uniform format.

6. Number Formatting
	•	Applied appropriate number formatting to ensure consistency in fields such as sales (currency) and quantities (integers).
	•	This made data presentation more professional and easier to read.

7. Check for Duplicates
	•	Checked for and removed duplicate entries to ensure the dataset was clean and accurate for analysis.
	•	This step prevented inaccuracies in metrics derived from the data.

8. Convert Range to Table
	•	Converted raw datasets into structured Excel tables to enable dynamic referencing and better management.
	•	This streamlined the use of formulas, filters, and pivot tables.

9. Pivot Tables and Pivot Charts
	•	Created pivot tables to summarize key metrics such as:
	•	Sales by country.
	•	Top-selling products.
	•	Customer order frequency.
	•	Designed pivot charts to visually represent these summaries for better insights.

10. Insert Timeline
	•	Added a timeline slicer to allow filtering of sales data by specific date ranges.
	•	Enabled dynamic interaction with pivot tables for time-based analysis.

11. Insert Slicers
	•	Implemented slicers for categories like customer, product, and country, allowing users to filter data dynamically.
	•	Applied custom formatting to improve usability and aesthetics.

12. Updating the Pivot Table Data Source
	•	Ensured pivot tables dynamically updated when new data was added by linking the data source to structured tables.

13. Building the Dashboard
	•	Created an interactive dashboard combining pivot charts, slicers, and timelines.
	•	Key metrics visualized include:
	•	Total sales by country.
	•	Top customers and products.
	•	Monthly and yearly sales trends.
	•	Designed the dashboard with consistent formatting and a user-friendly layout for clear communication of insights.


# Outcome:

This project effectively demonstrates the ability to organize, analyze, and visualize complex data sets. Using advanced Excel functions, pivot tables, and interactive dashboard elements, the analysis provides actionable insights for decision-making, showcasing proficiency in data analytics and business intelligence.
