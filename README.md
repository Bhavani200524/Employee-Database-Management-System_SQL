# Employee-Database-Management-System_SQL
A simple Employee Database Management System built using MySQL with table creation, data insertion, update, and query operations.

This project demonstrates basic database operations using MySQL.

## Features
- Create Employee Table
- Insert Employee Records
- Update Employee Details
- Manage Department Information
- Perform SQL Queries

## Technologies Used
- MySQL

## Database Operations
- CREATE DATABASE
- CREATE TABLE
- INSERT INTO
- UPDATE
- ALTER TABLE
- SELECT Queries

##CODE
create database bhavani;
use bhavani;
CREATE TABLE employee(
emp_id INT PRIMARY KEY,
ename VARCHAR(30),
job_desc VARCHAR(20),
salary INT );
INSERT INTO employee VALUES(1,'bhavani','ADMIN',10000000);
INSERT INTO employee VALUES(2,'sunny','MANAGER',12200);
INSERT INTO employee VALUES(3,'srujana','HR',100230000);
INSERT INTO employee VALUES(4,'venu','SALES',103400000);
INSERT INTO employee VALUES(5,'sathosh','DEVELOPER',133000000);
INSERT INTO employee VALUES(6,'Sneha','ADMIN',13000000);
INSERT INTO employee VALUES(7,'Tanmayee','HR',133000000);
INSERT INTO employee VALUES(8,'Nithya','SALES',330000000);
INSERT INTO employee VALUES(9,'Sunil','ADMIN',34000000);
INSERT INTO employee VALUES(10,'Sandhya','DEVELOPER',210000000);

#select * from  employee where job_desc="MANAGER" and salary>1100000;
#select *from employee where salary between 100000 and 1200000;
#select *from employee where emp_id not in (1,3,5,6);
#select *from employee where ename like "A_i%"
#select *from employee where ename like "__v__"

#select * from employee where ename like "_i__" limit 5;
select * from employee;
alter table employee add column branch varchar(10);
update employee set branch="chennai" where ename="jhon";

set sql_safe_updates=0;

## Learning Outcomes
- SQL Query Writing
- Database Management
- Table Design
- Data Manipulation
- MySQL Workbench Usage
