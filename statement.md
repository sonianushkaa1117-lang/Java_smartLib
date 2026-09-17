SmartLib – Campus Library Management System

1. Problem Statement

A Campus Library requires an efficient method to manage its resources, members, and circulation. 
Manually maintaining the inventory of books, journals, digital media, member data, due dates, and 
fines may become unwieldy as the number of resources and members grow.

SmartLib is a Java-based Campus Library Management System that manages the library 
catalog, members, borrowing, returning, renewals, overdue items, fines, and reports 
via a simple console-based application.

The project showcases practical Java Object Oriented Programming concepts like inheritance, polymorphism, 
abstraction, interfaces, method overloading and overriding, enums, nested classes, anonymous classes, recursion, and reflection.

2. Scope of the Project

The scope of SmartLib encompasses the management of:

• Library catalog (Books, Journals, Digital media)
• Library members, with varied tiers
• Loans, due dates, item availability
• Renewals of active loans, returns, and overdue items
• Calculating and reporting fines
• Generating Catalog and circulation reports
• Storing all data in a CSV-based persistence layer
The system is deployed as a campus-scale console application and leverages the Java Standard Library. 
The system does not utilize an external database or 3rd party libraries.
SmartLib is focused on the day-to-day operations of a Campus Library Circulation desk and is illustrative of 
how OOP concepts can be used to create enterprise software.

3. Target Users

The target users of SmartLib encompass the following:
Library Staff
Library staff users can:
• Manage the library catalog of books, journals, and digital media
• Maintain library members and their details
• Issue and return items
• Renew active loans
• View and manage overdue items and associated fines
• View library catalog and circulation reports
Library Administrators
The administrators can view:
• Catalog utilization and circulation reports
• Member and loan analytics
• Active loans and overdue items
• The state of the library resources (Books, Journals, Digital media)
Students / Library members
The members are represented by the system using their details. The members’ records include:
• Member tiers
• Active loans
• Loan limits
• Fine discounts
The members’ loan and fine details are maintained by the staff.
4. High-Level Features
4.1 Catalog Management
The system allows managing the library catalog of:
• Books
• Journals
• Digital media
Each of the catalog items can be searched for, viewed for availability, updated, or deleted. The system exposes 
catalog search, catalog stats, and catalog item management features.
4.2 Member Management
The system allows managing the library members. This feature encompasses member registration, 
information validation, and maintenance. Additionally, the system supports managing multiple tiers 
of membership, tracking active loans, and applying discounts based on member tiers.
4.3 Loan Management
The system allows issuing of available items as loans to members. Associated due dates are calculated based 
on the item type. Renewals of active loans are enabled, and returned items or overdue items are tracked. 
Additionally, the system tracks the fines accrued on the overdue items.
4.4 Reports and Analytics
This feature encompasses generating reports and analytics on:
• Catalog utilization
• Loans and overdue items
• Fines
• Members and their analytics
• Inventory by category
4.5 Data Persistence
This feature deals with storing and retrieving data from the file system. The system persists the following data:
• Catalog items
• Library members
• Active loans
The data files are stored as CSV files. The system handles malformed CSV data while persisting and retrieving the 
data without losing the entire dataset.
4.6 OOP Demonstration
SmartLib demonstrates the following Object-Oriented concepts:
• Abstract classes
• Inheritance
• Polymorphism
• Interfaces
• Encapsulation
• Method Overloading
• Method Overriding
• Enums
• Nested and anonymous classes
• Recursion
• Reflection
