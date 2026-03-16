HR Analytics Dashboard (Excel + Power BI)

Project Overview

This project focuses on cleaning and analyzing a messy employee dataset and building an interactive HR analytics dashboard using Excel and Power BI.
The goal was to transform raw data into meaningful insights about workforce distribution, salary trends, employee performance, and work patterns.

Tools Used

•Microsoft Excel – Data cleaning and preprocessing
•Power BI – Data modeling, visualization, and dashboard creation

Data Pre-processing (Excel)

The raw dataset was cleaned and transformed using Excel before loading it into Power BI.

Key steps included:

•Validated dataset for duplicate records using Employee_ID
•Handled missing values using median imputation:
  °Age
  °Salary
•Converted Join_Date from text format to a standardized date format
•Standardized categorical values such as Status
•Split Department_Region into separate Department and Region columns
•Corrected data types for numeric and date fields
•Created derived columns:
  °Full_Name (First_Name + Last_Name)
  °Experience_Years
•Used filtering and sorting for validation
•Created Pivot Tables for preliminary analysis

Power BI Dashboard

A multi-page interactive dashboard was built in Power BI to analyze the workforce.

Page 1 – HR Overview

Provides a quick summary of the workforce.

Visuals include:

•KPI Cards (Total Employees, Active Employees, Average Salary, Average Experience)
•Department summary table
•Region distribution (Treemap)
•Employee status distribution (Donut chart)

Page 2 – Salary & Performance

Focuses on compensation and performance insights.

Visuals include:

•Average Salary by Department
•Salary Distribution
•Performance Score Distribution

Page 3 – Workforce Analysis

Analyzes work patterns and experience distribution.

Visuals include:

•Remote vs Onsite workforce
•Remote employees by region
•Average experience by department
•Experience distribution

Key Insights

Some insights obtained from the dashboard include:

•Workforce distribution varies significantly across departments and regions
•Salary generally increases with experience but stabilizes after a certain point
•Remote work adoption differs across regions
•Some departments have higher average experience levels compared to others

Learning Outcomes

Through this project I learned how to:

•Clean and preprocess messy datasets
•Handle missing values and inconsistent formats
•Create calculated fields and derived metrics
•Design interactive dashboards in Power BI
•Use appropriate visualizations to communicate insights effectively

Future Improvements

Potential enhancements for this project:

•Introduce time-based trend analysis
•Integrate additional HR metrics such as attrition rate

Author

Arjun K U
