## Electricity Billing and Reporting Project ⚡

### Project Description 💡

This project involves working with two data sources: the customer database (`CompanyLtd`) and
a CSV file containing real electricity prices. The goal is to track electricity purchase prices, 
sales prices through different channels, and the company's profit to make strategic decisions. 
Specifically, the project aims to create fact data from the billing and billing cost in the year 2021. 📈

Build an ETL solution where you load the data into a staging database, modify the data for reporting purposes, 
investigate data gaps, and possibly correct them. Finally, load the data into the PowerBI system for reporting 
using database views. Design useful reports for the company in PowerBI. 📊

### Tools Used 🛠

* Visual Studio Community 
* SQL Server 
* PowerBI 

### Assignment 1 

1. Create a new database using a script. 

2. Ensure the database is in simple recovery mode. 

3. Take an initial full backup of the database. 

4. Update the data of a table. 

5. Take a screenshot of the table data, highlighting the modified data. 

6. Restore the database to its original state. 

7. Ensure the table data has been restored. 

8. Take a screenshot of the table data, highlighting the restored data. 

### Assignment 2 

1. Open Visual Studio Community. 

2. Create a new SSIS project. 

3. Add a Data Flow Task to the project. 

4. Use Source Assistant to create a flat file source using the `electricity_price.csv` file. 

5. Use Destination Assistant to create a SQL Server destination table named `extractedPrices`. 

6. Ensure proper data mappings. 

7. Add an Execute SQL Task in the Control Flow view with the command to TRUNCATE the destination table. 🗑

8. Execute the task. 

### Assignment 3 

1. Open Visual Studio Community. 

2. Create a new SSIS project. 

3. Add a Data Flow Task to the project. 

4. Use Source Assistant to create a SQL Server source using the `CompanyLtd` database. 

5. Use Destination Assistant to create a SQL Server destination table for each source table. 

6. Ensure proper data mappings. 

7. Add an Execute SQL Task in the Control Flow view with the command to TRUNCATE each destination table. 

8. Execute the task. 

### Assignment 4 

Create two views: 

* `vFactCustomerInvoices` with columns:
    * invoicenumber
    * customer_id
    * invoicedate
    * duedate
    * totalamount
    * totalcost

* `vFactCustomerInvoiceRows` with columns:
    * invoicenumber
    * rownumber
    * customer_id
    * amount
    * cost
    * contract_id
    * contracttype_id

Use T-SQL. 🐘

### Assignment 5 

1. Create a new PowerBI report project. 

2. Add the views and all dimension tables from the previous tasks to the PowerBI data model. 

3. Establish connections between the data models. 

4. Create two reports based on the loaded data. 

5. Take screenshots of the reports. 

6. Take screenshots of the data models and their connections. 

### Links 🔗

* [Visual Studio Community](https://visualstudio.microsoft.com/)
* [SQL Server](https://www.microsoft.com/sql-server/)
* [PowerBI](https://powerbi.microsoft.com/)
