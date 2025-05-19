Chapter 1: Introduction of Project
1.1 Objective of Project
The objective of the Car Rental Management System is to provide a convenient and efficient platform for customers to rent cars online. It allows users to view available vehicles, book cars for rent, and manage their bookings. The system also provides administrative functionalities for managing vehicles, bookings, and customer information.
1.2 Types of Users
1. Admin
2. Registered Users (Customers)
1.3 Dependency
The system depends on a web server (Apache), PHP interpreter, and a MySQL database server to function properly.
1.4 Methodology Used
Waterfall Model


Chapter 2: Requirement Analysis
2.1 Functional Requirement
• User Registration and Login
• Vehicle Listing and Details View
• Booking and Payment System
• Admin Panel for Vehicle and Booking Management
2.2 Nonfunctional Requirement
• User-friendly Interface
• Secure Authentication
• Reliable Performance
• Responsive Design
2.3 Technology Used
• Frontend: HTML, CSS, JavaScript
• Backend: PHP
• Database: MySQL
• Server: Apache
2.4 H/w Configuration
• Processor: Intel i3 or above
• RAM: 4GB or more
• Hard Disk: Minimum 10GB free space
• Monitor: Minimum 15-inch display
2.5 Graphical User Interface
GUI includes login screens, vehicle listing pages, booking forms, and admin dashboards designed with HTML/CSS and styled for usability.


Chapter 3: Design
3.1 DFD
The Data Flow Diagram (DFD) shows flow between user, admin, database, and car rental operations like registration, booking, and managing cars.

3.2 UML
Use Case Diagram includes actors like User and Admin, with use cases such as login, register, view car, book car, and manage bookings.


Chapter 4: Database Schema
4.1 Table-1: Users
• id (INT, PK)
• full_name (VARCHAR)
• email (VARCHAR)
• password (VARCHAR)
4.2 Table-2: Vehicles
• id (INT, PK)
• title (VARCHAR)
• brand (VARCHAR)
• price_per_day (DECIMAL)
• model_year (YEAR)
• fuel_type (VARCHAR)
• seating_capacity (INT)
4.3 Table-3: Bookings
• id (INT, PK)
• user_id (FK)
• vehicle_id (FK)
• booking_date (DATE)
• status (VARCHAR)



Chapter 5: Conclusion
The Car Rental Management System streamlines the process of renting cars through a digital platform, providing both users and administrators with effective tools to manage their needs.
Chapter 6: References
• www.php.net
• www.mysql.com
• www.w3schools.com
