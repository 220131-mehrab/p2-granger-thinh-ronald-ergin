![Company Logo](https://revature.com/wp-content/themes/revature/imgs/logo-white-color.png "Revature")
# Employee Record App

## Project Description

This project functions as an employee database for HR with simple Employee information modification. 

It provides the functionality required to create new employee records with the data fields of first name, last name, and email address. 

Further functionality includes the ability to update the data fields of employee records and delete employee records from the database. 

Additionally, an email service has been provided to send a precomposed email informing employees of changes to their records. 

## Technologies Used

* Java
* Spring
* HTML
* CSS
* JavaScript
* Angular
* Docker
* PostgreSQL
* REST API


## Features

List of features ready and TODOs for future development
* Create Employee Records
* View List of All Employee Records
* Update Employee Records
* Delete Employee Records
* Automated Email functionality
* Navigation Bar functionality

To-do list:
* Add more data fields to employee records, e.g., employee images
* Implement View Individual Employee details functionality

## Getting Started
   
   For Windows
```bash
$ cd C:/User/user
$ mkdir Employee-Database
$ cd C:/Users/user/Employee-Database
$ git init
$ git clone https://github.com/220131-mehrab/p2-granger-thinh-ronald-ergin-Employee-Management-App--P2
$ cd C:/Users/user/Employee-Databse/p2-granger-thinh-ronald-ergin-Employee-Management-App--P2/AngularSpringBoot
$ gradlew build
$ docker-compose build
$ docker-compose up
$ cd C:/Users/user/Employee-Database/p2-granger-thinh-ronald-ergin-Employee-Management-App--P2/AngularSpringBoot/angular-frontend
$ npm install
$ ng serve
```
For Linux
```bash
$ cd /home/user/
$ mkdir Employee-Database
$ cd home/user/Employee-Database
$ git init
$ git clone https://github.com/220131-mehrab/p2-granger-thinh-ronald-ergin-Employee-Management-App--P2/
$ cd home/user/Employee-Databse/p2-granger-thinh-ronald-ergin-Employee-Management-App--P2/AngularSpringBoot
$ gradle build
$ docker-compose build
$ docker-compose up
$ cd home/user/Employee-Database/p2-granger-thinh-ronald-ergin-Employee-Management-App--P2/AngularSpringBoot/angular-frontend
$ npm install
$ ng serve
```

## Usage

Once you have initiated the program you can access it via localhost:4200. 
You will arrive at a page with a navigation bar at the top with links, one to the currently displayed Employee List and one to the Create Employee page. You can Create an Employee by filling out the three entry forms labeled "First Name", "Last Name", and "Email Id". Once the "Submit" button is clicked the new Employee Record will be added to the databse. When this happens, an email will be sent to the entered email address informing the employee of their record being created. Once the information is submitted you will be returned to the Employee List page. Here you will see the newly created record, with two buttons available, one to Update the Employee record and one to Delete the Employee Record. When the Update button is clicked you will be taken to the Update Employee page, here you will be able to reinsert data for the three fields of Employee information. When submitted, the Employee will receive an email informing them of their records update and we will be sent back to the Employee list page. When the Delete button is pressed the selected Employee record will be deleted from the database. 

## Contributors

1. Granger Carty
2. Thinh Pham
3. Ronald Lemus
4. Ergin Bostanci


## License

This project uses the following license: [<license_name>](<link>).

