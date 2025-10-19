# Vendor-Performance-Analysis
We have analyzed the performance of each vendor to identify the poorly performing vendor & high-performance vendor. 
Our aim is to increase profit & reduce inventory management cost by analyzing the vendor performances.

Below are the steps that I have performed into the project:-

1. Data Collection:- We have created vendor summary table by fetching required columns from various tables like 	Purchases,	Purchase_prices,Sales,	Vendor_Invoice.
2. Data Cleaning & transformation:- In this step we have cleaned the data & created some new columns from the existing columns.
3. EDA( Exploratory Data Analysis):- We have derived some insights by performing the EDA.
4. Creation of the Power BI dashboard.
5. Report Writing:- In this section we have done storytelling from the data.

Below is the information of the files of the project:-

1. ingestion_db.ipynb --> Reading all CSV files & then storing them into the postgresql database tables.
2. get_vendor_summary.ipynb --> Creation of vendor_summary_table from the all tables. Then storing that table in postgresql.
3. EDA --> Exploratory Data Analysis
4. Vendor_Performance_dashboard --> Power BI dashboard.
5. Data Link:- 
6. Report Writing --> Final report of the analysis. 
   
Below is the description of all data files:-

1. Begin_Inventory:- It has the records of the inventory at the starting of the year.
2. End_Inventory:-It has the records of the inventory at the ending of the year.
3. Purchases:-This table holds every purchase done by the vendors including purchase prize, quantity.
4. Purchase_prices:-This table holds the actual & purchase price of each brand purchased by vendor.
5. Sales:- This table has the live data of all the sales done in the year by each & every vendor.
6. Vendor_Invoice:- It has the invoice details vendor wise including the freight cost (Cost required for the delivery of product) for that invoice. 
