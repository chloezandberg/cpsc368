# CPSC368: Databases in Data Science Research Project 

##### DataBAES (2025W2)
##### Authors: Olivia Lam & Chloe Zandberg


## About

This proposal examines how gender influences mental health experiences and workplace support in the tech industry. Our research focuses on two questions:
1. How do different genders describe their experiences with mental health support?
2. What is the average work time affected by mental health issues for women in tech?

Through qualitative thematic analysis and quantitative measures, we aim to uncover gendered disparities in mental health support and their impact on work performance, using trusted datasets like the OSMH mental health in tech survey and a general employee burnout dataset.


## Report
The final report can be found [here](https://docs.google.com/document/d/1gchvxl2wJo4w8LNdewH5KYQuhAWkNQO1HHuoyoXQ1F8/edit?usp=sharing).


## Required Libraries
- pandas: version 2.2.2
- numpy: version 1.26.4
- sqlite3: version 2.6.0
- altair: version 5.5.0


## Project File Descriptions
- ``cleaning-EDA/cleaning-EDA.ipynb``:
  This file is where we performed some basic cleaning and conducted some exploratory data analysis to better understand the data we were working with in context of our research questions. We also created and inserted data into our SQL file in preparation for our analysis.
- ``cleaning-EDA/mental_health.sqlite``:
  This file contains the mental health data that we used for our project from an SQLite database.
- ``database/cpsc368_proj.sql``:
  This file is the SQL file we created and exported our cleaned data into through a series of INSERT statements.
- ``analysis/chloe-implementation.ipynb``
  This file contains the work that Chloe did to establish a SQL connection, write a query to the database, and create a visualization in Altair.
- ``analysis/oli-implementation.ipynb``
This file contains the work that Olivia did to establish a SQL connection, write a query to the database, and create a visualization in Altair.
- ``database/my_database.db``
This is the database object we created to establish a SQLite connection.

## Report Query Specifications
- Chloe's SQL query is in ``analysis/chloe-implementation.ipynb`` at Cell 2, Lines 5-8.
- Olivia's SQL query in is ``analysis/oli-implementation.ipynb`` at Cell 1, Lines 8-10.

## Instructions to load our SQL file into the UBC CS Department server
1. After SSHing to the server department, use ``wget https://raw.githubusercontent.com/chloezandberg/cpsc368/main/cpsc368_proj.sql -O cpsc368_proj.sql`` to download our SQL file into the database.
2. After entering into SQL Plus, run ``@cpsc368_proj.sql`` to commit the tables to the database (note that you only need to do this once; everytime you access the database following this action, the tables will already be committed).





