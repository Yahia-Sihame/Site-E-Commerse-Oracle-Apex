# 🛒 Oracle APEX E-Commerce System  
### 🎓 Academic Project – Semester 5 (Database Module)  
Developed by **Yahia Sihame**

---

## 📌 Project Context

This project was developed during **Semester 5 (S5)** as part of the **Database Management Module**.

The main objective was not to build a visually advanced interface, but rather to design and implement a strong **database-driven backend system** using Oracle technologies.

The focus was placed on **PL/SQL programming, database architecture, and business logic implementation**.

---

## 🧠 Backend-Oriented Approach

This project emphasizes the “engine” of the application:

- Advanced **PL/SQL procedures and triggers**
- Strong **data integrity constraints**
- Optimized **relational schema design**
- Automated business logic at the database level
- Server-side validation and processing

The front-end uses the default **Oracle APEX Universal Theme**, mainly as a functional interface to test and interact with the backend logic.

---

## 🛠️ Technical Stack

- **Platform:** Oracle APEX  
- **Database:** Oracle Database (19c / 21c)  
- **Languages:** SQL & PL/SQL  
- **Concepts Applied:**  
  - DDL & DML  
  - Triggers  
  - Sequences  
  - Constraints (Primary Key, Foreign Key, Check)  
  - Relational Data Modeling  

---

## 🏗️ Database Design

The schema includes structured and normalized tables such as:

- Products  
- Categories  
- Customers  
- Orders  
- Order Details  

Special attention was given to:

- Preventing orphan records using foreign keys  
- Automating ID generation with sequences  
- Enforcing business rules through triggers  

---

## 🎥 Project Demonstration

https://www.youtube.com/watch?v=PCtQhBAQAvE

---

## 📂 Repository Structure

/database → SQL scripts (Tables, Triggers, Constraints, Sequences)
/application → Oracle APEX application export file


---

## 🎯 Learning Outcomes

Through this project, I strengthened my understanding of:

- Database architecture design  
- PL/SQL procedural programming  
- Backend automation  
- Data integrity enforcement  
- Bridging database logic with web applications


🚀 How to Run & Test
To run this project on your own Oracle APEX instance, follow these steps:

Prerequisites:

Access to an Oracle APEX Workspace (either locally or on apex.oracle.com).

Oracle Database 19c or higher is recommended.

Database Setup:

Go to SQL Workshop -> SQL Scripts -> Upload.

Upload and run the database_schema.sql file located in the /database folder. This will create all necessary tables, triggers, and constraints.

Import Application:

Go to App Builder -> Import.

Upload the .sql file located in the /application folder.

Follow the installation wizard and make sure to associate it with the correct Schema.

Run the App:

Once imported, click the Run Application button.

Log in using your APEX workspace credentials or any custom users defined in the logic.
