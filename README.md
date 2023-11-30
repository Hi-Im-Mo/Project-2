# Project-2
This project demonstrates proficiency at building an ETL pipeline from raw data. The code is authored entirely by the contributers to this repo and this README template is from the Data Science Working Group.

#### -- Project Status: [Completed]

## Project Intro/Objective
The goal of this project is to construct an ETL pipeline by reading in a given set of raw data, converting and normalizing the data for analysis, and storing the cleaned dataset in a SQL database for continued analysis. For the educational intent of this project, the dataset was generated arbitrarily. 

### Methods Used
* Data Cleaning, ETL
* CRUD Operations
* Relational Database Management

### Technologies
* Python
* Pandas, jupyter
* JSON

## Project Description
Our ETL pipeline can be evenly divided into 4 subsections. Initially, our team had been given 2 xlxs files containing raw "crowdfunding" and "contacts" data for a potential crowdfunding database. The first portion of our jupyter script deals with extracting the raw data from our "crowdfunding" source and normalizing the data by creating separate reference tables for the types of crowdfunding programs. The second portion of our jupyter script deals with the CRUD operations necessary to transform the existing "crowdfunding" dataset into a malleable table for analysis. This consisted of adding and dropping columns as well as updating datatypes and merging with the reference tables created previously. The third portion of our jupyter script extracts the JSON object from the "contacts" data source and transforms it into a malleable table to compare with the cleaned crowdfunding table. In our final portion of the ETL process, our team created a database "crowdfunding_db" to load our cleaned contacts and crowdfunding tables into for future analysis. 

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Our [Jupyter Notebook script](ETL_Mini_Project_GroupMerge.ipynb) is located in the forefront of this repo.
3. Our [SQL file](crowdfunding_db_schema.sql) is located in the forefront of this repo.
4. Cleaned datasets are available [here](Resources).
   
