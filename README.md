# Smart Library Management System

A Java-based desktop library system that manages books, members, borrowing/returns, fines, search, reports, and simple personalized book recommendations.

## Main Features
1. Book management: add, update, delete and search books.
2. Member management: register and manage library members.
3. Issue/return management with due dates and automatic fine calculation.
4. Smart recommendation based on a member's borrowing history.
5. Dashboard/reporting for inventory and circulation statistics.
6. Input validation and exception handling.

## Technology
- Java 17
- Maven
- SQLite
- JDBC
- Java Swing

## Requirements
- JDK 17+
- Maven 3.8+

## Run
```bash
mvn clean compile
mvn exec:java
```

The database file `library.db` is created automatically in the project directory.

## Default workflow
1. Add books.
2. Register members.
3. Issue a book.
4. Return it.
5. Search the catalog or generate recommendations.
6. Open reports to see library statistics.

## Suggested demo data
Books:
- Clean Code — Robert C. Martin — Programming
- Effective Java — Joshua Bloch — Programming
- Introduction to Algorithms — Cormen et al. — Algorithms
- Artificial Intelligence — Stuart Russell — AI
- Database System Concepts — Korth — Database

Members:
- Anushka Dubey
- Demo Student


