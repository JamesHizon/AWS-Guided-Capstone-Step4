# AWS Guided-Capstone Step 4 - Analytical ETL

### Description
After loading trade and quote tables with daily records, this step focuses on using Spark SQL and Python in order to build an ETL job which calculates the following results for a given day:
1. Latest trade price before the quote.
2. Latest 30-min moving average trade price, before the quote.
3. The bid/ask price movement from previous day's closing price.

### Learning Objectives:
By the end of this step, you will be able to:
1. Use more advanced Spark data transformations and SQL functions.
2. Leverage different methods to join datasets.
3. Use Spark Broadcast to achieve optimal performance.
4. Use Spark UI to monitor Spark jobs.

### Prerequisites:
1. PySpark: Temporary view, creating a DataFrame from a Hive table, knowledge of broadcast variables, use of SparkUI.
2. SQL: Analytical functions, joins, unions.
3. Hive: Hive DDL, external tables, etc.

### Uploaded File:
A Jupyter Notebook downloaded from AWS EMR Notebooks. In this file, I ended up realizing that some of the data I needed for my data transformations were missing. Thus, I ended up having to re-do previous steps to ensure I have to desired data from appropriate fields and also test to ensure that data is being transformed as desired using either the ".head()" or ".show()" methods.

