# LibraryManagementSystem
Use Case: Library Management System
The system manages:

Books

Members

Borrowing transactions

Authors

Categories

It includes 1–1, 1–M, and M–M relationships.
Relationships:
Books → Categories (Many-to-One)

Books ⇄ Authors (Many-to-Many via BookAuthors)

Members → Borrow (One-to-Many)

Books → Borrow (One-to-Many)
