# Payroll & Leave Management System (Java + MySQL)

Java + MySQL application to manage employee payroll and leave records. Automates salary calculation with deductions and attendance tracking; provides quick, structured reporting.

## Features
- Employee, leave, attendance, and payroll management
- Auto salary computation (basic + allowances − deductions)
- Simple reports: monthly payroll, leave balance, attendance summary
- JDBC DAO layer, input validation, clear error handling

## Tech Stack
- Java 17, Maven, JDBC, MySQL 8
- JUnit (tests), Git

## Setup
1. Create DB and load schema:
   ```bash
   mysql -u root -p < sql/schema.sql
   mysql -u root -p < sql/seed.sql
# Payroll-and-Leave-Mgmt.-System
