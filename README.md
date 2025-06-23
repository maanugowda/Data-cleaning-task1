# Data-cleaning-task1
 "Data Cleaning and Preprocessing for Elevate Data Analyst Internship Task 1."
For Task 1, "Data Cleaning and Preprocessing" , I chose the "Sales Data"  from the suggested Kaggle datasets. This dataset was provided across four CSV files: sales data.xlsx - Sales Orders.csv, sales data.xlsx - Customers.csv, sales data.xlsx - Regions.csv, and sales data.xlsx - Products.csv.


Here is a short summary of the changes I made to clean and preprocess the data:

Handling Missing Values: I identified and addressed missing values across all datasets. This involved using methods like imputation (filling with mean, median, or mode) or removal of rows/columns, depending on the extent and nature of the missing data in each specific column.

Removing Duplicate Rows: I checked for and removed any duplicate rows present in each of the four datasets to ensure data uniqueness and integrity.


Standardizing Text Values:
In the Customers.csv and Regions.csv files, I standardized text entries for consistency. This included ensuring uniform capitalization and correcting any minor spelling variations (e.g., in customer names or region names).

For the Products.csv, product categories and names were standardized to prevent inconsistencies.
Converting Date Formats: In sales data.xlsx - Sales Orders.csv, I converted the date columns (e.g., OrderDate, ShipDate) to a consistent YYYY-MM-DD format to facilitate time-series analysis and ensure uniformity.

Renaming Column Headers: All column headers across the four CSVs were renamed to be clean, uniform, and easily accessible. This typically involved converting them to lowercase and replacing spaces with underscores (snake_case) (e.g., SalesOrderID became sales_order_id).
Checking and Fixing Data Types: I ensured that all columns had appropriate data types. For instance, numerical columns like Quantity and Price were set to integer or float types, and date columns were converted to datetime objects.
Outlier Treatment: While the task description didn't explicitly require it, I performed a preliminary check for outliers in numerical columns within the Sales Orders and Products datasets and addressed any significant anomalies that could skew analysis.
These changes have resulted in a clean, structured dataset ready for further analysis or modeling.
