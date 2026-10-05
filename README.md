📚 Library Management System

A Library Management System developed in C using Data Structures and Algorithms (DSA). The project is designed to manage book records and issued-book records efficiently using a Doubly Linked List.

📌 Overview

This project provides a simple system for managing books in a library. It allows the user to store, search, update, delete, and organize book information, as well as maintain records of books that have been issued.

The project uses Doubly Linked Lists as the primary data structure, making it possible to dynamically add and remove records without requiring a fixed-size array.

Two separate structures are used:

Book Record Structure – stores information about books available in the library.

Issued Book Record Structure – stores information about books that have been issued to users.

🛠️ Technologies Used

Programming Language: C

Data Structures: Doubly Linked List

Concepts: Structures, Pointers, Dynamic Memory Allocation, Linked List Traversal, Searching, Sorting, Insertion and Deletion

Development Environment: GCC / Any C-compatible compiler

🧩 Data Structures
1. Book Record

The Book Record structure stores details about books available in the library, such as:

Book ID

Book name

Author name

Availability/status

Other relevant book details

Each book record is connected to the next and previous record using a doubly linked list.

NULL ← [Book 1] ⇄ [Book 2] ⇄ [Book 3] → NULL

2. Issued Book Record

A separate structure is maintained for issued books. It stores information related to books that have been borrowed, such as:

Book ID

Book name

Student/User details

Issue information

Other relevant issue details

NULL ← [Issued Book 1] ⇄ [Issued Book 2] ⇄ [Issued Book 3] → NULL


Keeping these as separate structures makes the system easier to organize and maintain.

⚙️ Key Features

Add new books

Display all books

Search for a book

Update book information

Delete book records

Issue books

Maintain issued-book records

Display issued books

Manage book availability

Return issued books

Dynamic memory allocation

Doubly linked list traversal

🧠 DSA Concepts Demonstrated

This project focuses on implementing fundamental DSA concepts in C:

Doubly Linked List

Structures

Pointers

Dynamic Memory Allocation

Insertion

Deletion

Searching

Sorting

Forward and backward traversal

Memory management

The doubly linked list allows records to be dynamically managed without the limitations of a fixed-size array.

📂 Project Structure
Library-Management-System/                                                                                                                                                                                            
│                                                                                                                                                                                                                     
├── main.c                                                                                                                                                                                                            
├── README.md                                                                                                                                                                                                         
└── ...                                                                                                                                                                                                               
                                                                                                                                                                                                                      
The exact file structure may vary depending on the implementation.

🔄 Basic Working

The system maintains two separate linked lists:

             Library Management System
                       │
             ┌─────────┴─────────┐
             │                   │
       Book Records        Issued Records
             │                   │
             ↓                   ↓
      Doubly Linked List   Doubly Linked List


When a book is issued, its relevant information is added to the Issued Book Record list and its availability status in the Book Record list is updated.

When the book is returned, the issued record can be removed and the book's availability can be updated.

🎯 Objective

The main objective of this project is to demonstrate how Data Structures and Algorithms can be applied to solve a real-world problem.

Instead of relying on fixed-size arrays, the project uses dynamic memory allocation and doubly linked lists to efficiently manage library records.

🚀 Future Improvements

Possible improvements include:

File handling for permanent data storage

Login/authentication system

Fine calculation for overdue books

Due-date management

Student/member management

Improved search and sorting algorithms

User-friendly menu interface

Database integration

👨‍💻 Learning Outcome

Through this project, I gained practical experience with:

Implementing doubly linked lists in C

Working with structures and pointers

Dynamic memory allocation

Managing multiple linked-list data structures

Implementing CRUD operations

Applying DSA concepts to a real-world application

📄 License

This project is created for educational and learning purposes.
