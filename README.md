# Employee Management System

## Overview

This project is a web-based Employee Management System that allows admins to manage employees and employees to view their personal details and download/print payslips. It is built using Spring Boot for the backend and Thymeleaf for the frontend, with Spring Security handling authentication and role-based access control.

## Features

### Admin
- Add new employees.
- View, edit, and delete employee details.
- Manage employee records through a dashboard.

### Employee
- View personal information through the employee dashboard.
- Download and print the last 6 months’ payslips in PDF format.

## Technologies Used
- **Java (Spring Boot)**: Backend
- **Spring Security**: Authentication & Authorization
- **Thymeleaf**: Frontend templating
- **MySQL** (or any other relational database): Database
- **JavaScript**: Client-side logic for download and print functionality
- **Maven**: Dependency management

## Installation and Setup

### Prerequisites
- **Java 11 or higher**: Ensure you have JDK 11 or later installed on your machine.
- **Maven**: Used for managing dependencies and building the project. You can download it from [Maven's official site](https://maven.apache.org/).
- **MySQL**: A relational database for storing employee data. Make sure it's installed and running.

### Steps to Run the Application

**Clone the Repository:**
   ```bash
   git clone <repository_url>
   cd employee-management-system
