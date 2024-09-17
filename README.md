# Employee Management System - Java OOP Concepts

This project demonstrates the basic Object-Oriented Programming (OOP) concepts in Java using a simple Employee Management System. The project contains two classes in the `Employee` package:

1. `Employee.java`: This class defines an employee with private attributes such as `firstName`, `lastName`, `salary`, and `email`. It includes getter and setter methods to access and modify these attributes, demonstrating **Encapsulation**.

2. `EmployeeRunner.java`: This class contains an `ArrayList` of `Employee` objects. It prints the details of each employee, showcasing how to work with **Objects** and **Collections** in Java.

## OOP Concepts Used

### 1. Encapsulation:
Encapsulation is achieved by making the data members (`firstName`, `lastName`, `salary`, and `email`) of the `Employee` class private and providing public getter and setter methods for accessing and modifying them. This restricts direct access to the fields and ensures data integrity.

### 2. Classes and Objects:
- **Class**: The `Employee` class represents a blueprint for an employee.
- **Object**: Instances of the `Employee` class are created to represent individual employees. These instances are stored in an `ArrayList` in the `EmployeeRunner` class.

### 3. Abstraction:
Although not fully demonstrated here, abstraction is partially achieved by using meaningful methods in the `Employee` class to interact with the employee's data, hiding the internal details of how data is stored and accessed.

## Project Structure

EmployeeManagementSystem/

│   ├── Employee.java           # Employee class with private attributes and getter/setter methods

│   ├── EmployeeRunner.java     # Runner class with ArrayList to store and print employee details

├── README.md                   # Project documentation
