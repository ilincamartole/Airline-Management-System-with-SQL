# Airline-Management-System

A robust relational database system designed to handle the complex operations of a commercial airline. [cite_start]This project demonstrates high-level database architecture, from initial conceptual design to **5th Normal Form (5NF)** optimization and advanced SQL analytics[cite: 16, 2251].

## Project Overview
The "Companie Aeriană" system is a comprehensive solution that manages the lifecycle of flight operations. It tracks aircraft maintenance, global routes across multiple continents, passenger bookings with integrated luggage tracking, and specialized crew scheduling.

## 🛠 Tech Stack
* **Database Engine:** Oracle SQL 
* **Normalization:** 1NF through 5NF & BCNF 
* **Logic:** Complex Joins, Subqueries, Views, and Analytical Functions 

## Database Architecture
The system is built on **17 interconnected tables** designed to ensure zero data redundancy and maximum referential integrity .



### Key Modules:
* **Operations:** Aircraft fleet management (`AERONAVA`) and flight scheduling (`ZBOR`).
* **Logistics:** Global geography tracking from Continents down to specific Airport terminals .
* **Human Resources:** Specialized staff tracking for Pilots (by license type), Flight Attendants, and Medical Staff.
* **Customer Experience:** Tiered loyalty accounts (`CONT_CLIENT`) and detailed luggage management (`BAGAJ`).

## Advanced SQL Features
This project highlights professional-grade SQL implementation, including:

* **Relational Division:** Identifying "Super-Users" who have booked flights on every available route.
* **Top-N Analysis:** Extracting high-value clients based on complex scheduling logic (e.g., overnight flights).
* **Complex Reporting:** A multi-table `VIEW` (`v_rezervari_extinse`) that provides a human-readable summary of the entire reservation ecosystem.
* **Data Integrity:** Automated primary key generation using 6 custom SQL Sequences [cite: 381-385].


