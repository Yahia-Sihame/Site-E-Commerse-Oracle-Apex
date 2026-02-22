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

🚀 Getting Started (How to Run)
Follow these instructions to deploy the project on your local or cloud environment.

📋 Prerequisites
Oracle APEX Workspace: Access to an instance (e.g., apex.oracle.com).

Database Version: Oracle 19c or 21c is recommended for full feature compatibility.

⚙️ Installation Steps
1. Database Schema Setup
First, you need to build the "Engine" of the application by running the DDL scripts:

Navigate to SQL Workshop > SQL Scripts > Upload.

Upload the file: /database/database_schema.sql.

Click Run to generate all tables, sequences, and PL/SQL triggers.

2. Import Application
Next, import the user interface and application logic:

Go to App Builder > Import.

Choose the file: /application/f248114.sql (or your exported filename).

Follow the wizard instructions. Important: Ensure you map the application to the same schema where you ran the database scripts.

3. Execution
Once the installation is complete, click Run Application.

Use your workspace credentials to log in and explore the system.

🛠️ Troubleshooting
[!TIP]
If you encounter any "Table not found" errors, double-check that the database_schema.sql script was executed successfully before importing the application.
