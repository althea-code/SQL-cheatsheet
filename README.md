# SQL-cheatsheet
common SQL commands

-- create a new database  
  CREATE DATABASE name_of_database; 

-- shows all databases   
  SHOW DATABASES;

  -- create a table
  CREATE TABLE table_name (
    id INT AUTO_INCREMENT PRIMARY KEY,
    column_name VARCHAR(100),
    column_name VARCHAR(50)
);

-- show all tables
SHOW TABLES;

-- Select a database
USE database_name;

-- select a table
USE table_name;

-- add a new column to a table
ALTER TABLE table_name ADD new_column variable_type;




