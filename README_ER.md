## Title 
University Enrollment System
## Overview
This project involves creating a relational data model for a university enrollment system, incorporating an Entity Relationship (ER) diagram, a relational model, and the SQL code for table creation. It aims to efficiently manage data related to students, courses, professors, and departments within a university setting.

## Resources
ER Diagrams: Familiarize with ER diagrams through resources like SmartDraw, Lucidchart, and Jack Zheng's Teaching Archive.
Drawing Tools: For creating ER diagrams, consider using draw.io or ERDPlus.

## Entities
Student: Netid, First Name, Last Name, Major, Status (Undergraduate/Graduate)
Course: Course ID, Course Name, Department, Semester, Year
Professor: Netid, First Name, Last Name, Rank, Department
Department: Code, Name, Chairman

## Relationships
Students can enroll in many courses.
Professors can teach and advise many students.
Each department has a chairman who is a professor.

## Submission Components
ER Diagram: A visual representation of entities and their relationships.
Relational Model: A detailed schema of the database structure in 3rd Normal Form.
SQL Code: Scripts for creating the database tables based on the relational model.

## Getting Started
To use this project:
1. Clone the Repository:
2. View the ER Diagram and Relational Model: Open the provided documents to understand the database structure.
3. Database Setup: Run the SQL scripts to create your database schema.