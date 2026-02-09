#Patient Management System

Patient Management System is a console-based Java application built as a college project using Java (Core + JDBC), MySQL, and Maven. This system allows users to manage patient information and related healthcare data through a menu-driven command-line interface, demonstrating how Java applications interact with a relational database using JDBC.

Project Summary :-
This application enables basic management of patient records and related operations. It is designed to help students learn real-world backend development concepts like database connectivity, CRUD operations, and modular application design using Java and MySQL.

Key Features :-

 •Add new patient records
 •View all patients
 •Update existing patient detail
 •Delete patients
 •Persistent storage using MySQL
 •Menu-based CLI for easy interaction

Tech Stack :-

 •Programming Language: Java
 •Database Connectivity: JDBC (Java Database Connectivity)
 •Database: MySQL
 •Build Tool: Maven
 •Interface: Command Line (CLI)

Project Structure :-

The project follows a modular structure with packages such as:

 •controller – Handles user interaction and navigation
 •dao – Contains Data Access Objects for database operations
 •model – Defines core data models (e.g., Patient)
 •service – Provides business logic for operations
 •util – Contains utility code such as database connection helper

Prerequisites :-

Before running the project, ensure you have:

 •Java JDK 8+
 •Apache Maven
 •MySQL Server

MySQL JDBC Connector dependency added via Maven

What You’ll Learn :-

  •How to use JDBC to interact with a MySQL database
  •Performing CRUD operations in Java
  •Structured application design using DAO and Service patterns
  •Using Maven for dependency and project management
  •Building a CLI-based user interface

Future Improvements :-

  •Add user authentication
  •Introduce role-based access (e.g., admin, staff)
  •Improve error handling and validation
  •Migrate to a GUI or Web UI

Reference Files :-

  •Project Report – Detailed project document included in the repo
  •Tutorial Video – A walkthrough demo of the system
