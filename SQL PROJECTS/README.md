# This folder contain all works related to Structured Query Lanquage using mysql workbench.
- **EXTENSION**
  - CSV files extentions are the files that will be imported to the database to answere questions on it
  - BACPAC file extention are database that will be imported to sql microsoft server to answer the question.
  - SQL file extention are files that will open on my sql workbench to answer ar veiw the content.
- Structured Query Language (SQL) is a standardized programming language that is used to manage
relational databases and perform various operations on the data in them. Initially created in the 1970s,
SQL is regularly used not only by database administrators, but also by developers writing data integration scripts
and data analysts looking to set up and run analytical queries. 
- **SYNTAX**
  - **SELECT:** This is a syntax that is used to retrive a particular column name
  - **FROM:** This syntax is used to select the table we are workin on the database
  - **WHERE:** This is used to fillter more information based on the condition specify in the where clause
  - **GROUP BY:** This is used when there is an aggregate function in the select statement
  - **HAVING:** This is used in conjuction with group by it is also used to filter information based on the group of statement.
  - **ORDER BY:** This assembles the sql output in either ascending or decending order based on the user decision.
  - **LIMIT:** This will restrict the sql output to the integer value entered by the user.
- **AGGREGATE FUNCTIONS** These are built in funtions that performs some task like counting the numbers of rows, maximum values , summation of values, summation of data. All aggregate functions are always with the bracket opening and closing it without the space between the name 
 of the function and bracket.
  - **count:** This function count the number of rows in a data set  E.g count(age)
  - **count(distinct):** This function return the distinct number value in the data set . E.g count(DISTINCT gender) will return 2.
  - **sum:** This function will return the summation of the selected column E.g sum(age)
  -  **min:** This function return the lowest value in the dataset based on the selected column field name
  -  **max:** This function return the highest value in the dataset based on the selected column field name.
