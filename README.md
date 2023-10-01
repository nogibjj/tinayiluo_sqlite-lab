## Python Script interacting with SQL Database
[![CI](https://github.com/nogibjj/tinayiluo_sqlite_lab/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/tinayiluo_sqlite_lab/actions/workflows/cicd.yml)

Week 5 Mini Project
Requirements
* Connect to a SQL database
* Perform CRUD (create, read, update, delete) operations
* Write at least two different SQL queries
Grading Criteria
* Database connection (20 points)
* CRUD operations (20 points)
Deliverables
* Python script
* Screenshot or log of successful database operations

### Goal

+ Set up a CodeSpaces environment to automate the interaction between Python Script and SQL Database.

+ This environment should facilitate connection to an SQL database, execution of CRUD (Create, Read, Update, Delete) operations, and formulation of at least two distinct SQL queries.

The workflow includes running a Makefile to perform tasks such as installation (`make install`), testing (`make test`), code formatting (`make format`) with Python Black, linting (`make lint`) with Ruff, and an all-inclusive task (`make all`). This automation streamlines the data analysis process and enhances code quality.

### Preperation

+ I forked the nogibjj/sqlite-lab.

+ I chose the Airline safety dataset `airline-safety.csv` from Github.

### Dataset Description

The dataset airline-safety.csv originates from the Aviation Safety Network and consolidates safety-related information for 56 airlines in a CSV file. It encompasses data on available seat kilometers flown every week and provides a detailed record of incidents, fatal accidents, and fatalities, each segregated into two time frames: 1985–1999 and 2000–2014.

#### [Resources](https://github.com/fivethirtyeight/data/tree/master/airline-safety) 

### Overview

This project creates a Python script that facilitate connection to an SQL database, execution of CRUD (Create, Read, Update, Delete) operations, and formulation of at least two distinct SQL queries. The specific steps involve: 

+ In my.lib, add extract.py, query.py and transform_load.py that perform:

* ETL-Query:  [E] Extract a dataset from URL, [T] Transform, [L] Load into SQLite Database and [Q] Query

* [E] Extract a dataset from a URL like Kaggle or data.gov. JSON or CSV formats tend to work well.

* [T] Transform the data by cleaning, filtering, enriching, etc to get it ready for analysis.

* [L] Load the transformed data into a SQLite database table using Python's sqlite3 module.

* [Q] Write and execute at least 2 different SQL queries on the SQLite database to analyze and retrieve insights from the data.
      Perform CRUD (create, read, update, delete) operations

+ Convert the main.py into a command-line tool that run each step independantly

+ In test_main.py, test extract, transform, CRUD (Create, Read, Update, Delete), and general query

+ In make file, add extract, transform_load, and query command

+ Include an architectural diagram showing how the project works

### Description

Step 1: In my.lib: 

+ create extract.py

+ create quetry.py

+ create transform_load.py

### Make Format, Test, Lint, All Approval Image
<img width="851" alt="Screen Shot 2023-09-30 at 7 32 58 PM" src="https://github.com/nogibjj/tinayiluo_sqlite_lab/assets/143360909/f0907017-4be5-49de-9e97-739047599c82">
<img width="1151" alt="Screen Shot 2023-09-30 at 7 36 13 PM" src="https://github.com/nogibjj/tinayiluo_sqlite_lab/assets/143360909/3df48fef-a3a2-4f87-8c78-3517c6b4dbe3">
<img width="1136" alt="Screen Shot 2023-09-30 at 7 36 57 PM" src="https://github.com/nogibjj/tinayiluo_sqlite_lab/assets/143360909/c6174dd0-4f34-47a4-b23e-815c4eab5be7">
