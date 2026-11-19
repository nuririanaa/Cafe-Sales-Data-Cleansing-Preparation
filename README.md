# Cafe-Sales-Data-Cleansing-Preparation
End-to-end data cleansing and preparation of a messy 10,000-row cafe sales dataset using Python (Pandas). Covers handling missing values, fixing schema typos, standardizing dates/text, and validating transaction calculations.
# Project Overview 
This project covers Data Cleansing and Data Preparation using Python (Pandas) on a messy 10,000-row cafe sales dataset. By resolving missing values, schema typos, and formatting inconsistencies, it produces reliable data ready to power a sales dashboard
# Dataset & Issues Handled
Initial Rows: 10,000 transactions

Key Data Issues:
 - Column Typo: Misspelled date column (Transcation Date).
 - Missing Values: Blank values (NaN) across Item, Quantity, Price Per Unit, Total Spent, Payment Method, and Location.
 - Corrupt Dates: Date fields stored as strings with missing or invalid timestamp values (NaT).
 - Text Inconsistencies: Leading/trailing whitespaces and mixed casing in categorical columns.
# Step Analysis 
 - Load Data: Load raw data (10,000 rows, 8 columns) in Pandas and inspect structure.
 - Data Cleaning: Fix column typo, handle missing values & invalid dates (NaT), standardize text, and export cafe_sales_cleaned.csv.
 - Analysis & Aggregation: Aggregate key metrics (Customer, Revenue, Order, AOV), top items (Juice), location, payment method, and trends.
 - Dashboard (Looker Studio): Visualize cleaned data in Sales & Analytic Overview.
 - Conclusion: Summarize key insights, Unknown share, and next steps
# Dashboard
<img width="1366" height="768" alt="2026-11-19 (2)" src="https://github.com/user-attachments/assets/c3521031-f8d4-4eb2-9000-1b73020e60de" />
Explore the interactive visualization on **Looker Studio**:  
👉 [[Open Sales & Analytic Overview Dashboard]](https://datastudio.google.com/reporting/e95adc4e-e559-494b-ab00-38fa87dd7f1f)
