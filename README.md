# Connecting HTML Registration Form to Database using PHP

This project demonstrates how to connect an HTML registration form to a MySQL database using PHP. It consists of two main files:

- **`index.php`**: This file contains the frontend part where users can fill out their registration details.
- **`insert.php`**: This file handles the backend database connection and inserts the submitted data into the database.

## Project Structure
/Registration 
│
├── index.php
└── insert.php

## Requirements

Before you begin, ensure you have the following:

- A web server (like Apache or Nginx) with PHP support.
- MySQL database server installed.
- PHP extensions for MySQLi enabled.

- Or Xampp Server

  ## Setup Instructions

1. Clone the Repository
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

2. Create Database
   CREATE DATABASE database_name;
   USE databae_name;

3. Create the table_name
   CREATE TABLE table_name (
   id INT(11) AUTO_INCREMENT PRIMARY KEY,
   name VARCHAR(100) NOT NULL,
   age INT(3) NOT NULL,
   gender ENUM('Male', 'Female') NOT NULL,
   address VARCHAR(255) NOT NULL,
   email VARCHAR(100) NOT NULL);

4.  Configure Database Connection
    $servername = "localhost"; // Database server
    $username = "root";         // Database username
    $password = "";             // Database password
    $dbname = "registration";   // Database name

5.  Access the Registration Form
    http://localhost/index.php

# Explanation of Sections

- Title: Clearly states the purpose of the project.
- Project Structure: Provides a quick overview of the files included in the project.
- Requirements: Lists the prerequisites for running the project.
- Setup Instructions: Detailed steps for setting up the project, including database creation and configuration.
- Usage: Brief explanation of how to use the form.






