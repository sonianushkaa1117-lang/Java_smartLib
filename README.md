SmartLib - Campus Library Management System

A Java Console-Based Campus Library Management System created as the Build your own project (BYOP) for the Java Object-Oriented Programming course at VIT. SmartLib implements a library circulation desk using core Java OOPs concepts like inheritance, polymorphism, interfaces, recursion, reflection, nested classes, anonymous classes and enums.


About the Project

SmartLib is a console application that manages a campus library's books, journals, digital media, members, loans, fines and reports. The project uses no external libraries or databases, only CSV files for data persistence.

The application features an interactive menu as well as a demo mode to demonstrate all the capabilities of the software automatically.
---

Features

1) Catalog Management

- Add new books, journals and digital media
- Auto-generate item IDs
- Search catalog by keyword, category or custom filter
- Update and remove catalog items
- View catalog summary by type and category

2) Member Management

- Register new members with email validation
- Membership tiers:

BASIC
SILVER
GOLD
FACULTY
- Loan quota management
- Upgrade membership
- Fine settlement

3) Circulation Management

- Issue library items
- Renew issued items (max 2 renewals)
- Return items and calculate overdue fines
- Detect overdue loans
- Mark lost items

4) Reports

- Catalog dashboard
- Circulation dashboard
- Most issued items
- Recursive category tree
- Reflection-based entity inspector

5) CSV Persistence

- Save library data to CSV files
- Load saved data on application start
- Skip malformed CSV records
---

6) Java OOPs Concepts Used

| Concept | Implementation |
| Classes & Objects | Book, Journal, Member, Loan, LibraryItem |
| Inheritance | Book, Journal & DigitalMedia extend LibraryItem |
| Polymorphism | Different loan periods and fine rates for each item type |
| Abstraction | Abstract `LibraryItem` class |
| Interfaces | Borrowable, Searchable, FinePolicy |
| Method Overloading | Search, Issue, Return methods |
| Method Overriding | `loanPeriodDays()`, `dailyFineRate()`, `detailLine()` |
| Enums | MembershipTier, ItemStatus |
| Nested Classes | SearchIndex, Stats |
| Anonymous Classes | FinePolicy Strategy |
| Recursion | Category Tree rendering and searching |
| Reflection | Runtime object inspection |
---

Project Structure

```text
SmartLib/
│
├── SmartLib.java
├── data/
│  ├── items.csv
│  ├── members.csv
│  └── loans.csv
├── README.md
└── Project_Report.pdf
```
---

 How to Run

### Compile

```bash
javac SmartLib.java
```

### Run Interactive Menu

```bash
java SmartLib
```

### Run Demo Mode

```bash
java SmartLib --demo
```
---

Sample Menu

```text
========== SMARTLIB MENU ==========
1. Show Catalog
2. Search Catalog
3. Register Member
4. Show Members
5. Issue Item
6. Renew Loan
7. Return Item
8. Reports
9. Reflection Inspector
0. Exit
```
---

Sample Library Data

The application initializes with sample library records including:

Java Books
Algorithms Books
Database Books
IEEE Journal
ACM Journal
Java OOP Digital Lecture Series

It also creates sample members for testing different membership tiers.
---

Sample Output

Catalog listing with availability status.
Member loan quota tracking.
Issue and return transactions.
Automatic fine calculation.
Reports showing utilization and overdue loans.
Recursive category hierarchy.
---

Technologies Used

Language: Java 17+
Platform: Console Application
IDE: VS Code / BlueJ / IntelliJ IDEA
Storage: CSV Files
Version Control: Git & GitHub
---

Learning Outcomes

This project showcases the implementation of Java Object-Oriented Programming concepts through a real-world library management system. It emphasizes clean code, modular design, error handling, reusable components and data persistence without the use of any external frameworks.
---

Course Information

Course: Java Object-Oriented Programming
Project Type: Build your own project (BYOP)
Institute: VIT bhopal
---

Author

Anushka Soni
B.Tech Computer Science Engineering- AIML 
VIT bhopal
