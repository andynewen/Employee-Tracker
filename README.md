# Employee-Tracker

## Table of Contents

- [Overview](#overview)
- [Built With](#built-with)
- [Usage](#usage)
- [Contact](#contact)

# Overview

# User Story : 

```
As a business owner
I want to be able to view and manage the departments, roles, and employees in my company
So that I can organize and plan my business
```


## Built With

**3. [MySQL](https://www.npmjs.com/package/mysql) NPM package** : 
* MySQL is an open-source relational database management system.
* A relational database organizes data into one or more data tables in which data types may be related to each other; these relations help structure the data.
* SQL is used by language programmers to create, modify and extract data from the relational database, as well as control user access to the database.

**2. [Node.js](https://nodejs.org/en/)** : 

* Node.js is an open-source and cross-platform JavaScript runtime environment. 

* A Node.js app is run in a single process, without creating a new thread for every request. 

* Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking.

**3. [InquirerJs](https://www.npmjs.com/package/inquirer/v/0.2.3)** :

* Inquirer.js strives to be an easily embeddable and beautiful command line interface for Node.js. 

* NPM package to interact with the user via the command-line.

**4. [console.table](https://www.npmjs.com/package/console.table)** :

* Uses easy-table for printing to console.log

* Used to print MySQL rows to the console.

## Usage


* Clone this repository to use this application on local machine.

* To install necessary dependencies, run the following command :

```
npm i
```

* The application will be invoked with the following command: This will start localhost server on PORT 3000.

```
node server.js
```


## Acceptance Criteria

Here is the Acceptance Criteria for this weeks Challenge.

```
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 


```



## Contact
LinkedIn: https://www.linkedin.com/in/andy-nguyen-b5b356256/
