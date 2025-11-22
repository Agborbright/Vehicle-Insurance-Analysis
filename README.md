# Vehicle Insurance Analysis
## This project provide an analysis into fraudulent claims in XYZ insurance company


## Table of Content
- [Data Summary](#data-summary)
- [Data Source](#data-source)
- [Tools](#tools)
- [Objective](#objective)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Data Limitation](#data-limitation)
- [Approach](#approach)


## Data Summary
The dataset came in a structured format (CSV) with 15,420 rows and more than 29 columns. Some main columns includes age of policy holder, police reported filed, witness present, vehicle price, number of past claims etc. The insurance dataset was downloaded from Kaggle.


## Data Source:
The data was downloaded from Kaggle


## Tools
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) for data cleaning

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black) for creating visuals and report


## Objective
The objective of this report was to analyse fraudulent claims and uncover hidden patterns that indicate fraudulent activities. The analysis focuses on identifying which factors such as marital status, vehicle price, driver age, car brand, vehicle age etc are mostly associated with fraudulent claims, helping insurance companies detect and prevent false claims.


## The end user should be able to indentify:
- Total fraud case
- Deductible
- Supplemental claims


## Problem solved
- The isurance company had a total of 923 fraudulent claims
- The insurance company saw $379,100 deductible
- Policyholders made 1,973+ supplemental claims


## Key Findings
- 920 Accident cases had no witnesses present at the scene of the incident
- 907 Accident cases were never reported to the police by either the drivers or the Policyholders.
- 939 Fraudulent claims were made by married couples. Married men accounted for 576 of the fraudulent claims.
- Pontiac is the most claimed vehicle brand with 213 fraudulent claims.
- 360 Policyholders who made fraudulent claims were between the ages of 31-35
- 68 Policyholders have previously made more than four fraudulent claims
- 189 Policyholders claimed vehicle worth more than $69,000 with two claimants aged 18 - 20.


## Recommendations
- Automatically flag all accidents without police report for enhanced review by external agent
- Flag all claims with more than 3 supplements for enhanced review by external agent
- Increase premiums for Policyholders with more than two past claims
- Implement mandatory vehicle inspections for Policyholders filing a claim for vehicle worth $69,000
- Provide additional fraud detection training for internal agents and randomly check their decisions.


## Data Limitation
The dataset had no data dictionary, making analysis a bit challenging 


## Approach
The dataset was imported into MySQL for cleaning. To ensure quick data refresh, some redundant columns were dropped. After the cleaning process, an ETL was performed.  loaded the data directly into Power BI using the ODBC in the get data tool.
In Power BI, data transformation was carried out to ensure data is in it right format. Data modeling was created for faster data refresh.
