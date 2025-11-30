# powerbi-practice-project-dashboards
Power BI • SQL Server • MySQL • DAX • Power Query

This project demonstrates an end-to-end analytics workflow involving SQL-based data cleaning, database switching, and interactive Power BI report creation.

🚀 Project Overview

I built a Power BI dashboard from scratch using data stored in SQL Server and MySQL.
The goal was to clean the data, resolve date format issues, merge tables using SQL joins, and create a fully interactive dashboard for product availability and demand insights.

🛠️ Tech Stack

Power BI Desktop

SQL Server (MSSQL)

MySQL

Power Query (M-code)

DAX

Excel

🔧 Process & Steps
1. Data Loading & Exploration

Imported raw Excel datasets into SQL Server for validation.

Explored and understood column structures, data types, and missing values.

2. Data Cleaning in SQL

Fixed inconsistent date formats (DD-MM-YYYY vs YYYY-MM-DD)

Removed errors and resolved null values

Standardized column names

Joined tables using Product ID

3. Data Source Switching (MSSQL → MySQL)

Migrated data source inside Power BI

Updated Power Query M-code using Advanced Editor

Corrected errors caused by type conversion and date formats

Ensured the model remained intact after database switching

4. Power BI Modelling

Built relationships between tables

Created a clean model

Fixed data types and rebuilt slicers based on new columns

5. DAX Calculations

Used DAX to compute KPIs such as:

SUM()

SUMX()

DIVIDE()

FILTER()

CALCULATE()

6. Publishing

Created a dedicated Power BI workspace

Published the final report to Power BI Service

📸 Dashboard Screenshots

All screenshots are inside the Screenshots folder.

📂 Files Included

SQLMySQLdashboard.pbix

mySQLdashboard.pbix

/Screenshots/ – visuals and data model screenshots

README.md

🎯 Key Learnings

Hands-on experience with SQL joins

Advanced Power Query transformations (including date fixes)

Switching entire data sources in Power BI

Building clean data models

Using DAX to create metrics

Publishing reports using Power BI Service

🏁 Outcome

A fully functional Power BI dashboard that showcases product demand, availability, and pricing insights, built with end-to-end BI development best practices.
