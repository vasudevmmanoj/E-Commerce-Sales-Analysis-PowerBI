E-Commerce Sales Analysis using Power BI

This project focuses on analyzing e-commerce sales data using Microsoft Power BI. The project covers data importing, transformation, data modeling, relationships, and sales analysis using Power Query and Power BI.

📂 Project Files

The complete project files, including the source CSV files and Power BI file, are available here:

📁 Access Project Files – 📁 [Access Project Files – Google Drive](https://drive.google.com/drive/folders/1ZYszNy48zMotarvtRIk3TqUP_U6bA845?usp=drive_link)

📊 Dataset

The project uses the following datasets:

* List of Orders.csv
* Order Details.csv
* Sales Target.csv

🛠️ Data Transformation

The following transformations were performed using Power Query:

* Restricted the List of Orders table to the first 500 rows.
* Converted Order Date to Date format.
* Converted Amount and Target to Fixed Decimal Number.
* Formatted CustomerName using Proper Case.
* Created a Location column in the format City, State.
* Created a Profit Margin column.
* Created a Profit Status column with:
    * Profit
    * Loss
    * Break-Even
* Merged List of Orders and Order Details using Order ID.

🔗 Data Modeling

Relationships were established between:

* List of Orders → Order Details using Order ID
* Order Details → Sales Target using Category

📈 Analysis

The project includes analysis of:

* Sales and profit
* Profit margin
* Order trends
* State-wise performance
* Category and sub-category performance
* Sales targets
* Monthly target analysis
* Profit/Loss status
* Recent order trends

🧹 Data Cleaning

Missing values and duplicate records were identified and handled appropriately during the data preparation process.

💻 Tools Used

* Microsoft Power BI
* Power Query
* CSV
* DAX

🎯 Objective

The objective of this project is to demonstrate practical skills in data cleaning, transformation, data modeling, relationship creation, aggregation, and business-oriented sales analysis using Power BI.
