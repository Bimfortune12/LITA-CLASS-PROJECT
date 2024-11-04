# LITA_CLASS_PROJECT
I am currently a data analyst undergoing training with an Incubator Hub. The experience has sharpened my skills in data analysis and visualization. This is where i want to put my first project while learning the Incubator Hub.

### Project Title:SALES ANALAYSIS

### Project Overview
This data analysis project aims to collect and analyze data from various sales performance of the project by analysing the various ways from data received to enchance insight to make reasonable decision and provide insights that will inform business strategies, enhance operational efficiency and analytic efficiency that will execute business processess,manage business processess to improve customer satisfaction by evaluate business processess which will enchaces insights gotten to know different transaction categories,business strategies and to know all performance from data to  collects and analyzes relevant data to provide the insights gotten into sales trends.

#### Data Sources
The primary Source of data used here is Data Saled.csv and this is an open source of Data or any other repository site.
### Data Set
A data set is a collection of data points.
### Data Generation
Data generation is important because it will determine the values that you will get from your data set. Data generated can either be ;
Structured,Semi structured and Unstructured.
### ETL : Extracting, Transforming and Loading.
The ETL is used for data transformation from a particular structure to data that can be analysed.
### Data Storage
A data can either be stored in the......
premises; that is within the organization and anybody that needs to access the data must be within the organization.
cloud; here data is stored in the ware house and the data can only be retrieved via the internet.

### Tools used

* Microsoft Excel:
  * Data Cleaning
  * Data Analysis
  * Data Visualization
* SQL - Structured Query Language for Quering of Data
* GitHub for Portolio Building
* Power BI

### Data Cleaning and Preparations

In the initial Phase of the Data Cleaning and Preparations, we perform the following action;

* data cleaning
* Handling missing Variable
* Data Cleaning and Formatting

### Exploratory Data Analysis

EDA involved the exploring of the Data to answer some questions about the Data such as;

* What is the Overall Sales Trend?
* Which product are Top Sellers?
* What are the products on Peak sales?

###  Data Visualization

### REGION BY REVENUE,Top 10 STORES BY REVENUE AND TOP 5 MARKET BY REVENUE

### PIVOT TABLE:	

