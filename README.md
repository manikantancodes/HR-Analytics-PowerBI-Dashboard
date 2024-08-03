# HR Analytics Dashboard

## Objective
The objective of this project is to identify the key factors driving employee turnover and provide actionable insights for improving workforce retention in an organization. This dashboard helps the HR team with their analysis by visualizing the turnover of an organization and other related metrics.

## Project Overview
This Power BI dashboard provides a comprehensive analysis of employee turnover and associated factors. The dashboard offers insights into various HR metrics, allowing stakeholders to make data-driven decisions for enhancing employee retention.

## Key Features
- **Total Workforce**: Displays the total number of employees in the organization.
- **Employee Turnover**: Shows the total number of employees who have left the organization.
- **Turnover Percentage**: Represents the turnover rate as a percentage of the total workforce.
- **Current Employees**: Indicates the number of active employees remaining in the organization.
- **Average Age**: Provides the average age of employees in the organization.
- **Turnover by Department**: A pie chart displaying the distribution of turnover across different departments (R&D, Sales, HR).
- **Employee Age Demographics**: A stacked column chart showing the distribution of employees by age group and gender.
- **Employee Satisfaction Scores**: A matrix visual displaying satisfaction scores across various job roles.
- **Turnover by Education**: A bar chart illustrating the turnover rates across different education fields.
- **Turnover Rates by Gender and Age**: A set of donut charts showing the turnover rates for different gender and age groups.

## Steps Followed

### 1. Data Gathering
- Imported raw data from a CSV file into Power BI and transformed it using Power Query Editor for cleaning and processing.

### 2. Data Cleaning
- Removed empty columns, duplicates, and errors.
- Replaced values and renamed columns for clarity.
- Detected and corrected data types for each column.

### 3. Data Processing
- Created a new column called "TurnoverCount" using the conditional column feature based on turnover status.
- Calculated turnover rates using DAX queries.
- Developed various KPIs and charts to visualize key metrics.

### 4. Data Analysis
- Analyzed the data using a variety of visualizations, including pie charts, bar charts, KPIs, matrix tables, and donut charts.
- Answered key business questions regarding employee demographics, turnover, and satisfaction.

## Learned Concepts
- **Calculated Fields**: Used to calculate metrics like Turnover Rate and Current Employees.
- **Matrix Table**: Used to present job satisfaction ratings.
- **Donut Chart and Pie Chart**: Visualized turnover distribution.
- **Bar Chart and Clustered Column Chart**: Showed demographic and department-specific data.
- **KPI and Slicer**: Enabled interactive filtering and data exploration.
- **Conditional Formatting**: Applied a color gradient to satisfaction scores for quick visual insights.

## Key Insights Summary
- **Total Workforce**: The organization has 1470 employees.
- **Employee Turnover**: 237 employees have left, with 150 males and 87 females.
- **Departmental Turnover**: The Research and Development Department has the highest turnover at 56%.
- **Turnover by Education**: Life Sciences field has the highest turnover.
- **Job Role Turnover**: Sales roles are experiencing the highest turnover.
- **Turnover by Gender and Age**: Employees aged 25-34 have the highest turnover count at 112.

## How to Use
Clone this repository and open the Power BI file to explore the dashboard. The interactive features allow you to filter data by various fields, providing a customizable analysis experience.

## Conclusion
This HR Analytics Dashboard serves as a powerful tool for organizations to monitor and address employee turnover, leading to more informed HR strategies and improved retention efforts.
