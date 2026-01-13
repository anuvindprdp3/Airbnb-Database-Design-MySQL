# Airbnb-Database-Design-MySQL

📌 Project Title

Airbnb Reservation and Review Database Design (MySQL)

📖 About the Project

This project was developed as to focus on designing and implementing a relational database for Airbnb’s core reservation and review functionality.

Airbnb is an online marketplace that connects hosts, who list properties, with guests, who book these properties for short- or long-term stays. The goal of this project was to reverse engineer Airbnb’s booking and review system by analyzing the website workflow and translating it into a structured database design.

The project covers only the reservation and review processes, as defined in the assignment scope, and excludes payment processing, messaging, and other advanced features.

🎯 Project Objectives

The main objectives of this project were:

To analyze Airbnb’s guest and host workflows

To identify key entities, attributes, and relationships

To design an Entity Relationship Diagram (ERD)

To implement the ERD as a physical database schema in MySQL

To populate each table with sample data

To ensure the database follows proper relational design principles

🧠 Assumptions Followed

The following assumptions were strictly followed as per the guidelines:

Guests register using an email-based account

A user cannot be both a guest and a host

Guests can leave reviews about hosts

Hosts can leave reviews about guests

Only confirmed bookings are stored

Any functionality not explicitly mentioned is considered out of scope

🗂️ What I Did in This Project
1. Requirement Analysis

I studied the Airbnb website and provided screenshots to understand how guests search for properties, how bookings are made, and how reviews are submitted.

2. Entity Identification

Based on the analysis, the following main entities were identified:

Guest Login

Host Login

Properties

Booking

Review

Each entity was assigned appropriate attributes based on functional dependencies observed from the website.

3. ER Diagram Design

An Entity Relationship Diagram (ERD) was created using MySQL Workbench, defining:

Relationships between guests, hosts, properties, bookings, and reviews

Proper primary keys and foreign keys

Correct cardinalities (one-to-many relationships)

4. Physical Database Implementation

The ER model was forward-engineered into a MySQL database, where:

Tables were created following the required naming convention

Primary and foreign key constraints were enforced

Referential integrity was maintained

5. Data Population

Each table was populated with at least 10 records, demonstrating realistic Airbnb booking and review scenarios.

6. Documentation

Screenshots of:

The ER diagram
<img width="975" height="680" alt="image" src="https://github.com/user-attachments/assets/1ada1cf9-a400-44f0-83bf-301dd5ba2ad1" />


Table structures

Table data

were captured and compiled into a Word document as required.

🧱 Database Tables Overview

Guest_Login – Stores guest account details

Host_Login – Stores host account details

Properties – Contains property listings created by hosts

Booking – Tracks confirmed reservations made by guests

Review – Stores mutual reviews between hosts and guests

🛠️ Tools & Technologies Used

MySQL Workbench

MySQL Server

Microsoft Word (for documentation)

GitHub (for version control and portfolio showcase)
