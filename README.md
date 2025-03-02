Employee Management Application
This is a simple Employee Management application built with ASP.NET Core MVC and Entity Framework Core. It allows you to perform basic CRUD (Create, Read, Update, Delete) operations on employee records.

Features

List Employees: View all employees in a table.
Add Employee: Add a new employee with name, position, and salary.
Edit Employee: Update an existing employee's details.
Delete Employee: Remove an employee from the system.
Validation: Ensures all fields are filled correctly (e.g., salary must be a positive number).
Technologies Used

ASP.NET Core MVC: For building the web application.
Entity Framework Core: For database operations.
SQLite: As the database (can be replaced with SQL Server, PostgreSQL, etc.).
Bootstrap: For styling the user interface.
Getting Started

Prerequisites

.NET SDK (version 6.0 or later).
A code editor (e.g., Visual Studio Code or Visual Studio).
Installation

Clone the repository:
bash
Copy
git clone https://github.com/shahad-jeza/EmployeeManagement.git
Navigate to the project directory:
bash
Copy
cd EmployeeManagement
Restore dependencies:
bash
Copy
dotnet restore
Apply database migrations:
bash
Copy
dotnet ef database update
Running the Application

Start the application:
bash
Copy
dotnet run
Open your browser and navigate to:
Copy
http://localhost:5000


feel free to contribute 🚀
