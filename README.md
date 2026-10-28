# DVLD — Driving & Vehicle License Department System

A C# desktop application for managing driving-license-related operations, built using Windows Forms, ADO.NET, SQL Server, and a three-tier architecture.

**Project Type:** Desktop Application  
**Architecture:** Three-Tier Architecture  
**Status:** Portfolio Project  
**Repository:** [DVLD-3Tier-System](https://github.com/mwageh690-cmyk/DVLD-3Tier-System)

## Overview

The DVLD System is designed to organize driver and driving-license administration through a desktop application backed by a relational database.

The project focuses on applying object-oriented programming, database-driven application development, separation of concerns, and layered software architecture to a realistic administrative system.

## Features

The system's feature list should reflect the functionality implemented in the repository. The intended domain includes:

- People and driver record management
- User and account management
- Driving-license application workflows
- License-related operations
- Database-backed record management

Additional workflows, such as test appointments, license renewal, replacement, or international licenses, should be listed here only when their implementation has been verified.

## Technology Stack

- **Language:** C#
- **User Interface:** Windows Forms
- **Framework:** .NET Framework — verify the target version in the project file
- **Database:** Microsoft SQL Server
- **Data Access:** ADO.NET
- **Architecture:** Three-Tier Architecture
- **Development Environment:** Visual Studio
- **Version Control:** Git and GitHub

## Architecture

The application follows a three-tier architecture that separates presentation, business logic, and data access.

### 1. Presentation Layer

Responsible for the Windows Forms user interface, user interactions, and displaying application results.

### 2. Business Logic Layer

Responsible for application rules, validation, and coordinating operations between the presentation and data access layers.

### 3. Data Access Layer

Responsible for database communication and data persistence using ADO.NET and SQL Server.

### Request Flow

```text
User
  |
  v
Presentation Layer
  |
  v
Business Logic Layer
  |
  v
Data Access Layer
  |
  v
SQL Server Database
```

This structure separates responsibilities and makes the application easier to maintain and extend.

## Database

The system uses a relational database to store and manage application data.

Add the verified database details here, including:

- Database name
- Main tables and their relationships
- Primary and foreign keys
- Database setup script or backup file, if included in the repository

## Getting Started

### Prerequisites

- Windows
- Visual Studio with Windows desktop development support
- The .NET Framework targeting pack required by the project
- Microsoft SQL Server
- SQL Server Management Studio (SSMS), recommended for database setup

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mwageh690-cmyk/DVLD-3Tier-System.git
   ```

2. Open the solution file in Visual Studio.

3. Restore any required dependencies.

4. Set up the SQL Server database using the actual database script or backup included in the repository, if available.

5. Configure the application's database connection string for your local SQL Server instance.

6. Set the presentation-layer project as the startup project.

7. Build the solution and run the application.

> The exact database name, script location, startup project name, and connection-string configuration must be confirmed from the repository before these instructions are considered complete.

## Screenshots

Add screenshots of the actual application to demonstrate its functionality.

Recommended screenshots:

- Login screen
- Main dashboard
- People and user management
- License application workflow
- License management screens

## Technical Concepts Demonstrated

- Object-oriented programming with C#
- Windows Forms desktop development
- Three-tier architecture
- Separation of business logic and data access
- SQL Server integration using ADO.NET
- Relational database design
- CRUD operations, where implemented

## Future Improvements

Potential improvements include:

- Automated tests for business logic
- More comprehensive input validation and exception handling
- Improved logging and diagnostics
- Clearer database documentation
- Additional documentation for business rules and workflows

These are potential enhancements, not claims about existing functionality.

## Author

**Mohamed Wageh**

- GitHub: [mwageh690-cmyk](https://github.com/mwageh690-cmyk)

