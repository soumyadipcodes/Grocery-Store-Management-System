# Grocery-Management-System
This program has been made as a school project using Python and MySQL.

*DataBase*
Database name: grocery_store
Tables: admin_register, employees, invoices, products
1.admin_register
-->fields : id{int}, username{varchar(20)}, password{varchar(50)}
2.employees
-->fields : employee_id{int}, username{varchar(20)},password{varchar(50)}, 
          employee_name{varchar(300)},contact_num{varchar(10)},address{varchar(300)},aadhar_num{varchar(12)}
3.invoices
-->fields : bill_number{int}, date{varchar(20)},customer_name{varchar(300)}, customer_contact{varchar(10)}
4.products
-->fields : product_id{int}, category{varchar(300)},sub_category{varchar(300)}, product_name{varchar(300)},stock_quantity{int}, MRP{int}

*General Instruction*

1.The database is to be created manually as mentioned below.
2.The admin account can only be created manually from the MySQL command line. You will need to at least create one admin account to   
  get started with the system.
3.Host, Username, Password is set to the default value, change it according to your device to connect the program with the database.
-->*NOTE:- There is 19 database connector statement which all need to change according to your device.*
4.Category, Sub-Category, Products are to be manually added to the code as well as normally added to the database to execute further instructions in the system. (To manually add items jump to line no: 1325)
-->*NOTE:- Data added to the database is to be the same as the data entered in the source code. Also, space gap is not allowed in sub-
          categories and products, adding gap may result in an error. Use subtract symbol or underscore instead.*
