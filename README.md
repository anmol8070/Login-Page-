# Login Page Project

## Overview

This project is a simple login page developed using HTML, CSS, PHP, and a MySQL database. It is designed to authenticate users with credentials stored in the database. The project runs on XAMPP, a popular open-source cross-platform web server solution stack package.

## Features

- User authentication with PHP and MySQL
- Form validation for secure login
- Responsive design using CSS
- Secure password hashing
- Session management for logged-in users

## Requirements

- XAMPP installed on your local machine
- Basic knowledge of HTML, CSS, PHP, and SQL

## Setup Instructions

1. **Install XAMPP:**
   - Download and install XAMPP .
   - Start the Apache and MySQL modules from the XAMPP control panel.

2. **Clone the Repository:**
   - Clone this repository to your XAMPP `htdocs` directory:
     ```bash
     git clone https://github.com/yourusername/login-page-project.git
     ```
   - Or you can download the ZIP and extract it to the `htdocs` directory.

3. **Create the Database:**
   - Open PHPMyAdmin by visiting `http://localhost/phpmyadmin/`.
   - Create a new database, e.g., `login_db`.
   - Import the `database.sql` file located in the project directory to create the necessary tables.

4. **Configure the Database:**
   - Open the `config.php` file in the project directory.
   - Update the database configuration:
     ```php
     <?php
     $host = 'localhost';
     $db = 'login_db';
     $user = 'root';
     $pass = '';
     $charset = 'utf8mb4';
     ?>
     ```

5. **Run the Project:**
   - Visit `http://localhost/login-page-project/index.php'.
   - Register a new user or log in with an existing account.


