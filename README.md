# Employee Management System

An Employee Management System is a web application that allows users to manage employee information and their addresses. It provides endpoints for creating, reading, updating, and deleting employees and addresses.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- POSTMAN
- Maven (build tool)

##  Data Flow

* Controller -

  it Will receive request from client and send request to service layer.

* Service -

  it Will receive request from controller and this will manipulate the operation and send send request to DAO layer

* Repository -

  it Will receive request from service and it will communicate with the Database.

* DataBase Design -

  For Database i am using MySQL and created a pogo for user management where i performing CRUD
  operation with user basic information.

##  Data Structure used in project

* DataBase Design -

  In this project mostly used ArrayList & along with java 8 feature like optional class and
  lambda expression.


##  Project Summary


* In UserManagement System i created a Rest APIs with the help of spring boot where we can perform
  CRUD operation with the user information.



## Features

- Create a new employee with their address details.
- Retrieve a list of all employees and their addresses.
- Retrieve an employee's information by their ID.
- Update an employee's information, including their address, using their ID.
- Delete an employee and their associated address by their ID.

## Setup

To run the Employee Management System on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-management-system.git