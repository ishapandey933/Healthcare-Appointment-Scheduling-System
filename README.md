
# Student Health Centre Booking System

![Student Health Centre Booking System](https://via.placeholder.com/150)

## Description

The **Student Health Centre Booking System** is a web-based application designed to streamline the management of GP appointment bookings at a student health center. This system allows users to check appointment availability, book, cancel, and view pending appointments with their designated GPs. Additionally, the system includes an administration interface for managing bookings, GPs, and patient data, with future improvements planned to enhance data management by replacing foreign keys with their corresponding values.

## Features

- **User Interface**:
  - Check appointment availability.
  - Book, cancel, and consult appointments.
  
- **Administration Interface**:
  - Manage GPs, patients, and bookings.
  - Future enhancements planned for improved data management.

## Technology Stack

- **Backend**:
  - C#
  - ASP.NET Framework
  - LINQ to SQL
  - Forms Authentication security

- **Frontend**:
  - HTML, CSS, Bootstrap
  - jQuery
  - ASP.NET AJAX

- **Database**:
  - SQL Server
  - MySQL

## Getting Started

### Prerequisites

- Visual Studio (configured)
- Microsoft SQL Server
- Microsoft SQL Server Management Studio Express

### Installation

1. **Clone the Repository**:  
   Clone the repository to your local machine or download the zip file and extract it.

2. **Database Setup**:
   - Open Microsoft SQL Server Management Studio.
   - Create a new server and a new database named `StudentHealthCenter`.
   - Import the provided `.sql` file into the `StudentHealthCenter` database.

3. **Project Configuration**:
   - Open the project in Visual Studio.
   - In the `Web.config` file, replace the `ConnectionString` value (`Data Source=MARIA-PC\SQLEXPRESS`) with your server name.

4. **Run the Application**:
   - Debug the project files in Visual Studio.
   - Press the 'Start' button to run the web application.
