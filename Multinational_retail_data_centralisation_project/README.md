# Multinational Retail Data Centralization Project

## Project brief

You work for a multinational company that sells various goods across the globe.

Currently, their sales data is spread across many different data sources making it not easily accessible or analysable by current members of the team.

In an effort to become more data-driven, your organisation would like to make its sales data accessible from one centralised location.

Your first goal will be to produce a system that stores the current company data in a database so that it's accessed from one centralised location and acts as a single source of truth for sales data.

You will then query the database to get up-to-date metrics for the business.

## Milestone 1: Set up the environment

Set up GitHub and create a GitHub repo. 

## Milestone 2: Extracted and cleaned up data from the data sources

Task~1: Set up a local database to store data.

Task~2: Initialize three project Classes

Task~3: Extract and clean user data.

Task~4: Extracting users and cleaning card details.

Task~5: Extract and clean the details of each store.

Task~6: Extract and clean the product details.  

Task~7: retrieve and clean the orders table.

Task~8: Retrieve and clean the date events data.

## Milestone 3: Create the database schema

Task~1 : Cast the columns od the orders_table to the correct data types.

Task~2 : Cast the columns of the dim_users to the correct data types.

Task~3 : update the dim_stores_details table.

Task~4 : Make changes to the dim_products table for the delivery team.

Task~5 : update the dim_products table with the required data types.

Task~6 : update the dim_date_times table.

Task~7 : updating the dim_card_details table.

Task~8 : create the primary keys in the dimension tables.

Task~9 : Finalising the star-based schema & adding the foreign keys to the orders table.

## Milestone 4: Querying the data

Task~1.sql : How many stores does the business have and in which countries?

Task~2.sql : Which locations currently have the most stores?

Task~3.sql : Which months produce the most sales typically?

Task~4.sql : How many sales are coming from online?

Task~5.sql : What percentage of sales come through each type of store?

Task~6.sql : Which month in each year produced the most sales?

Task~7.sql : What is our staff headcount?

Task~8.sql : Which German store type is selling the most?

Task~9.sql : How quickly is the company making sales?

## Required Packages

### Package install requirements before running the project:

- [Tabula-py](https://github.com/chezou/tabula-py): `pip install tabula-py`
- [Requests](https://docs.python-requests.org/en/latest/): `pip install requests`
- [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html): `pip install boto3`
- [Pandas](https://pandas.pydata.org/): `pip install pandas`
- [SQLAlchemy](https://www.sqlalchemy.org/): `pip install SQLAlchemy`
- [Psycopg2](https://www.psycopg.org/): `pip install psycopg2`



