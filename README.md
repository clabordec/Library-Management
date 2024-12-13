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
1. T-SQL
    - Core language for database querying and procedural logic.
    - Used for creating stored procedures, triggers, functions, and views to support the banking system's operations.
    - Ensures optimized query performance and secure data handling.

2. SQL Server 2016
    - Relational database engine chosen for its robustness, security, and performance.
    - Features utilized include:
        - High Availability (HA) and disaster recovery (DR) with Always On Availability Groups.
        - Transparent Data Encryption (TDE) to secure sensitive financial data.
        - Advanced indexing strategies to handle large volumes of transactional data efficiently.

3. SQL Server Integration Services (SSIS)
   - Automates ETL (Extract, Transform, Load) processes for seamless data integration.
   - Utilized for importing/exporting data across systems and maintaining data consistency.
   - Supports automated batch jobs for regular updates.
  
4. SQL Server Reporting Services (SSRS)
    - Provides detailed, real-time financial and operational reports.
    - Enables management to make informed decisions using interactive dashboards and parameterized reports.

<br>

## Usage
- Day-to-Day Operations:
  - Use the IMS dashboard to monitor inventory levels, restocking needs, and sales trends.
  - Schedule daily/weekly reports to keep stakeholders informed.

- Data Integration:
  - Automate data imports from external systems using pre-configured SSIS packages.

- Advanced Reporting:
  - Leverage SSRS to customize and drill down into specific inventory metrics.
 
<br>

## Directory Structure
```graphql
Library_Management\
├── T-SQL_Scripts\
│   ├── Schema\
│   ├── Procedures\
│   ├── Triggers\
├── SSIS_Packages\
├── SSRS_Reports\
├── PowerShell_Scripts\
├── Documentation\
│   ├── UserGuide.pdf
│   ├── ArchitectureDiagram.png
```

## Contact
Name: Chaanyah Laborde <br>
Email: chaanyahlaborde@gmail.com <br>
LinkedIn: [Chaanyah Laborde](https://www.linkedin.com/in/claborde/) <br>
