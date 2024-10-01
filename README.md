#Olist Sales Data Analysis Project

## 1 - Objective
The goal of this project is to perform a comprehensive sales data analysis for Olist, a Brazilian company. The idea was to make the analysis as close to a real-world business scenario as possible by fetching data using SQL and visualizing the insights with Power BI.

## 2 - Methodology

### 2.1 - Data Loading
The data was downloaded from Kaggle in CSV format, consisting of multiple CSV files.

### 2.2 - Clean Database Creation
After downloading the files, I created a database using SQL through DBeaver. This involved joining various tables using primary keys. Once the database was structured, I performed a cleaning process with specific SQL queries.

During the process, I noticed a significant amount of duplicate rows in my database. While I initially attempted to remove them using SQL, the query was too time-consuming (over an hour). I then opted to use Python and the Pandas library, which provided a more efficient solution. As a result, the file size reduced dramatically from 17 GB to 56 MB.

### 2.3 - Power BI Dashboard
Once the database was cleaned, I imported the data into Power BI to create a dashboard. The goal was to synthesize key information that a manager or director at Olist would need, including revenue insights, best-selling products, and various other charts.

## 3 - Areas of Improvement

I would have liked to fetch the data directly from a server via SQL queries. This would have made the project even closer to real-world business operations, where data is often fetched from data lakes.
My initial plan was to work exclusively with MySQL and establish a direct connection to Power BI. Unfortunately, MySQL couldn’t read my CSV files, which led me to use DBeaver for the database creation.
I would have preferred not to use Python for data cleaning. However, due to the slow performance of SQL queries in DBeaver, Python provided a much faster solution for reducing the database size.


## 4 - Contribution

Several YouTube videos helped me improve my skills in SQL and Power BI. Additionally, artificial intelligence tools like ChatGPT 4.0 were invaluable in refining my SQL queries and optimizing my code.
