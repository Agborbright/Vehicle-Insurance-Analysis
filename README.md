# Vehicle Insurance Analysis
## This project provide an analysis into fraudulent claims in XYZ insurance company

### Data Summary
The dataset came in a structured format (CSV) with 15,420 rows and more than 29 columns. Some main columns includes age of policy holder, police reported filed, witness present, vehicle price, number of past claims etc. The insurance dataset was downloaded from Kaggle.

### Objective
The objective of this report was to analyse fraudulent claims and uncover hidden patterns that indicate fraudulent activities. The analysis focuses on identifying which factors such as marital status, vehicle price, driver age, car brand, vehicle age etc are mostly associated with fraudulent claims, helping insurance companies detect and prevent false claims.

#### The end user should be able to indentify:
Total fraud case 
Deductible 
Supplemental claims



### Approach
The dataset was imported into MySQL for cleaning. To ensure quick data refresh, some redundant columns were dropped. After the cleaning process, the data was loaded directly into Power BI using the ODBC in the get data tool. Basically, an ETL was performed.
In Power BI, data transformation was carried out to ensure data is in it right format. Data modeling was created for faster data refresh.
