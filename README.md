# ReuStaff — Online Staff Management System

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black" alt="Tomcat" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

## 📌 Project Overview
**ReuStaff** is an enterprise-grade administrative solution designed to streamline staff operations within an educational environment. The system automates critical HR tasks including attendance tracking, leave management, payroll processing, and internal role-based communication.

---

## 🛠️ Tech Stack
*   **Language:** Java (OOP Architecture)
*   **Server:** Apache Tomcat
*   **Database:** MySQL (Managed via MySQL Workbench)
*   **Design Tools:** UML (Use Case, Sequence, and Communication Diagrams)

---

## 🚀 Key Features
*   **Secure Authentication:** Role-based login system with credential validation and password recovery.
*   **Leave Management:** Automated workflow for teachers to request **Medical**, **Half-day**, or **Full-day** leave, with Principal approval/rejection logic.
*   **Payroll Engine:** Dedicated module for the Payroll Officer to calculate basic salaries and bonuses based on real-time attendance data.
*   **Attendance Tracking:** Comprehensive monitoring of staff check-in/out times and historical records.
*   **Resource Management:** Tools for generating school timetables and broadcasting college-wide announcements.

---

## 🏗️ System Architecture & Actors
The system is built on a **Role-Based Access Control (RBAC)** model:

*   **Admin:** Full authority over user account management (CRUD operations).
*   **Teacher:** Manages personal attendance, leave requests, and resource access.
*   **Payroll Officer:** Handles salary computation, pay-slip generation, and payroll inquiries.
*   **Principal:** High-level oversight including leave approval and attendance monitoring.
*   **Supportive Staff:** Responsible for timetable assignments and event management.

---

## 📂 Project Structure
*   **Add Staff Module:** Handles administrator-level user registration and account security.
*   **Payroll Query Module:** Facilitates communication between staff and payroll officers regarding salary discrepancies.
*   **Leave Request Module:** Manages the lifecycle of a leave application from submission to approval.
*   **Login & Security:** Core authentication logic and session management.

---

## ⚙️ Installation & Setup

### 1. Database Configuration
Import the provided `.sql` schema using **MySQL Workbench** to set up the necessary tables and relationships.

### 2. Server Setup
Configure **Apache Tomcat** (v9.0 or later recommended) in your preferred IDE:
*   Eclipse Enterprise Edition
*   IntelliJ IDEA Ultimate
*   VS Code (with Community Server Connectors)

### 3. Deployment
1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/ReuStaff.git](https://github.com/your-username/ReuStaff.git)
    ```
2.  Deploy the project as a **WAR file** or run it directly on the Tomcat server through your IDE.

### 4. Access
Once the server is running, access the system via:
`http://localhost:8080/ReuStaff`

---
> *This project highlights the implementation of Object-Oriented Programming (OOP) principles and Software Engineering methodologies.*
