# Employee Management Application

This is a simple Employee Management application built with ASP.NET Core MVC and Entity Framework Core. It allows you to perform basic CRUD (Create, Read, Update, Delete) operations on employee records.

## Features

- List Employees: View all employees in a table.
- Add Employee: Add a new employee with name, position, and salary.
- Edit Employee: Update an existing employee's details.
- Delete Employee: Remove an employee from the system.
- Validation: Ensures all fields are filled correctly (e.g., salary must be a positive number).

## Technologies Used

- ASP.NET Core MVC: For building the web application.
- Entity Framework Core: For database operations.
- SQLite: As the database (can be replaced with SQL Server, PostgreSQL, etc.).
- Bootstrap: For styling the user interface.

## Getting Started

### Prerequisites

- .NET SDK (version 6.0 or later).
- A code editor (e.g., Visual Studio Code or Visual Studio).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-management.git

2. Navigate to the project directory:
    ```bash
    cd employee-management

3. Restore dependencies:
    ```bash
    dotnet restore

4. Build the application:
      ```bash
      dotnet build

5. Run database migrations:
    ```bash
    dotnet ef database update

6. Start the application:
      ```bash
      dotnet run

feel free to contribute 🚀
