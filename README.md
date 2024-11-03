# Manager Salary Analysis Project

## Project Overview

This project involves building a data pipeline that processes and analyzes data on manager salaries, including data cleaning, transformation, and exploratory visualization. The project involves managing missing data, standardizing formats, and exporting the refined dataset to both a database and a CSV files.

## Objectives
1. **Data Cleaning:** Handle missing values, standardize column formats, and transform categorical data where necessary.
2. **Data Transformation:** Derive new columns, such as total_compensation and seniority_level.
3. **Data Loading and Export:** Load the cleaned datasets into a SQLite database and export it to CSV files.
4. **Data Visualization:** Perform basic visualizations to understand salary distribution by various factors like education level and country.

## Dataset Description
### The dataset includes columns such as:
**Timestamp:** The date and time when the record was entered.

**Age:** Age of the respondent.

**Industry:** The industry in which the respondent works.

**Job Title:** Job title of the respondent.

**Annual Salary:** The respondent’s annual salary.

**Monetary Compensation:** Additional monetary compensation received.

**Currency:** The currency of the salary.

**Country:** The country where the respondent works.

**State:** The state (if applicable) where the respondent works.

**City:** The city where the respondent works.

**Work Experience:** Total years of work experience.

**Relative Work Experience:** Work experience relevant to the current job.

**Education Level:** The respondent’s highest level of education.

**Gender:** The respondent’s gender.

## Project Steps
1. **Data Loading**
Loaded the dataset and displayed initial rows to understand data structure.
Checked for null values and assessed data types.
2. **Data Cleaning**
Replaced missing values in critical columns (e.g., country and currency) with placeholders.
Cleaned categorical data for consistency (e.g., lowercasing text, removing extra whitespace).
Created total_compensation by adding annual_salary and monetary_compensation.
3. **Data Transformation**
Created a seniority_level column based on years of work experience.
Derived insights by grouping data by columns like education_level and country for further analysis.
4. **Data Visualization**
Used bar plots and box plots to visualize salary distributions by education level and country.
Presented visual insights into how factors like age and education affect total compensation.
5. **Data Loading and Export**
Saved the final cleaned data to an SQLite database for structured storage.
Exported the cleaned data to CSV files for further analysis or sharing.
