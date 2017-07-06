# BigData_Session6_Assignment1


<<<<<<<<------------ Problem Statement ------------>>>>>>>>

Create a database named 'custom'.
Create a table named temperature_data inside custom having below fields:
1. date (mm-dd-yyyy) format
2. zip code
3. temperature
The table will be loaded from comma-delimited file.
Load the dataset.txt (which is ',' delimited) in the table.

Associated data file "dataset_Session 14.txt"

<<<<<<<<------------ Solution ------------>>>>>>>>

Screenshots 1-12 describe:
1. How to launch hive
2. How to create database
3. How to create table
4. How to load data in table

KeyNote:- Since required date format is mm-dd-yyyy, however data file contains date in dd-mm-yyyy, therefore, two tables are created

-> "temp_data" table captures data in the same format as in data file
-> "temperature_data" table captures data from "temp_data" but date field now contains date in mm-dd-yyyy format as asked in the assignment.
