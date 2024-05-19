
## MySQL Fundamentals: Analyzing Sales Data

### Project Description
This project involves analyzing sales data using SQL. The goal is to perform various queries to gain insights into the sales performance of a company. The analysis includes retrieving data, calculating totals and averages, identifying top-performing regions and products, and more.
### Dataset
[Sales dataset](https://witscloud-my.sharepoint.com/:x:/g/personal/2168978_students_wits_ac_za/EUdSzYo6vnVKjp7EA9TMQY0BNWGA4tWtOor8H1VDsvpxKg?e=MrBH2M)
### Requirements
- Dataset: The provided sample dataset contains sales data with the following columns:
  1. Date: Date of the sale
  2. Product: Name of the product sold
  3. Sales: Total sales revenue generated
  4. Profit: Profit earned from the sale
  5. Region: Region where the sale occurred
- Provide explanations and interpretations of the results obtained from each query.
- Organize the analysis in a clear and structured manner.
- Use SQL functions and clauses to enhance the analysis.
- Take a screenshot of the code and the results in the solution document.

### Technologies Used
- MySQL

### Methods

#### 1. SQL
**Performing the following tasks using SQL queries**

- Retrieve all columns from the 'sales' table.
- Find the total sales and total profit generated.
- Calculate the average sales and average profit.
- Identify the top 3 regions with the highest total sales.
- Determine the product with the highest profit margin.
- Find the total sales and profit for each product.
- Calculate the average profit for each region.
- Identify the date with the highest sales.
- Determine the product with the highest sales in the East region.
- Identify the top 5 dates with the highest sales.

### Results

I provided my solutions in two documents. A google doc and google sheet.<br/>
On the google doc, I wrote the MySQL queries with the explanations. see a snap shot of it below.

![MySQL assessment 3 - Google Docs 2024-05-19 06_09_46](https://github.com/JonasGiven/MySQL-fundamentals-project/assets/169194581/0e8cfbe0-f730-4dc7-983b-7af28849a64b)
To access the google doc [click here](https://docs.google.com/document/d/1smuYvHCBbrSOrolQFgm-Om0RR4be_3ubtxR1-R6_P8c/edit?usp=sharing) <br/>
On the google sheet, I have all the images of the query results from MySQL. See below
![MySQL Results per query - Google Sheets 2024-05-19 06_18_31](https://github.com/JonasGiven/MySQL-fundamentals-project/assets/169194581/e9f05968-c2ef-4db0-b1fb-0af8730eec6d)

To access the google sheet file [click here](https://docs.google.com/spreadsheets/d/1T5PxfY5wwdwjZnxmeMcHjgD0yIchjOnyJfz29lWuksE/edit?usp=sharing)

---
### Access the Entire MySQL Code
To access the entire MySQL code, [click here](https://github.com/JonasGiven/MySQL-fundamentals-project/blob/main/MySQL%20code).

### Step-by-Step Guide to Run the MySQL Code

#### 1. Install MySQL Workbench
- Here is a youtube tutorial on how to install [MySQL workbench](https://youtu.be/BxdSUGBs0gM?si=VMxhT4WOfB7cYTTT)
- Download and install MySQL Workbench from the official MySQL website: [MySQL Workbench](https://www.mysql.com/products/workbench/)

#### 2. Create a Schema
- Open MySQL Workbench.
- In the Navigator pane on the left side, locate and expand the "SCHEMAS" section.
- Right-click on the empty space within the "SCHEMAS" section and select "Create Schema...".
- Enter "company_sales" as the name for the schema and click "Apply".

#### 3. Import the Table
- Download the provided dataset or use the table named "sales".
- In MySQL Workbench, right-click on the "company_sales" schema that you just created.
- Select "Table Data Import Wizard".
- Follow the wizard to import the table named "sales" into the "company_sales" schema.
- Make sure to specify the correct file or database connection for importing the table.

#### 4. Run the MySQL Code
- Open the MySQL script file containing the code you want to run.
- Make sure the schema is set to "company_sales" at the top of the script, or specify it explicitly in the queries.
- Highlight the queries you want to execute.
- Click the lightning bolt icon or use the shortcut (Ctrl+Enter) to run the selected queries.
- Review the results in the output panel to verify the execution of the queries.

### Additional Notes
- Ensure that MySQL Workbench is properly configured and connected to your MySQL server instance.
- Double-check the schema name and table name to ensure they match the names used in the MySQL code.
- Modify the queries as needed to suit your specific analysis 
