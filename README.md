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
Before start Registering Details start the Apache and MYSQL on XAMMPP Control Pannel.
Lets 'see in the below image
![image](https://github.com/rupasrigithub/Connecting-HTML-Form-With-MYSQL-Database-Using-PHP/assets/140321029/9338ed8c-dfe9-40de-aee0-6dd02bf5320c)

Step 3: 
Step 2: Create an HTML form
Create a new HTML file (index.html for example) with a form that collects the necessary information:
![image](https://github.com/rupasrigithub/Connecting-HTML-Form-With-MYSQL-Database-Using-PHP/assets/140321029/e468d0e3-094b-4555-87d1-46e58e713958)




