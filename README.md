Step 1:

i) Set up your MySQL database
Install MySQL on your server if you haven't already.
Create a new database and a table to store your form data.

For example: 

CREATE DATABASE mydatabase;

USE mydatabase;

CREATE TABLE mytable (

    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    email VARCHAR(50),
    message TEXT
);

Step 2:

Install XAMMPP server on you system if you haven't already.
Before starting Registering Details start the Apache and MYSQL on XAMMPP Control Pannel.

![Screenshot 2024-03-17 090529](https://github.com/rupasrigithub/Connecting-HTML-Form-With-MYSQL-Database-Using-PHP/assets/140321029/7dfa7550-fa30-410e-8a44-f817c2c76a4a)


