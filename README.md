Data Preparation Overview
Before performing any meaningful analysis, it was essential to clean and structure the raw loan repayment dataset. The original data contained datetime fields that were not formatted consistently and could not be used directly for temporal analysis.

To address this, several preprocessing steps were carried out using SQL to transform and organize the data in a more analytical-friendly format. These included:

Extracting and separating the date_time field into two components: Date and Time.

Formatting the rep_month column to follow the standard YYYY-MM date format, making it suitable for time-based grouping and reporting.

Removing redundant or no longer needed columns such as date_time to streamline the dataset.

These foundational changes were critical to ensuring data consistency, simplifying future analysis, and enabling accurate trend visualizations in the next phases of the project.

# BankLoan-SQL-Cleaning
