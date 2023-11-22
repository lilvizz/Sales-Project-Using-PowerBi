# Power BI Sales Project

## Overview

This repository contains a Power BI project focused on visualizing and analyzing sales data across different products and domains. The project involves data manipulation in Excel, storage and retrieval in SQL Server Management Studio (SSMS), and visualization using Power BI.

## Prerequisites

Before getting started, ensure that you have the following software installed:

- **Microsoft Excel:** Used for data preparation and initial analysis.
- **SQL Server Management Studio (SSMS):** Required for managing and querying the SQL database.
- **SQL Server (or SQL Express):** The database engine where sales data will be stored.
- **Power BI Desktop:** Used for creating and modifying Power BI reports.

## Setup Instructions

### 1. Excel Data Preparation

1. Open the Excel file (`SalesData.xlsx`) in the 'Data' folder.
2. Verify and clean the data as needed.
3. Save the Excel file with the prepared data.

### 2. SQL Server Database Setup

1. Open SSMS and connect to your SQL Server instance.
2. Run the SQL scripts in the 'SQL Scripts' folder:
   - `CreateDatabase.sql`: Creates the database for sales data.
   - `CreateTables.sql`: Defines tables for products, domains, and sales.
   - `InsertData.sql`: Inserts data from the Excel file into the tables.

### 3. Power BI Report Creation

1. Open Power BI Desktop.
2. Connect to the SQL Server database using the 'Get Data' option.
3. Load relevant tables into Power BI.
4. Design visualizations and reports based on your analysis requirements.
5. Save the Power BI file (`SalesAnalysis.pbix`) in the 'Power BI' folder.

## Folder Structure

- **Data:** Contains the Excel file with raw sales data.
- **SQL Scripts:** Includes SQL scripts for database and table creation.
- **Power BI:** Holds the Power BI file with visualizations and reports.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and enhancements are highly appreciated.


