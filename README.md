# Library Management System

## Overview
The Library Management System is a comprehensive database solution designed to streamline the management of library operations, including cataloging books, managing patrons, issuing and returning books, and tracking overdue items. Built with Microsoft SQL Server 2016, this system leverages the power of SQL Server's suite of tools, including T-SQL, SQL Server Integration Services (SSIS), and SQL Server Reporting Services (SSRS), to deliver a robust and scalable solution for library administration.

<br>

## Features
- Book Management: Maintain a comprehensive catalog of books, including title, author, genre, ISBN, and availability status.
- Patron Management: Track patron information such as membership details, borrowing history, and account status.
- Transaction Management: Manage book loans, returns, and overdue fines efficiently.
- Reporting: Generate insightful reports on library usage, popular books, overdue items, and more using SSRS.
- Data Integration: Seamlessly import and export data using SSIS to ensure interoperability with other systems.

<br>

## Tools & Technologies
1. SQL Server 2016
    - Core database engine for robust data storage and management.
    - Advanced query optimization for high performance.
2. T-SQL (Transact-SQL)
    - Implements complex business logic through stored procedures, functions, and triggers.
    - Optimizes database performance with custom indexing and query tuning.
3. SQL Server Integration Services (SSIS)
    - Automates data migration and transformation tasks.
    - Ensures seamless integration of external datasets into the library system.
4. SQL Server Reporting Services (SSRS)
    - Provides dynamic and interactive reports for library administrators.
    - Includes dashboards to monitor library operations and key performance indicators (KPIs).

<br>

## Installation & Setup
1.Database Setup
    - Open SQL Server Management Studio (SSMS).
    - Execute the provided LibraryManagementSystem.sql script to create the database schema.

2. SSIS Integration
    - Deploy the SSIS package provided in the DataIntegration/ directory.
    - Schedule SSIS jobs for periodic data import/export tasks.

3. SSRS Configuration
    - Open the SSRS Report Manager.
    - Upload the report files from the Reports/ directory.
    - Assign appropriate permissions to access reports.

4. Testing
    - Populate the database with sample data using the SampleData.sql script.
    - Verify database operations by running sample queries provided in the documentation.

<br>

## Contact
For questions, feedback, or support, please reach out to:

Name: Chaanyah Laborde
Email: chaanyahlaborde@gmail.com
LinkedIn: [My LinkedIn](https://www.linkedin.com/in/claborde/)
