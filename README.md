# LIBRARY_MANAGEMENT_SYSTEM
project based on library management system

- create table branch(branch_no int primary key,manager_id int, branch_address varchar(100),contact_no int(10));

- create table employee (emp_id int primary key,emp_name varchar(100), position int,salary decimal);

- create table customer(customer_id int primary key,customer_name varchar(200), customer_address varchar(100),reg_date date);

- create table issuestatus(issue_id int primary key, issued_cust int,foreign key(customer_id) referances