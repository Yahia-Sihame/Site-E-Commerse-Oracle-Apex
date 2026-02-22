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




## 🚀 How to Run & Test the Project

Follow the steps below to deploy and test the system on your Oracle APEX environment.

---

### 1️⃣ Prerequisites

Before starting, make sure you have:

- Access to an **Oracle APEX Workspace**
- An **Oracle Database 19c (or higher)** instance
- Required privileges to create tables, triggers, and sequences

---

### 2️⃣ Database Setup

1. Log in to your Oracle APEX Workspace.
2. Navigate to:  
   **SQL Workshop → SQL Scripts → Upload**
3. Upload the file:

/database/database_schema.sql

4. Run the script.

This will automatically create:

- All required tables  
- Primary & Foreign key constraints  
- Sequences  
- PL/SQL Triggers  

Once completed, your database structure will be fully configured.

---

### 3️⃣ Application Import

1. Go to:  
   **App Builder → Import**
2. Upload the application export file located in:

application

3. Follow the installation wizard.
4. Select your target schema.
5. Complete the installation process.

After installation, the application will be ready to run and test.

---

### ✅ System Ready

Once both steps are completed successfully, you can launch the application from App Builder and start testing all features including:

- Product Management  
- Order Processing  
- Data Integrity Automation  
- Backend Logic Execution  
