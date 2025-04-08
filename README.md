# CPSC368: Databases in Data Science Research Project 

##### DataBAES (2025W2)
##### Authors: Olivia Lam & Chloe Zandberg


## About

This proposal examines how gender influences mental health experiences and workplace support in the tech industry. Our research focuses on two questions:
1. How do different genders describe their experiences with mental health support?
2. What is the average work time affected by mental health issues for women in tech?

Through qualitative thematic analysis and quantitative measures, we aim to uncover gendered disparities in mental health support and their impact on work performance, using trusted datasets like the OSMH mental health in tech survey and a general employee burnout dataset.


## Report
The final report can be found here (link the report)!!!!!


## Required Libraries
- pandas: version 2.2.2
- numpy: version 1.26.4
- sqlite3: version 2.6.0
- altair: version 5.5.0


## Project File Descriptions
- cleaning-EDA.ipynb:
  This file is where Chloe and I performed some basic cleaning and conducted some exploratory data analysis to better understand the data we were working with in context of our research questions. We also created and inserted data into our SQL file in preparation for our analysis.
- cpsc368_proj.sql:
  This file contains the mental health data that we used for our project from an SQLite database
- cpsc368_proj.sql:
  This file is the SQL file we created and exported our cleaned data into through a series of INSERT statements

## Report Query Specifications
- After SSHing to the server department, use ``wget https://raw.githubusercontent.com/chloezandberg/cpsc368/main/cpsc368_proj.sql -O cpsc368_proj.sql`` to download our SQL file into the database.