![image](https://github.com/user-attachments/assets/829c1fed-3293-4acf-871a-8a29d61abcef)

 
![image](https://github.com/user-attachments/assets/94c927e4-632d-41ff-aeca-ec1e9d839ac4)


![image](https://github.com/user-attachments/assets/b2139409-0fb1-4819-a5a3-77630a0f90e9)


![image](https://github.com/user-attachments/assets/e5cf2a01-47c2-409c-b1c5-5af22d2e89dc)



## REGION BY REVENUE

- FILTERED CHART FOR THE YEAR 2014

![image](https://github.com/user-attachments/assets/cd6ec74b-6d58-4063-8472-6486f734e166)

 
### General Revenue 
The graph shows a decline in revenue across some region and also an increase in some region too.North East and South West are the highest performing region while North West and NORTH Central are the lowest performing region.
* North East: The chart shows that it's the highest revenue and strong market presence by having highest customer demand.
* South West: This region still perform significatly but could not meet North East performance.
* North West: This shows drop from the other region.It;s an underperforming region not like performing region
* North Central: This region appears to have the weakest market,the lowest.It's need an improvement and market development to meet up.

* The pivot table also shows the 10 Top stores by revenue other are not performing well.Also Top 5 market by revenue to the the market that is performing well in the market. in conclusion the data shows that the organisation experience it;s strongest performancein Noth East while it's gets reducing from South West,South South,South East,North West and North Central which was the lowest performing region there was low performance due to market size and customer demand.


### SQL - Structured Query Language for Quering of Data:
 * SQL(Structured Ouery Language) it is used for storing and managing data in Relational Database management system(RDBMS)
 * It's a standard Language for Relational Database System,it enabless user to relate databases and table.
 * SQL is a programming Language and aquery language.
 * ALL the RDBMS like MYSQL,POSTGRE SQL.ORACLE, MS ACCESS and SQL SERVER use SQL as their standard database language
 * SQL allows users to query database in a number of ways using English like statement.
SQL follows the following rules:This is not case sensitive.Generally keywords of SQL are written in uppercase.
* Using the SQL staetement,you can perform most of the actions in database.
* What is the Database: A database is an organised collection of data that is stored and managed in structured way to allow for easy access,
  retrieval and manipulation.Database store data in structured format using table which composed of rows and columns.

 ### Basic SQL COMMAND
 SQL commands are instruction.It is used to connunicate with the database.It is also used to perform specific tasks function and queries of data.
 *TYPES OF SQLCOMMANDS:
 There are five types of SQL command:
 * DDL: Data Definition Language:(CREATE,ALTER,DROP and TRUNCATE)
 * DML: Data Manipulation Language:(INSERT, UPDATE,DELETE)
 * DCL: Data Control Language:(GRANT and REVOKE )
 * TCL: Transaction Control Language:(WHERE CLAUSE)
 * DQL: Data Query Language:(COMMIT,ROLLBACK and SAVE POINT)
## SQL KEYS: In SQL keys are special fields in table that help:
- Create relationships between tables
- Maintain uniqueness
- Ensure data is consistent and valid.
 There different ypes of keys:They are as follows:
- Super Key
- Database key
- Foreign Key:A field in one table that uniquely identifies a row of another table, creating a relationship between the two tables.
  Example: Employee_id in the Salary table is a foreign key (FK) that references the Employee_id in the Employee table 
  (PK)
- Surrogate Key:A surrogate key is a unique identifier for each record in a table, typically created by the database itself (e.g an auto Incincrementing integer)
- Composite key
- Primary Key:A special type of key that uniquely identifies each record in a table. Each table can have only one primary key.
  Example: Employee_id in the Employee table.
- Alternate Key:Alternate key is a candidate key, currently not selected as a primary key of the table
   Example: License_Number and Passport_Number
- Candidate Key:Candidate key is a key of a table which can be selected as primary key. A table can have multiple candidate keys, out of 
  which one can be selected as a primary key. 
  Example: Employee_id, License_Number, and Passport_Number.
  ### SQL Operators
  An SQL operator is a reserved words or a character used primarily in an SQL statement's WHERE clause to perform 
  operation(s), such as comparisons and arithmetic operations. These Operators are used to specify conditions in an SQL 
  statement and to serve as conjunctions for multiple conditions in a statement
  ###  SQL Clauses
  SQL clauses are essential components of SQL (Structured Query Language) that define how queries interact with the 
  database. They are used to specify conditions, modify data, and control how results are returned. Here’s an overview of 
  some of the most common SQL clauseS.
  ### Group BY Clause
  SQL GROUP BY statement is used to arrange identical data into groups. 
  • The GROUP BY statement is used with the SQL SELECT statement. 
  • The GROUP BY statement follows the WHERE clause in a SELECT statement and precedes the ORDER BY clause. 
  • The GROUP BY statement is used with aggregation function
  ### Having Clause
  • HAVING clause is used to specify a search condition for a group or an aggregate. 
  • Having is used in a GROUP BY clause. If you are not using GROUP BY clause then you can use HAVING function like a 
    WHERE clause
  ### Order BY 
  • The ORDER BY clause sorts the result-set in ascending or descending order. 
  • It sorts the records in ascending order by default. DESC keyword is used to sort the records in descending order.
  ### WRITING QUERY
  Below was the query written in the class by creating an employee table using Varchr to create staffID, Second Name, Gender Using Primary by inserting into 
  eMPLOYEE(STAFFID,FIRSTNAME,SECONDNAME,GENDER,DATE OF BIRTH,HIREDDATE)How to drop table,delete SQL command,truncate sql command truncate table employee.Also create 
  another table to insert into employee tableto crate a salary table.
  * We are taught how to import data into SQL by first of all you create a database and give it a name and right click on itthen click on task then click on import flat 
  file if your data is on csv but if it is on excel click onimport data then click on next it will take you to location of files to imported then click on browse and 
  choose files.


   [Uploading LITA_DB QUERY.sql…]()create database LITA_DB

   CREATE TABLE Employee (
   staffid varchar (10) not null,
    FirstName varchar (255) NOT NULL,
   SecondName varchar (255),
   Gender varchar (10),
   Date_of_Birth date,
   HireDate datetime,
   primary key (staffid)
   )

   select * from Employee

  insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
  values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
  ( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
  ( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
  ( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
  ( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
  ( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
  ( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
  ( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
  ( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')

   -------to drop table --------

     drop table employee

   ----delete sql command--

    delete from employee
    where staffid  = 'ab281'

  ----truncate sql command

  truncate table employee

   ------identity in SQL -----

  CREATE TABLE PERSON (
  personid int identity (1,1)
  primary key not null,
  personname varchar (255) not null,
  age int,
  )

  insert into PERSON (personname, age)
  values ('saidu', 45),
  ('adebanjo', 49),
  ('olorunda', 33),
  ('martha', 88),
  ('sandi', 100),
  ('jackson', 22),
  ('okunola', 19),
  ('esther', 45)

   select * from PERSON
  
   ### HOW TO USE SUM, COUNT, MAX, MIN, AVERAGE-

  SELECT SUM(Salary) AS TOTALSALARY FROM Salary

  SELECT AVG(Salary) AS AVERAGESALARY FROM Salary

  SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE

  SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary

  ### Analysis on Employee table

  select * from Employee

  select count(*)  from employee 
  where state_of_origin  = 'Kano'

  select count(*)  from employee 
  where gender  = 'male'

 select * from Salary

  select count(*)  from Salary
  where department  = 'Human Resources'

  select top 5 * from Salary

   select * from Salary
  where salary > 700000

  select Staffid, salary from Salary
  where salary < 700000


  select max(salary) from Salary

  select min(salary) as min_salary from Salary

-
  ###  HOW TO GROUP BY

  SELECT COUNT(*)  FROM Payment
  where Payment_Method = 'cASH'

  select count(staffid) as StaffPerSate, state_of_origin from Employee
  GROUP BY State_of_Origin
 
  select count(staffid), department from Salary
  group by department
 
  ### HOW TO USE HAVING

  select count(staffid) as StaffPerSate, state_of_origin 
  from Employee
  GROUP BY State_of_Origin
  HAVING COUNT(staffid) >=3
 
 ### HOW TO USE ORDER BY
 select count(staffid) as StaffPerSate, state_of_origin 
 from Employee
 GROUP BY State_of_Origin
 order by  count(staffid) desc
 
 ### HOW TO SORT BY COLUMN INDEX
 select count(staffid) as StaffPerSate, state_of_origin 
 from Employee
 GROUP BY State_of_Origin
 order by  1 desc
 

### HOW TO USE DIFFERENT TYPE OF JOIN

 * INNER JOIN
 * LEFT JOIN
 * RIGHT JOIN
 * FULL JOIN

 SELECT * FROM EMPLOYEE
 SELECT * FROM SALARY
 SELECT * FROM PAYMENT 

 -----JOIN 2 TABLES----------------

  --EMPLOYEE  =  7 COLUMNS ( STAFFID, FIRSTNAME, GENDER, HIREDATE, STATE)
  --SALARY  = 6 COLUMNS (DEPARTMENT, SALARY)

     select     employee.staffid, 
                employee.firstname, 
		employee.gender,
		employee.hiredate,
		employee.state_of_origin, 
		Salary.department,
		Salary.salary
   from employee
   join Salary
   on salary.Staffid = employee.staffid

-------inner join----------------

    select   employee.staffid, 
                employee.firstname,
		employee.gender,
		employee.hiredate,
		employee.state_of_origin,
		Salary.department,
		Salary.salary
   from employee
   join Salary
   on salary.Staffid = employee.staffid

 ---- ---------left join---------------------
      select  employee.staffid, 
              employee.firstname, 
	      employee.gender,
	       employee.hiredate,
	        employee.state_of_origin, 
		Salary.department,
	         Salary.salary
    from employee
    left join Salary
    on salary.Staffid = employee.staffid

 --------------right join---------------
      select employee.staffid, 
             employee.firstname, 
             employee.gender,
	     employee.hiredate,
	     employee.state_of_origin, 
	     Salary.department,
		alary.salary
   from employee
   right join Salary
    on salary.Staffid = employee.staffid

 ---------------full join---------------------

           Select employee.staffid, 
                employee.firstname, 
		employee.gender,
		employee.hiredate,
		employee.state_of_origin, 
		Salary.department,
		Salary.salary
   from employee
   full join Salary
   o n salary.Staffid = employee.staffiD
   
  ## This is an example of CASE WHEN HOW TO USE IT
   update Employee
    set StateOfOrigin =
    case 
    when Staffid = 'AB200' THEN 'Delta'
    when Staffid = 'AB212' THEN 'Lagos'
    when Staffid = 'AB223' THEN 'Oyo'
    when Staffid = 'AB234' THEN 'Bauchi'
    when Staffid = 'AB240' THEN 'Port Harcourt'
    when Staffid = 'AB249' THEN 'Lagos'
    when Staffid = 'AB254' THEN 'Edo'
    when Staffid = 'AB260' THEN 'Ekiti'
    when Staffid = 'AB268' THEN 'Delta'
    when Staffid = 'AB270' THEN 'Lagos'
    when Staffid = 'AB278' THEN 'Kano'
    when Staffid = 'AB281' THEN 'kano'
    when Staffid = 'AB282' THEN 'Ekiti'
    when Staffid = 'AB286' THEN 'Lagos'
    when Staffid = 'AB298' THEN 'Delta'
    when Staffid = 'AB299' THEN 'Edo'
    when Staffid = 'AB401' THEN 'Oyo'
    when Staffid = 'AB405' THEN 'Delta'
    ELSE 'Unknown'
    End

  ### GitHub for Portolio Building
 
 
  ### Power BI
  * Power BI is a business analytics tool by misrosoft that provides interactive visualization and business intelligence capabilities with a simple interface for end users 
    to create reports and dashbords.The main components of Power BI is Power BI Desktop(for report creation).Power BI Service(for sharing and collaboration)and Power BI 
    Mobile( for viewing reports on mobile.







 









 





























































































































  
  
  
  
  
  
















 







