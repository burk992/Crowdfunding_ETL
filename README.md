# Crowdfunding_ETL

This is a repository to conclude Project 2 of the Data Analytics Boot Camp through Washington University in St. Louis, partnered with edX. 

**Authors**

Chris Burk, https://github.com/burk992

Micah Lewis, https://github.com/younglewy23


# Introduction

In the ETL mini project, our collaborative task involved constructing an ETL pipeline using Python, Pandas, and Python dictionary methods for data extraction and transformation. Following the data transformation phase, we generated four CSV files, utilizing their data to construct both an Entity-Relationship Diagram (ERD) and a table schema. To conclude, we imported the CSV file data into a Postgres database.

# How To Use

Download the repo and open the 'ETL_Mini_Project_CBurk_MLewis.ipynb' file within Jupyter Notebook. Run all of the lines of code in sequence to generate fresh copies of the exported .csv files already included in the 'Resources' directory of the repo. 

Open pgAdmin4 go to Object > Create > Database and create a database named 'crowdfunding_db'.

Select the new database and open a query. Use the 'Open File' function to load in 'crowdfunding_db_schema.sql', and run the code.

Within the new database and schema, seperately import to each table the respectively named .csv file from the 'Resources' directory. Load the 'Campaign' data into the table after the other three tables. 

You can then use the 'Open File' function within the database query to load 'queries.sql'. Run each line of the queries file seperately to confirm that data has been loaded into each table.

An example of the ERD for the SQL database is included as 'databaseERD.png'. 

