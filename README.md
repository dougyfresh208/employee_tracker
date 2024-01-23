# Employee Tracker
## Description
Employee Tracker is a command-line application to manage a company's employee database, using Node.js, Inquirer, and MySQL. This application allows business owners to view, add, and manage departments, roles, and employees in their company to organize and plan their business effectively.
## Installation

To install this application, you'll need Node.js and MySQL installed on your system.

1. Clone the repository:
  ```bash
    git clone git@github.com:dougyfresh208/employee_tracker.git

    cd employee_tracker
```

2. Install Dependencies:
```
   - npm install
```
3. Set up MySQL Database:

 - Log into your MySQL shell and create the database and tables using the schema.sql file:

```
SOURCE path/to/schema.sql;
```
- Optionally seed the database with initial data:
```
SOURCE path/to/schema.sql;
```
4. Update Database Connection Information:
  - Edit `db.js` with your MySQL user (typically 'root') and password.


## Usage

To start the application, run the following command in your terminal:

```
node app.js
```

Follow the on-screen prompts to view, add, or update departments, roles, and employees.

## Features

- View all departments, roles, employees and the salaries for each role
- Add departments, roles and employees
- Update employee roles


### Links

Github Repository: https://github.com/dougyfresh208/employee_tracker

Demonstration video: https://youtu.be/Nm0sgFM3Y00
