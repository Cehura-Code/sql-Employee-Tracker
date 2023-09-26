# sql-Employee-Tracker

# <h1 align="center">SQL-Employee-Tracker</h1>
Week-12 Challenge (SQL)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

*  [Description](#Description)
          <a name="Screenshots"></a>

*  [Screenshots](#Screenshots)
          <a name="Screenshots"></a>
   
*  [Technologies-Used](#Technologies-Used)
          <a name="Technologies Used"></a> 
          
*  [Installation](#Installation)
          <a name="Installation"></a> 
          
*  [Usage-Information](#Usage-Information)
          <a name="Usage-Information"></a> 
          
*  [License](#License)
          <a name="License"></a>
<h1>Description</h1>
This application lets the users manage the roles, employees and departments in the company. The database is built with MySQL and interacts with JavaScript. 

I have obtained the skills in database seeding when using mySQL and sequelize more clesrly.

<h1>Live Screen Recording of Application Functionality</h1>
*recording of app functionality from local database link goes here 

<h1>Screenshots</h1>
(https://github.com/Cehura-Code/sql-Employee-Tracker/assets/134533516/85e09d4a-3bba-4b6a-a1b1-ef2bdcd7d379)


<h1>Technologies Used</h1>

<h1>Installation</h1>

1.Clone the repository by running the following command: git clone

2.Open the cloned repository in Visual Studio Code. If you do not have Visual Studio Code installed, please install it.

3.Using the terminal, install Node.js version 16. If you have Homebrew installed, you can use the following command: brew install node@16. However, the specific installation command may vary depending on your system, so please refer to the documentation for the correct instructions.

4.Once Node.js version 16 is installed, initialize and create a package.json file where project files will be stored by running the command npm init -y in the terminal.

5 .Install the dependencies associated with this application using the terminal and the npm i command. Developers may need to install dependencies directly from the command line.

<br>To install Sequelize, run the command npm i sequelize.</br>
<br>To install mysql2, run the command npm i mysql2.</br>
<br>To install dotenv, run the command npm i dotenv.</br>
<br>To install Inquirer version 8.2.4, run the command npm i inquirer@8.2.4.</br>
<br>To install Chalk, run the command npm i chalk.</br>


6 .Once all the dependencies are installed, you need to create the database. Navigate to the "db" directory containing the "schema.sql" file using the terminal. Then, open a MySQL shell and run the command source schema.sql to create the database.

7 .After creating the database, you need to seed the database, which will also create the table structure within the database. From the root directory, navigate to the "seeds" folder and run the associated files. This step needs to be done from the root directory because the ".env" file is located there. The commands will be as follows:

To seed the departments: node ./seeds/departments.
To seed the roles: node ./seeds/roles.
To seed the employees: node ./seeds/employees.
Once the database has been seeded, you can run the command npm start from the root directory to start the application.

<h1>Usage Information</h1>

<h1>License</h1>
