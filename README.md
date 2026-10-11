# HR Analytics & Employee Attrition Dashboard (Excel)

## Overview
Excel portfolio project using a synthetic workforce dataset to analyze headcount, department composition, salary patterns, satisfaction, overtime, and attrition.

## Dataset
- 350 synthetic employee records across seven departments
- INR salary assumptions
- Educational practice data only; no real employee information

## Key features
- Raw and cleaned data worksheets
- Derived tenure and salary bands
- KPI cards: headcount, employees left, attrition rate, average monthly salary
- Department headcount, attrition rate, and average salary charts
- Department selector that filters KPI cards
- Data dictionary and project guide

## Data cleaning
- Missing Education values are labeled `Not specified`.
- Leading/trailing spaces are removed from text fields.
- Tenure and salary bands are derived for segmentation.
- Raw records are preserved in `Raw_Data`.

## Metric definition
Attrition rate = records with Employment_Status `Left` divided by all employee records in the selected group. This is a simplified portfolio metric, not a standardized period-based turnover rate.

## Tools
Microsoft Excel, Excel Tables, COUNTIF, COUNTIFS, AVERAGEIF, data validation, charts, conditional formatting.

## How to use
Open `workbook/HR_Analytics_Attrition_Dashboard.xlsx` in Excel and allow formulas to recalculate. On Dashboard, change cell B4 to All or a department.
