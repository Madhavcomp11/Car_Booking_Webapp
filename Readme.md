Sample Car Booking Application
The Sample Car Booking App is a web application built with Java (Spring Boot) and Angular that allows users to book cars for rent. It supports two types of users: Customers and Dealers.

User Roles
Dealer
Dealers can add cars for various outlets/locations.
Dashboard features include:
Adding, editing, deleting, and updating cars.
Searching, sorting, and paginating through their car listings.
Customer
Customers can browse and book cars listed by any dealer.
Dashboard features include:
Viewing and filtering available cars with search, sort, and pagination options.
A "Book Now" button for each car to facilitate bookings.
Shared Features
Both Customers and Dealers can view their bookings and manage their profiles from the sidebar menu after logging in.
Technology Stack
Backend: Spring Boot
Frontend: Angular
UI Components: Angular Material for enhanced user experience, including sidebar, cards, tables, and dialogs.
Pre-requisites
Ensure you have the following installed before running the application:

JDK (version 8.0)
Maven (version 3.3)
MySQL Server (version 8)
Node.js (version 10.16.0 LTS)
Angular CLI (version 8.0.0 LTS)
Running the Application
API Server
Start the MySQL server.
Update the MySQL root credentials in carbooking/api/src/main/resources/application.yml.
Create a database named carbooking in MySQL.
Build and run the application.
Docker Instructions
To run the application in a Docker container:

Build the Docker image.
Run the Docker container.
UI Application
Open a command prompt or terminal.
Navigate to the project directory.
Install dependencies.
Start the Angular application.
Accessing the Application
The application will be accessible at: http://localhost:4200/
