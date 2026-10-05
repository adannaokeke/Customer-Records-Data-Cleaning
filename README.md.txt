# Customer Records Data Entry & Cleaning Project

## Project Overview

This project demonstrates a practical workflow for entering, cleaning, validating, organizing, and reporting customer data using Microsoft Excel.

The dataset contains customer records with common data-quality issues such as inconsistent formatting, inconsistent gender values, inconsistent phone-number formats, extra spaces, and duplicate records.

The goal of the project was to identify these issues, clean and standardize the data, validate the cleaned dataset, and create a simple summary report for decision-making.

## Business Problem

Small businesses may collect customer information in different formats, which can lead to inaccurate, inconsistent, or duplicated records.

For this project, the customer dataset contained several data-quality issues that could affect reporting and record management.

The task was to identify these issues, clean and standardize the records, remove duplicates, validate the final dataset, and produce a clear summary report.

## Project Objectives

* Enter and organize customer records in Microsoft Excel.
* Identify common data-quality issues.
* Clean and standardize customer information.
* Detect and remove duplicate records.
* Validate the cleaned dataset using Excel formulas.
* Summarize customer records by gender and city.
* Create a simple report and chart to communicate the results.

## Dataset

The dataset contains 30 customer records with the following fields:

* Customer ID
* Full Name
* Gender
* Phone
* Email
* City
* Registration Date

The raw dataset was intentionally prepared with common data-entry and data-quality issues to simulate a realistic cleaning task.

After cleaning and removing duplicate records, the final dataset contained **28 customer records**.

## Data Quality Issues Identified

The following data-quality issues were identified during the initial inspection:

* Inconsistent capitalization in customer names.
* Inconsistent gender values such as `M`, `F`, `Male`, and `Female`.
* Inconsistent capitalization in gender values.
* Inconsistent phone-number formats.
* Leading and trailing spaces in some customer names.
* Duplicate customer records.

A separate **Data_Quality_Check** worksheet was used to document the identified issues and the required corrective actions.

## Data Cleaning Process

The following cleaning steps were performed in Microsoft Excel:

1. **Names:** Removed leading and trailing spaces and standardized name capitalization.
2. **Gender:** Standardized gender values to `Male` and `Female`.
3. **Phone Numbers:** Removed spaces and hyphens and standardized phone numbers to an 11-digit format.
4. **Duplicates:** Identified and removed duplicate customer records.
5. **Cleaned Dataset:** Stored the cleaned records separately from the original raw data to preserve the source data.

The original raw data was kept unchanged, while the cleaned records were maintained in a separate **Cleaned_Data** worksheet.

## Validation Checks

After cleaning the data, validation checks were performed using Excel formulas to confirm that the dataset met the required quality standards.

The following checks were completed:

* Total cleaned records: **28**
* Duplicate Customer IDs: **0**
* Missing names: **0**
* Missing emails: **0**
* Invalid gender values: **0**
* Invalid phone-number lengths: **0**

All validation checks passed successfully.

The results were documented in the **Validation_Check** worksheet.

## Summary Results

The cleaned dataset contained **28 customer records** after duplicate records were removed.

### Gender Distribution

* Male customers: **14 (50%)**
* Female customers: **14 (50%)**

### Customer Distribution by City

* Abuja: **6**
* Lagos: **6**
* Enugu: **4**
* Kaduna: **3**
* Kano: **3**
* Ibadan: **2**
* Owerri: **2**
* Calabar: **1**
* Port Harcourt: **1**

Abuja and Lagos had the highest number of customer records, with **6 customers each**.

A PivotTable and chart were used to summarize and communicate the customer distribution by city.

## Tools Used

* **Microsoft Excel**

  * Data entry and organization
  * Data cleaning and standardization
  * Excel formulas
  * Duplicate detection and removal
  * Data validation
  * PivotTables
  * Charts and reporting

* **Git & GitHub**

  * Project version control
  * Portfolio documentation and project sharing

## Skills Demonstrated

* Data Entry
* Data Cleaning
* Data Validation
* Data Organization
* Data Quality Checking
* Duplicate Detection
* Excel Formulas and Functions
* PivotTables
* Basic Data Reporting
* Basic Data Visualization
* Documentation
