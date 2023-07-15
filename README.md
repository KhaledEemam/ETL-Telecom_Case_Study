# ETL-Telecom_Case_Study

This is a project that involves Extracting, Transforming, and Loading (ETL) data from CSV files into a database. It provides a solution for storing and processing data related to customer transactions for a telecommunications company.

## Project Overview

The goal of this project is to automate the process of storing and managing customer transaction data in a database. It involves the following steps:

1. **Data Extraction**: A system periodically saves a CSV file containing customer transaction data every 5 minutes. This CSV file includes essential information about various transactions within a specific time period.

2. **Data Transformation**: The extracted data undergoes necessary processing to ensure its quality and suitability for database storage. This includes validating and cleaning the data, as well as performing any required data transformations or calculations.

3. **Data Loading**: The processed data is then loaded into a database for long-term storage and efficient querying. The main dataset is stored in a designated table, while rejected records that do not meet the required conditions are stored in a separate table. Additionally, a link is established between the stored data in the database and the original CSV file.

4. **Post-processing**: Once the data is successfully stored in the database, the CSV file is moved to another designated folder for archival or further processing purposes.

## Used tools

- SQL Server
- SQL Server Integration Services (SSIS)
