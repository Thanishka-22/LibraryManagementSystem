📚 Library Management System (Java Web Application)

📌 Project Description
This is a Library Management System developed using Java Servlets, JDBC, and Oracle Database.
The system allows the librarian/administrator to add books to the library and search/view book details using ISBN.
It follows a layered architecture with Bean, DAO, Service, and Servlet layers.

✨ Features
 Add books to the library
 Search books using ISBN
 View complete book and author details
 Validation for input data
 Oracle database connectivity using JDBC
 Web interface using HTML and Servlets

🛠️ Technologies Used
Java (JDK 8 or above)
Java Servlets
JDBC
Oracle Database (XE)
Apache Tomcat Server
HTML
Eclipse IDE
Git & GitHub

🏗️ Project Architecture
com.kce.library
│
├── bean
│   ├── BookBean.java
│   └── AuthorBean.java
│
├── dao
│   ├── BookDAO.java
│   └── AuthorDAO.java
│
├── service
│   └── Administrator.java
│
├── servlets
│   ├── MainServlet.java
│   └── ViewServlet.java
│
└── util
    └── DBUtil.java
 
🗃️ Database Tables

📘 Author_Tbl
| Column Name | Data Type | Description    |
| ----------- | --------- | -------------- |
| Author_Code | NUMBER    | Primary Key    |
| Author_Name | VARCHAR2  | Author Name    |
| Contact_No  | NUMBER    | Contact Number |

📕 Book_Tbl
| Column Name | Data Type | Description                 |
| ----------- | --------- | --------------------------- |
| ISBN        | VARCHAR2  | Primary Key                 |
| Book_Name   | VARCHAR2  | Book Title                  |
| Book_Type   | CHAR      | G – General / T – Technical |
| Author_Code | NUMBER    | Foreign Key (Author_Tbl)    |
| Cost        | NUMBER    | Book Price                  |


🧪 Modules Implemented

Add Book Module
Search Book Module
View Book Details Module

   ![Screenshot 1](https://github.com/user-attachments/assets/e024b1bc-684a-4764-b14c-d61dd02dda0f)
   ![Screenshot 2](https://github.com/user-attachments/assets/790be958-9608-43f7-87fb-5f2c2b1befcb)
   ![Screenshot 3](https://github.com/user-attachments/assets/465a85aa-5fec-4e4b-8fd3-fdc8082a8f9c)
   ![Screenshot 4](https://github.com/user-attachments/assets/3350adca-49c0-49a0-a889-618c04ec4ce3)



