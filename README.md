# LibraryConsoleApp
+
+Description:
+This is a console-based Library Automation System developed in the C programming language. It is designed to track and manage books in a small library.
+This project serves as a practical application of foundational computer science concepts, specifically focusing on basic data management, user input handling, memory structures, and function design.
+Upon initialization, the program comes pre-loaded with 50 existing books to allow for immediate testing and interaction. 
+
+ Features:
+ The application is entirely menu-driven , utilizing a do-while loop and switch-case structures for navigation. Users can perform the  +following operations: 
+ -Add a Book: Prompts the user for an ID and verifies it against the existing database. If the ID is unique, the user can input the book's title, author, and publication year to add it to the library; if the ID exists, it returns a "book already exists" error.
+ -Delete a Book: Prompts for a book ID, iterates through the records, and deletes the matching entry.
+ -Borrow a Book: Checks the library for a specific ID. If the book is available, its status is updated to borrowed; if it is already borrowed, the user is notified. 
+ -Return a Book: Takes the ID of a borrowed book and updates its status back to available. 
+ -List All Books: Displays the ID, title, author, publication year, and current status of every book in the library. If the library is empty, it alerts the user.
+ -Search for a Book: Allows users to search the library using multiple filters: ID, Book Title, Author Name, or Publication Year. 
+
+ Technologies & Concepts Used:
+ This project demonstrates proficiency in the following C programming structures: 
+ -struct (Structures): Used for defining the properties of a book (ID, title, author, year, status). 
+ -Arrays: Used for storing and managing the collection of book structures.  
+ -Decision Structures: Extensive use of if/else logic for validation and error handling. 
+ -Modular Functions: Core operations are separated into distinct, reusable functions.  
