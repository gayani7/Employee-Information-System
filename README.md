# Employee Information System

A desktop-based Employee Management System developed using Java Swing and MySQL (MariaDB). This application allows users to manage employee records with full CRUD functionality and search capability.

---

##  Features
- Add new employee records
- Update existing employee details
- Delete employee records
- Search employees by name or city
- Display records in JTable
- Auto-refresh table after operations

---

## Technologies Used
- Java (Swing GUI)
- MySQL / MariaDB
- JDBC (Java Database Connectivity)
- NetBeans IDE

---

## Database Structure

`sql

CREATE TABLE employee(
    id INT(10) AUTO_INCREMENT PRIMARY KEY,
    fname VARCHAR(100),
    lname VARCHAR(100),
    city VARCHAR(100),
    phone INT(10),
    salary INT(11)
);

---


## Screenshots

<table>
  <tr>
    <td>
      <img src="Employee system.png" width="600"/>
    </td>
  </tr>
</table>

---

