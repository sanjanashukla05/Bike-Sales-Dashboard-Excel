Bike Sales Dashboard Excel-Dashboard

A data analysis and visualization project built using Microsoft Excel to understand customer bike purchasing behavior.
This project focuses on data cleaning, transformation, analysis, and interactive dashboard creation using pivot tables and slicers.
The final output is an interactive Excel dashboard that helps visualize how factors like income, age, commute distance, and demographics affect bike purchases.
---
# Project Objective
•	Clean raw sales data and make it analysis-ready
•	Analyze customer trends related to bike purchases
•	Build an interactive dashboard using Excel pivot tables and charts
# Data Cleaning Process
Before creating the dashboard, the dataset was carefully reviewed and cleaned to make it suitable for analysis.

• A working sheet was created as a copy of the raw data 
• Duplicate records were identified and removed  
• Marital status values were cleaned and converted from:
      - M → Married
      - S → Single  
• Gender values were converted from:
      - M → Male  
      - F → Female 
• Income values were formatted as currency for better readability  
---
# Age Bracket Column
The age column had a wide range (23 to 89), which made analysis difficult.  
To make it easier to interpret, a new Age Bracket column was created using nested IF formulas:
• Adolescent 
• Middle Age 
• Old  
This grouping helped in better comparison and clearer visualizations.
---
# Dashboard Creation
Created multiple Pivot Tables from the cleaned data to analyze trends:  
• Average income vs bike purchase  
• Commute distance vs purchase behavior  
• Age group trends  
Converted pivot tables into charts and combined all charts into a single dashboard sheet.  
• Removed gridlines to improve appearance  
• Added Slicers to enable interactive filtering across multiple charts
---
## Key Dashboard Insights
• Customers who purchased bikes generally have higher average income  
• Middle-aged customers purchased bikes more compared to other age groups  
• Customers with shorter commute distances are more likely to buy bikes  
• Factors like gender, marital status, education, and occupation influence buying decisions
---
## Tools & Techniques Used
• Microsoft Excel  
• Data Cleaning & Transformation  
• Pivot Tables & Pivot Charts  
• Nested IF formulas  
• Slicers for interactivity---
# Dashboard Preview
Dashboard image is attached with the project files.
---
## How to Use
• Download the Excel file from this repository  
• Enable editing and content  
• Use slicers to filter data  
• Explore trends and insights interactively  
---
#Note
This project was created as part of my data analytics learning journey to strengthen my Excel and data analysis skills.
