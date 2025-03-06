# Superstore Sales

## Overview
An analysis project on the customers of a superstore through a dataset on its sales

## Files:
  - `SuperstoreSales.csv`: Raw data on the sales
  - `RFM_analysis.sql`: Creation of the database as well as the queries required to perform RFM analysis
  - `README.md`: Description of the project

## Note:
Database management system is MySQL. Data was imported using the LOAD DATA query from the dataset that was stored locally. The directory mentioned in the query has to be changed according to where the dataset will be stored

## Methodology:
1. **Creation of database:** A 'Superstore_sales_database' is created unless it already exists 
2. **Creation of table:** The table 'superstore_sales_data' is created according to the category of the raw data noticing the datatype of each column
3. **Bulk insertion of data:** Data from the .csv file is inserted into the 'superstore_sales_data' table using the LOAD DATA query of MySQL
4. 
