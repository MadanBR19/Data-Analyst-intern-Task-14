# Data-Analyst-intern-Task-14
Task-14
🧩 Task 14 — ETL Mini Pipeline (Python)

This project demonstrates a complete ETL (Extract → Transform → Load) pipeline using Python and SQLite, simulating a real-world data engineering workflow.

🎯 Objective

To build a mini ETL pipeline that:

Extracts raw retail data

Cleans and transforms the dataset

Creates new analytical features

Splits the dataset into normalized tables

Loads structured data into a database

🛠 Tools & Technologies

Python

Pandas

SQLite

Jupyter Notebook / Google Colab

🔄 ETL Pipeline Steps
🔹 1. Extract

Loaded raw dataset from CSV file

Stored inside raw/ folder

🔹 2. Transform

Data cleaning and preparation:

Removed duplicate records

Handled missing values

Standardized column names

Converted date fields to proper datatype

Created new features:

margin = sales − cost

