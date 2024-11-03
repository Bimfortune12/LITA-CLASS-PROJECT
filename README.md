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

 create database LITA_DB

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

-----truncate sql command

  truncate table employee

--------12/09/2024----------------------------

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

   ------Insert more records into Employee table-------

  insert into [dbo].[Employee]
  values ( 'AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
  ( 'AB405', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
  ( 'AB282', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
  ( 'AB278', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09'),
  ( 'AB240', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
  ( 'AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
  ( 'AB268', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
  ( 'AB286', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
  ( 'AB270', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09')

   select * from [dbo].[Employee]

  ---- to create second table call SALARY TABLE-------

  CREATE TABLE Salary (
 salary_id int identity (1,1)not null,
 Staffid varchar (255),
 firstname varchar (255),
 lastname varchar (255),
 department nvarchar(max),
 salary decimal (10, 3) ---(10: precision, 3:scale)
 )

 select * from [dbo].[Salary]

 create database LITA_DB

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

-----truncate sql command

truncate table employee

--------12/09/2024----------------------------

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

------Insert more records into Employee table-------

insert into [dbo].[Employee]
values ( 'AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB405', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB282', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB278', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09'),
( 'AB240', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB268', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB286', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB270', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09')

select * from [dbo].[Employee]

---- to create second table call SALARY TABLE-------

CREATE TABLE Salary (
salary_id int identity (1,1)not null,
Staffid varchar (255),
firstname varchar (255),
lastname varchar (255),
department nvarchar(max),
salary decimal (10, 3) ---(10: precision, 3:scale)
)

select * from [dbo].[Salary]


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

-----truncate sql command

truncate table employee

--------12/09/2024----------------------------

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

------Insert more records into Employee table-------

insert into [dbo].[Employee]
values ( 'AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB405', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB282', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB278', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09'),
( 'AB240', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB268', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB286', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB270', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09')

select * from [dbo].[Employee]

---- to create second table call SALARY TABLE-------

CREATE TABLE Salary (
salary_id int identity (1,1)not null,
Staffid varchar (255),
firstname varchar (255),
lastname varchar (255),
department nvarchar(max),
salary decimal (10, 3) ---(10: precision, 3:scale)
)

select * from [dbo].[Salary]

-----insert records into Salary table-------------

insert into salary (staffid, FirstName, lastname, Department, Salary)
values ( 'AB401', 'ayan', 'olakun', 'Information Tech.', 45000.45),
( 'AB212', 'okorie', 'mercy','Account',500000.99999),
( 'AB223', 'joshua', 'chukwuemeka', 'Human Resources',100560.9339999),
( 'AB234', 'sanni', 'ibrahim', 'Sales and Marketing',845688.99),
( 'AB254', 'mercy', 'olanipekun', 'Account',8889.999999),
( 'AB249', 'johnson', 'mercy', 'Information Tech.',234000.90909090),
( 'AB298', 'ayomide', 'halleluyah', 'Logistics', 678000.991999),
( 'AB260', 'deborah', 'justin', 'Logistics',900099.00697969),
( 'AB281', 'wale', 'olanipekun', 'Information Tech',873093.2344)

insert into [dbo].[Salary]
values ( 'AB200', 'ayomide', 'halleluyah', 'Human Resources',45699.8585),
( 'AB405', 'deborah', 'justin', 'Account',898349.900222),
( 'AB282', 'wale', 'olanipekun', 'Sales and Marketing',362636.564848),
( 'AB278', 'shukurat', 'lasisi', 'Logistics',100000.464647),
( 'AB240', 'johnson', 'mercy', 'Information Tech',3855590.9890093),
( 'AB299', 'ayomide', 'halleluyah', 'Account', 8585858.9292),
( 'AB268', 'deborah', 'justin', 'Human Resources',76767.93939)

select * from [dbo].[Salary]

----SUM, COUNT, MAX, MIN, AVERAGE---------------------------------

SELECT SUM(Salary) AS TOTALSALARY FROM Salary

SELECT AVG(Salary) AS AVERAGESALARY FROM Salary

SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE

SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary

-----update--------

update Salary
set salary = 7056999.9994
where Staffid = 'AB401'

-----------------------13/09/2024------------------------

--update staff name-----

select * from [dbo].[Employee]

update employee
set secondname = 'Endurance'
where staffid = 'AB405'

----UPDATE DEPARTMENT-------

select * from [dbo].[Salary]

UPDATE SALARY
SET department = 'Information Tech.'
where Staffid = 'AB234'

UPDATE SALARY
SET department = 'Information Tech.'
where Staffid = 'AB240'

SELECT * FROM Salary
WHERE Staffid = 'AB281'

----CREATE ADDITIONAL COLUMN INTO EMPLOYEE TABLE-------

ALTER TABLE EMPLOYEE
ADD State_of_Origin varchar (50)

select * from employee

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB268'

UPDATE EMPLOYEE
SET State_of_Origin = 'Lagos'
where staffid = 'AB200'

UPDATE EMPLOYEE
SET State_of_Origin = 'Oyo'
where staffid = 'AB212'

UPDATE EMPLOYEE
SET State_of_Origin = 'Delta'
where staffid = 'AB223'

UPDATE EMPLOYEE
SET State_of_Origin = 'Kano'
where staffid = 'AB234'

UPDATE EMPLOYEE
SET State_of_Origin = 'Abuja'
where staffid = 'AB240'

UPDATE EMPLOYEE
SET State_of_Origin = 'PortHarcourt'
where staffid = 'AB249'

UPDATE EMPLOYEE
SET State_of_Origin = 'Abuja'
where staffid = 'AB254'

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB260'

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB268'

UPDATE EMPLOYEE
SET State_of_Origin = 'Abuja'
where staffid = 'AB270'

UPDATE EMPLOYEE
SET State_of_Origin = 'Oyo'
where staffid = 'AB278'

UPDATE EMPLOYEE
SET State_of_Origin = 'Bauchi'
where staffid = 'AB281'

UPDATE EMPLOYEE
SET State_of_Origin = 'PortHarcourt'
where staffid = 'AB282'

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB286'

UPDATE EMPLOYEE
SET State_of_Origin = 'Lagos'
where staffid = 'AB298'

UPDATE EMPLOYEE
SET State_of_Origin = 'Oyo'
where staffid = 'AB299'

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB401'

UPDATE EMPLOYEE
SET State_of_Origin = 'Abuja'
where staffid = 'AB405'

select * from employee

ALTER TABLE EMPLOYEE
ADD State_of_Origin varchar (50)

select * from employee

UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB268'

-----create another table call PAYMENT TABLE------

CREATE TABLE Payment (
paymentid int identity (1,1) primary key,
Account_No bigint not null,
staffid int,
Bank varchar (255) default 'Zenith Bank',
Payment_Method varchar (50) check (Payment_Method = 'Cash' or Payment_Method = 'Transfer')
)

alter table payment
alter column staffid varchar (30)

select * from Payment

insert into Payment (account_no,staffid,payment_method )
values (2033030303, 'AB200', 'transfer'),
(2123459910, 'AB401',  'transfer'),
(2034562240, 'AB254',  'cash'),
(2234556303, 'AB212',  'transfer'),
(2033037703, 'AB249',  'cash'),
(2033030303, 'AB298',  'cash'),
(2455657503, 'AB260',  'transfer'),
(2045595953, 'AB281',  'cash'),
(2033030303, 'AB273',  'transfer'),
(2077778903, 'AB299',  'transfer'),
(2033030301, 'AB286', 'transfer'),
(2123459911, 'AB260',  'transfer'),
(2034562241, 'AB270',  'cash'),
(2234556302, 'AB104',  'transfer'),
(2033037705, 'AB268',  'cash'),
(2033030306, 'AB270',  'cash'),
(2455657509, 'AB300',  'transfer')

insert into Payment
values (2198773830, 'AB299',  'GT bank', 'transfer'),
(2024656569, 'AB405',  'Access bank', 'cash'),
(2222444933, 'AB200',  'Fidelity bank', 'transfer'),
(5674842300, 'AB278', 'Access bank', 'transfer'),
(2222444933, 'AB200',  'GT bank', 'transfer'),
(2034537300, 'AB278', 'Access bank', 'transfer')

------those receive their salary by cash-----

SELECT * FROM Payment
WHERE Payment_Method = 'Cash'

select * from Payment
where Payment_Method = 'TRANSFER'

SELECT COUNT(*)  AS ZenithStaff FROM Payment
where Bank = 'Zenith Bank'

SELECT COUNT(*)  FROM Payment
where Bank = 'GT BANK'

SELECT COUNT(*)  FROM Payment
where Payment_Method = 'Transfer'

---Analysis on Employee table------

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

--------------------------------17/09/2024--------------------------------------------------------

select * from employee
 
select * from Salary
 
--------GROUP BY------------------------------

SELECT COUNT(*)  FROM Payment
where Payment_Method = 'cASH'

select count(staffid) as StaffPerSate, state_of_origin from Employee
GROUP BY State_of_Origin
 
select count(staffid), department from Salary
group by department
 
---------HAVING------------------------------

select count(staffid) as StaffPerSate, state_of_origin 
from Employee
GROUP BY State_of_Origin
HAVING COUNT(staffid) >=3
 
select count(staffid) as staffperdepart, department 
from Salary
group by department
having count(Staffid) >= 2
 
-------order by----------------

select count(staffid) as StaffPerSate, state_of_origin 
from Employee
GROUP BY State_of_Origin
order by  count(staffid) desc

 
select count(staffid) as StaffPerSate, state_of_origin 
from Employee
GROUP BY State_of_Origin
order by count(staffid) asc

-------sort by column index------------
 
select count(staffid) as StaffPerSate, state_of_origin 
from Employee
GROUP BY State_of_Origin
order by  1 desc

select count(staffid) as StaffPerSate, state_of_origin 
from Employee
GROUP BY State_of_Origin
order by 2 asc
 
----Comparison/Relational Operator--------------------
< = less than
> = greater than
<> = not equal
 
select * from Salary
where salary = 100560.934
 
select * from Salary
where salary <> 100560.934
 
select * from Salary
where salary > 100560.934
 
select * from Salary
where salary < 100560.934
 
-------range operators---------------------
Between 
Not Between
 
select * from Salary
where salary between 500000 and 900000
 
select * from Salary
where salary not between 500000 and 900000


----------------19/09/2024----------------

---List operator------------------
--IN
--NOT IN

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME IN ('SANNI', 'DEBORAH', 'MERCY')

SELECT * FROM Salary
WHERE department IN ('ACCOUNT', 'LOGISTICS','HUMAN RESOURCES')

SELECT * FROM Salary
WHERE department NOT IN 
('ACCOUNT', 'LOGISTICS','HUMAN RESOURCES')

----------LOGICAL OPERATORS----------------------
----AND
---OR

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JUSTIN'

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JUSTIN' AND GENDER = 'FEMALE'

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JOHNSON' AND GENDER = 'FEMALE'

----OR

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JUSTIN' OR GENDER = 'FEMALE'

SELECT * FROM  EMPLOYEE
WHERE GENDER = 'MALE' AND DATE_OF_BIRTH <= '1990-01-01'
AND STATE_OF_ORIGIN = 'Ekiti'

SELECT * FROM  EMPLOYEE
WHERE GENDER = 'MALE' AND DATE_OF_BIRTH >= '1990-01-01'
AND STATE_OF_ORIGIN = 'Ekiti'


SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'JOHNSON' OR GENDER = 'GIRL,'

SELECT * FROM EMPLOYEE
WHERE FIRSTNAME = 'FEMI' OR GENDER = 'GIRL,'

-------UPDATE--------

SELECT * FROM Salary

UPDATE Salary
SET FIRSTNAME = 'Emeka'
where Staffid = 'AB212'

UPDATE SALARY 
SET STAFFID = 'AB550' 
WHERE STAFFID = 'AB254'

---SALARY = 5% (0.05)

UPDATE SALARY
SET SALARY = SALARY +(SALARY * 0.05)
WHERE STAFFID IN ('AB200', 'AB268','AB278')

UPDATE SALARY
SET SALARY = SALARY * 1.05
WHERE STAFFID IN ('AB200', 'AB268','AB278')

UPDATE SALARY
SET SALARY = SALARY * (1 + 0.05)
WHERE STAFFID IN ('AB200', 'AB268','AB278')

SELECT * FROM Salary

--------------JOIN-----------------------

INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL JOIN

SELECT * FROM EMPLOYEE
SELECT * FROM SALARY
SELECT * FROM PAYMENT 

-----JOIN 2 TABLES----------------

 --EMPLOYEE  =  7 COLUMNS ( STAFFID, FIRSTNAME, GENDER, HIREDATE, STATE)
 --SALARY  = 6 COLUMNS (DEPARTMENT, SALARY)

 select employee.staffid, 
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

 select employee.staffid, 
        employee.firstname,
		employee.gender,
		employee.hiredate,
		employee.state_of_origin,
		Salary.department,
		Salary.salary
from employee
join Salary
on salary.Staffid = employee.staffid

-------left join---------------------
 select employee.staffid, 
        employee.firstname, 
		employee.gender,
		employee.hiredate,
		employee.state_of_origin, 
		Salary.department,
	    Salary.salary
from employee
left join Salary
on salary.Staffid = employee.staffid

-------right join---------------
 select employee.staffid, 
        employee.firstname, 
		employee.gender,
	    employee.hiredate,
		employee.state_of_origin, 
		Salary.department,
		Salary.salary
from employee
right join Salary
on salary.Staffid = employee.staffid

-----full join---------------------

 select employee.staffid, 
        employee.firstname, 
		employee.gender,
		employee.hiredate,
		employee.state_of_origin, 
		Salary.department,
		Salary.salary
from employee
full join Salary
on salary.Staffid = employee.staffid

------join 3 tables-------------------

select employee.staffid,
       employee.firstname, 
	   employee.gender,
	   employee.hiredate,
	   employee.state_of_origin,
	   Salary.department,
	   Salary.salary,
	   Payment.Account_No,
	   Payment.Bank,
	   Payment.Payment_Method
from employee
inner join Salary
on salary.Staffid = employee.staffid
inner join Payment
on Payment.staffid = salary.Staffid

-------------------
select p.staffid, 
       p.firstname, 
	   p.gender,
	   p.hiredate,
	   p.state_of_origin, 
	   a.department,
	   a.salary
from employee p
join Salary a
on a.Staffid = p.staffid

------union vs union all

create table  LITA_Store_Lekki (
customerID INT not null,
firstname varchar (max),
lastname  varchar (max),
Customer_gender nvarchar(max),
age int,
address varchar (max),
transaction_amount decimal (18, 4)
)

insert into LITA_Store_Lekki(customerID,firstname, lastname, Customer_gender, age, address, transaction_amount)
values (100, 'ramesh', 'abdukl', 'male', 24, '8 ahmed road', 2000.00),
       (121,'khilan', 'delhi', 'female',33, '9 delhi stree, okun', 1500.33),
       (111,'malik', 'delhi', 'female',39, '2 agriiv stree, makunn', 1999.33),
       (110, 'kara', 'ogun', 'male',40, '10 hahroh road, ottawa', 3400.33),
       (109,'sunkanmi','alade','male', 44, '9 orebiyi street, okun', 37575.00),
	   (108,'orobiyi', 'kekerekun', 'male',24, '88 malele road, ijebu', 6500.33),
	   (115,'igbati', 'bunmi', 'male',29, '90 delhi street, abeokunta', 1000.69),
	   (120,'mummry', 'akinbho','female', 25, '9 babaoluwa quarter, ipaha', 9000.50),
	   (119,'latana', 'jerremy', 'male',33, '9 ifelofudn quarter, ado', 15090.35),
	   (108,'orobiyi', 'kekerekun', 'male',24, '88 malele road, ijebu', 6500.33),
	   (111,'malik', 'delhi', 'female',39, '2 agriiv stree, makunn', 1999.33)

select * from LITA_Store_Lekki

create table  LITA_Store_Marina (
customerID INT not null,
firstname varchar (max),
lastname  varchar (max),
Customer_gender nvarchar(max),
age int,
address varchar (max),
transaction_amount decimal (18, 4)
)

insert into LITA_Store_Marina( customerID,firstname, lastname, Customer_gender, age,address, transaction_amount)
values ( 200,'Femk', 'abdukl',  'male',24, '9 old road', 88000.00),
       (201, 'isaiah', 'john','male', 55, '22 alaly stree, okun', 1590.33),
       (206,'emma', 'abu','male', 39, '7 ababa street, makunn', 6788.33),
	   (210, 'kara', 'ogun','female' ,40, '10 hahroh road, ottawa', 3400.33),
	   (211,'sunkanmi', 'osagie', 'female' ,49, '9 agric butstop street, okun', 89875.00),
	   (209,'oge', 'kunle', 'male',88, '10 iwo street, liverpool', 7860.33),
	   (204, 'igbayin', 'elizabeth', 'female',78, '100 kukuma street, epe', 89100.69),
	   (219,'mummry', 'akinbho','female', 25, '9 babaoluwa quarter, ipaha', 9000.50),
	   (220,'latana', 'jerremy','male', 33, '9 ifelofudn quarter, ado', 15090.35),
	   (216, 'marvelous', 'jerremy', 'female',96, '9 jo grey quarter, igbo', 53590.35),
	   (210, 'kara', 'ogun','female' ,40, '10 hahroh road, ottawa', 3400.33),
	   (211,'sunkanmi', 'osagie', 'female' ,49, '9 agric butstop street, okun', 89875.00),
	   (206,'emma', 'abu','male', 39, '7 ababa street, makunn', 6788.33)

select * from LITA_Store_Marina

-------union all------
select * from LITA_Store_Lekki
union all
select * from LITA_Store_Marina

------------union-----------
select  customerID, Customer_gender, transaction_amount
from LITA_Store_Lekki
union 
select customerID, Customer_gender, transaction_amount
from LITA_Store_Marina


select * from LITA_Store_Lekki
union all
select * from LITA_Store_Marina

select 'Lekki Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		   customer_gender as [GENDER],age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
FROM LITA_Store_Lekki
UNION ALL
select 'Marina Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		    customer_gender as [GENDER], age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
from LITA_Store_Marina


-------------------------------------------24/09/2024------------------------------

-------------------SQL VIEWS--------------------------------

select * from employee

create view vw_Employee_tbl
as
SELECT STAFFID, firstname, gender, hiredate from employee

select * from vw_Employee_tbl

create view vw_LITA_Store_transaction_tbl
as
select 'Lekki Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		   customer_gender as [GENDER],age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
FROM LITA_Store_Lekki
UNION ALL
select 'Marina Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		    customer_gender as [GENDER], age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
from LITA_Store_Marina

select * from [dbo].[vw_LITA_Store_Transaction_tbl]

create view vw_LITA_Store_transaction_tbl2
as
select 'Lekki Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		   customer_gender as [GENDER],age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
FROM LITA_Store_Lekki
UNION 
select 'Marina Store' as [BRANCHES], customerID AS [CUSTOMERID],
           firstname as [FIRST NAME], lastname as [LAST NAME], 
		   customer_gender as [GENDER], age as AGE, address as [ADDRESS], 
		   transaction_amount as [TRANSACTION AMOUNT]
from LITA_Store_Marina

select * from [dbo].[vw_LITA_Store_Transaction_tbl2]


create view vw_LITA_Employee_Info 
as
select employee.staffid,
       employee.firstname, 
	   employee.secondname,
       employee.gender,
	   employee.hiredate,
	   employee.state_of_origin,
	   Salary.department,
	   Salary.salary,
	   Payment.Account_No,
	   Payment.Bank,
	   Payment.Payment_Method
from employee
inner join Salary
on salary.Staffid = employee.staffid
inner join Payment
on Payment.staffid = salary.Staffid

select * from [dbo].[vw_LITA_Employee_Info]

-------SQL CASE WHEN-------------------------

SELECT * FROM EMPLOYEE

ALTER TABLE EMPLOYEE
ADD AGE AS DATEDIFF(YEAR, Date_of_Birth, Hiredate) -
   CASE
     WHEN MONTH(Hiredate) < month(Date_of_birth)
	   OR MONTH(Hiredate) = month(Date_of_birth)
	   AND DAY(Hiredate) < DAY(Date_of_birth))
	THEN 1
	ELSE 0
END

-------------
ALTER TABLE EMPLOYEE
ADD AGE AS datediff( year, Date_of_Birth, Hiredate)

SELECT * FROM EMPLOYEE

-----------------26/09/2024----------------------------------

select * from employee

--60 and above = SeniorExecutive
---40 -59 = Senior Manager
--30 and 39 = Manager
--less than 30 =  Assistant Manager

select Staffid, firstname, Gender, state_of_origin, Age,
  CASE
       when Age  >= 60 then 'Senior Executive'
	   when Age between 40 and 59 then 'Senior Manager'
	   when Age between 30 and 39 then 'Manager'
	   when Age <= 29 then 'Assistant Manager'
	 Else 'Unknown'
End as AgeGroup

-----------------26/09/2024----------------------------------
select * from employee

--60 and above = SeniorExecutive
---40 -59 = Senior Manager
--30 and 39 = Manager
--less than 30 =  Assistant Manager

select Staffid, firstname, Gender, state_of_origin, Age,
  CASE
       when Age  >= 60 then 'Senior Executive'
	   when Age between 40 and 59 then 'Senior Manager'
	   when Age between 30 and 39 then 'Manager'
	   when Age <= 29 then 'Assistant Manager'
	 Else 'Unknown'
End as AgeGroup
from [dbo].[Employee]

-----Drop state_of_origin column-------------

ALTER TABLE EMPLOYEE
DROP COLUMN STATE_OF_ORIGIN 

SELECT * FROM EMPLOYEE

---create column stateoforigin----------

ALTER TABLE EMPLOYEE
ADD  StateOfOrigin varchar (255)

select * from employee

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

select * from employee

-----------------International Breweries------------------------

SELECT * FROM [dbo].[InternationalBreweries]

---to get total profit----
select sum(profit) as TotalProfit from InternationalBreweries

---to get totalprofit for senegal------
select sum(profit) as TotalProfit from InternationalBreweries
where countries = 'Senegal'

--to get total for Nigeria in 2019---
select sum(profit) as TotalProfit from InternationalBreweries
where countries = 'Nigeria' and YEARs = '2019'

----
select Brands, sum(profit) as TotalProfit 
from InternationalBreweries
where countries = 'Nigeria' and years = '2017'
Group by Brands
order by 2 desc

select Brands, sum(profit) as TotalProfit 
from InternationalBreweries
where countries = 'Nigeria' 
Group by Brands
order by 2 desc


----to get totalprofit for Hero brands-----
select  sum(profit) as TotalProfitHero 
from InternationalBreweries
where countries = 'Nigeria' and years = '2017' and brands ='Hero'
Group by Brands
---order by 2 desc

SELECT countries,
      CASE
	    WHEN COUNTRIES IN ('Nigeria', 'Ghana') then 'Anglophone'
		 Else 'Francophone'
End as CountriesGroup,
sum(Profit) as TotalProfit from internationalbreweries
where years in ('2017', '2018', '2019')
Group by Countries
order by 3 desc













 









 





























































































































  
  
  
  
  
  
















 







