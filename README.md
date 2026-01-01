# SolveWithPowerBI — Challenge #1: Load and Clean Data in Power BI
## Welcome to the first challenge of SolveWithPowerBI 🎉
This challenge focuses on the most important Power BI skill: preparing messy data for analysis using Power Query.

Before dashboards, visuals, or DAX—data quality comes first.

---

# Challenge Goal

Learn how to:
Load Excel data into Power BI
Clean and transform raw data using Power Query
Fix column names and data types
Remove empty rows
Handle missing values safely

By the end, you’ll have a dataset that’s ready for reporting.

---

# Business Scenario

You’ve received a sales export from a colleague.
The data comes from multiple systems and hasn’t been cleaned.

Before you can analyze sales or build dashboards, you must prepare the data correctly.

This is a realistic first step in almost every Power BI project.

---

# Dataset

File: sales_raw.xlsx
Sheet: SalesData

## Intentional Data Issues

Inconsistent region names (us, US, eu, Eu, apac)
Sales values stored as text with $ and €
Blank and null values in Quantity
Trailing spaces in column headers
Completely empty rows

---

# Requirements

Power BI Desktop (latest version recommended)

---

# Your Task

Using Power BI Desktop and Power Query, clean the dataset so that:

Column names are clear and consistent
Empty rows are removed
All columns use correct data types
Sales values are numeric
Missing quantities are handled safely
These issues are intentional and must be fixed.

---

# Step-by-Step Guide

## 1️⃣ Load the Data

Open Power BI Desktop
Select Get Data → Excel
Choose sales_raw.xlsx
Select the SalesData sheet
Click Transform Data

## 2️⃣ Rename Columns

Rename columns to:

Order Date
Region
Product
Sales
Quantity

Use clear, simple names—this will matter later when writing DAX.

## 3️⃣ Remove Empty Rows

In Power Query:
Go to Home → Remove Rows → Remove Blank Rows


## 4️⃣ Fix Data Types

Set the correct data types:

Order Date → Date
Region → Text
Product → Text
Sales → Decimal Number
Quantity → Whole Number

If Sales contains currency symbols:
Replace $ and €
Then convert to a numeric type

## 5️⃣ Handle Missing Values

Replace null or blank values in Quantity with 0

## 6️⃣ Apply Changes

Click Close & Apply
Your cleaned dataset is now loaded into the data model.

# Expected Outcome

After completing this challenge, you should have:

One clean, structured table
Correct data types
No empty rows
A stable foundation for visuals and DAX measures
No visuals yet—this challenge is about getting the data right.

# Why This Matters

Most Power BI problems are caused by poor data preparation.
Mastering Power Query early:
Prevents broken dashboards
Improves performance
Makes reports easier to maintain
Saves hours later in the project
This skill separates beginners from professionals.

# Optional Bonus

If you want to go further:

Trim whitespace from Region
Standardize region names (e.g. us, US, Us → US)
Reorder columns logically

# Next Challenge

👉 Challenge #2: Create Your First KPI Card

You’ll use the cleaned dataset from this challenge to build your first Power BI visual.


# 🌐 About SolveWithPowerBI

SolveWithPowerBI helps you learn Power BI by solving real-world problems, one challenge at a time.

No long videos.
No theory overload.
Just practical Power BI skills.

