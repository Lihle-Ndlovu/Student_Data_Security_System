### Student_Data_Security_System

#### Overview
This is an SQL-based project designed to demonstrate secure data handling, user access control, and data protection techniques in a database environment. The system focuses on enforcing security best practices such as role-based access control, permission management, and secure querying of sensitive student information.

#### Project Objectives
* Implement secure data storage for student records
* Demonstrate user authentication and authorization in SQL
* Apply role-based access control (Admin, Lecturer, Student roles)
* Protect sensitive data using SQL permissions and constraints
* Showcase secure query handling and restricted access views

#### Security Concepts Implemented
* Data Layer → Stores student records and academic information
* Security Layer → Implements roles, permissions, and access rules
* Access Layer → Uses SQL views to expose only authorized data
* User Layer → Admin, Lecturer, and Student roles with different privileges

Security Design Approach
Role-Based Access Control (RBAC)
Users are grouped into roles based on responsibilities:
Admin → Full system access
Lecturer → Can view and update academic data
Student → Read-only access to limited personal data
Audtior → Read-only 
Analyst sees:
aggregated fact table only

#### Skills Demonstrated
* SQL Database Security Design
* Role-Based Access Control (RBAC)
* User Privilege Management (GRANT / REVOKE)
* Secure Data Modeling & Separation of Duties
* Data Protection & Access Restriction Strategies
