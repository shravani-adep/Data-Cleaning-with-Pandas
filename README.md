# Data Cleaning Project using Python & Pandas

# Project Overview

This project demonstrates a complete data cleaning workflow using Python and Pandas on a real-world Data Analyst job dataset.

The objective was to transform raw, inconsistent, and incomplete data into a clean and analysis-ready dataset suitable for SQL quering ,Exploratory Data Analysis (EDA), Machine Learning, and Business Intelligence applications.



# Dataset

The dataset contains information related to Data Analyst job postings, including:

* Company Name
* Salary Estimate
* Rating
* Industry
* Sector
* Revenue
* Headquarters
* Competitors
* Founded Year



# Project Goals

* Identify and handle missing values
* Remove invalid data entries and unnecessary columns
* Standardize column names
* Fix inconsistent formats
* Convert data types
* Clean salary column information
* Prepare the dataset for further analysis



# Tools & Libraries

* Python
* Pandas
* Jupyter Notebook



# Data Cleaning Steps Performed

# 1. Data Inspection

* Loaded dataset using Pandas
* Checked dataset shape
* Checked column information
* descriptive statistics

# 2. Removed Unnecessary Columns

* Dropped irrelevant columns not required

# 3. Missing Value Analysis

* Identified null values across all columns
* Evaluated missing-value patterns

# 4. Duplicate Detection

* Checked for duplicate records

# 5. Column Name Standardization

* Removed leading and trailing spaces
* Replaced spaces with underscores
* Improved naming consistency

# 6. Invalid Value Handling

* Identified placeholder values such as:

  * -1
  * "-1"

* Replaced invalid entries with proper null values

# 7. Missing Value Imputation

# Numerical Columns

* Filled missing Rating values using median imputation

# Categorical Columns

* Filled missing values using:

  * "Unknown"
  * "Unknown / Non-Applicable"
  * "FALSE"

depending on business context

# 8. Data Type Conversion

* Converted Rating to numeric format
* Converted Founded year to nullable integer format('INT64')


# 9. Salary Data Cleaning

Cleaned salary estimates by:

* Removing text such as "(Glassdoor est.)"
* Removing currency symbols
* Converting salary ranges into numeric values
* Extracting minimum and maximum salary values


# 10. Final Validation

* Rechecked missing values
* Verified data types
* Confirmed removal of invalid entries



The final dataset was transformed into a clean, structured, and analysis-ready format that can be directly used for:

* Exploratory Data Analysis (EDA)
* Machine Learning Models
* Dashboard Development
* Business Reporting



# Author

Shravani Adep

Aspiring Data Analyst | Data Scientist
