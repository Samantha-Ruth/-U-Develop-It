# U-Develop-It

## Description

This project uses a combination of node, inquirer package, npm console.table, SQL, and mysql2 to create an accessible database.

This project was a great introductionto SQL.  I practiced creating schemas and seed files, as well as learning the SQL language, using join to create database tables and other queries to edit and delete the data.  I also worked with npm inquirer again, as well as learned about creating a connection to the server using constructors.  


## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Links](#links)
* [Questions](#questions)

## Installation

If the user already has node installed on their device, they can download this project and run "npm init" and then "npm install --save inquirer@^8.0.0 (** please note: newer versions of inquirer will not work properly with this program!), and then npm install console.table --save.  After this, install --save mysql2. In order to protect passwords, the user will also want to "install dotenv" as well. 

In order to access the mysql2 shell,  the user needs to create a .env file with the following, replacing <username> and <user password> with the users own username and password: 
  
DB_NAME=ecommerce_db

DB_USER= < username >

DB_PASSWORD= < user password >


To ensure the user is connected to the correct database, navigate to the root folder of the project, and then open the mysql2 shell and enter "source db/schema.sql".  Then enter "source db/seeds.sql" to seed the database file. Exit the mysql2 shell by entering "exit" into the command line.

Finally, connect the server by entering "npm start" into the command line.

## Usage

This is a voting app to pick a new president for an imaginary group named "U Develop It".  This project developed the backend relational database for this voting application.  The user can pick the individual they would like to be president and cast a vote for them on this application.  The user can then view how many votes each candidate has received and with which parties they are affiliated. 

## Links


Link to video of project:


The url of the Git repository is here: https://github.com/Samantha-Ruth/U-Develop-It


## Questions

If you have any questions about the repo, open an issue or you can find more of my work at (https://gitHub.com/Samantha-Ruth).


