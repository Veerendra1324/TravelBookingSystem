# TravelBookingSystem

# Travel Booking System

## Overview
The **Travel Booking System** is a simple console-based Java application that allows users to view available travel destinations, make bookings, and view all existing bookings. It demonstrates basic object-oriented programming concepts such as classes, objects, encapsulation, and list management in Java.

## Features
- View available travel destinations
- Book a destination for a registered user
- Display all bookings
- Simple text-based user interface
- Modular design using multiple Java classes and services

## Technologies Used
- Java (JDK 8 or higher)
- Eclipse IDE (recommended)
- Collections Framework (ArrayList)

## Project Structure
```
src/
└── travelbooking/
    ├── User.java
    ├── Destination.java
    ├── Booking.java
    ├── DestinationService.java
    ├── BookingService.java
    └── TravelBookinApp.java
```

### Class Descriptions
- **User.java** – Represents a user with name and email information.
- **Destination.java** – Represents a travel destination with name and price.
- **Booking.java** – Represents a booking made by a user for a specific destination.
- **DestinationService.java** – Provides and manages the list of destinations.
- **BookingService.java** – Handles all booking-related operations.
- **TravelBookinApp.java** – Contains the main method and acts as the entry point of the program.

## How to Run

### 1. Using Eclipse IDE
1. Open Eclipse.
2. Go to **File → Switch Workspace → Other** and create a new workspace if needed.
3. Create a new **Java Project** named `TravelBookingSystem`.
4. Inside `src`, create a **package** named `travelbooking`.
5. Add all `.java` files from this repository to the package.
6. Right-click on `TravelBookinApp.java` → **Run As → Java Application**.

### 2. Using Command Line
1. Open the terminal and navigate to the project folder.
2. Compile all Java files:
   ```bash
   javac travelbooking/*.java
   ```
3. Run the application:
   ```bash
   java travelbooking.TravelBookinApp
   ```

## Sample Output
```
===== Travel Booking System =====
Enter your name: John
Enter your email: john@example.com

===== MENU =====
1. View Destinations
2. Book Destination
3. View All Bookings
4. Exit
Enter choice: 1

--- Available Destinations ---
1. Goa - ₹12000
2. Manali - ₹15000
3. Kerala - ₹18000
4. Ooty - ₹10000
```



## Author
Developed by **C Veerendra** as part of a Java console-based application project.
````
