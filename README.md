# Acadia_Assignment
Project of python and data_viz
This project is a Python-based tool that generates a detailed report on a given dataset. The report includes various analyses and visualizations, such as missing value checks, data categorization, handling of duplicates and constant columns, box plots for numeric columns, and distribution plots for random columns. The generated report is exported in multiple formats: HTML, PDF, and Word.

Features
Missing Values Detection: Identifies columns with missing values and lists them.
Data Type Categorization: Categorizes columns based on their data types (numeric and categorical).
Duplicate Columns Removal: Detects and removes duplicate columns, providing before and after states.
Constant Columns Removal: Identifies and removes constant columns (columns with the same value in all rows).
Box Plots: Generates box plots for numeric columns to visualize outliers.
Distribution Plots: Creates distribution plots for 6 randomly selected columns to visualize the data distribution.
Export to PDF and Word: Exports the generated report to both PDF and Word formats.
Requirements
To run this project, you need to have the following Python packages installed:

pandas
matplotlib
seaborn
fpdf
docx
