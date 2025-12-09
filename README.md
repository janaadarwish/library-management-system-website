# Library Management System

## System Overview
This project represents a Library Management System designed to manage user authentication, book searching, borrowing, favorites, and administrative book management.  
The system supports two roles: **User** and **Admin**, and aims to simplify library operations through a clear and structured design.

---

## System Analysis Diagrams

### 1. Data Flow Diagram (DFD) – Level 0
[View DFD Level 0 (PDF)](diagrams/dfd-lvl-0.pdf)

The DFD Level 0 provides a high-level overview of the system as a single process.  
It shows how data flows between external entities (User and Admin) and the Library Management System, highlighting the main inputs and outputs without internal details.

---

### 2. Data Flow Diagram (DFD) – Level 1
[View DFD Level 1 (PDF)](diagrams/dfd-lvl-1.pdf)

The DFD Level 1 expands the main system into detailed sub-processes such as user authentication, book management, searching, borrowing, and favorites.  
It illustrates how data is processed internally and stored in the database.

---

### 3. Use Case Diagram
[View Use Case Diagram (PDF)](diagrams/usecase.diagram.pdf)

The use case diagram describes the interactions between actors (User and Admin) and the system.  
It defines the main functionalities available to each role, such as registration, login, searching books, borrowing books, managing favorites, and admin book management.

---

### 4. Class Diagram
[View Class Diagram (PDF)](diagrams/class.diagram.pdf)

The class diagram represents the static structure of the system.  
It shows the main classes, their attributes, methods, and relationships, helping to understand how the system is organized internally.

---

### 5. Sequence Diagram
[View Sequence Diagram (PDF)](diagrams/sa_sequence-diagram.pdf)

The sequence diagram illustrates the interaction between system components over time.  
It shows the order of messages exchanged between the user interface, application server, and database during operations such as registration, login, searching, and favorites management.

---

### 6. Activity Diagram
[View Activity Diagram (PDF)](diagrams/sa_activity-diagram.pdf)

The activity diagram represents the workflow of the system.  
It focuses on user and admin actions, decision points, and alternative paths during processes such as login, registration, searching, borrowing, and book management.

---

## Conclusion
These diagrams collectively provide a complete system analysis by explaining the system behavior, data flow, structure, and interactions before and during implementation.
