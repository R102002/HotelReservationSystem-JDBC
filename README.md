# Hotel Reservation System

## Overview

This Java project implements a simple Hotel Reservation System using JDBC (Java Database Connectivity) to interact with a MySQL database. The system allows users to perform various operations related to hotel reservations, such as reserving a room, viewing reservations, getting room numbers, updating reservations, and deleting reservations.

## Features

1. **Reserve a Room:**
   - Users can reserve a room by providing guest name, room number, and contact number. The reservation details are stored in the "reservations" table in the database.

2. **View Reservations:**
   - Users can view the current reservations stored in the database. The system displays reservation details in a tabular format, including reservation ID, guest name, room number, contact number, and reservation date.

3. **Get Room Number:**
   - Users can retrieve the room number for a specific reservation by providing the reservation ID and guest name. The system queries the database and returns the corresponding room number.

4. **Update Reservations:**
   - Users can update an existing reservation by providing the reservation ID. They can change the guest name, room number, and contact number. The system updates the reservation details in the database.

5. **Delete Reservations:**
   - Users can delete a reservation by providing the reservation ID. The system removes the reservation from the database.

6. **Exit:**
   - Users can exit the system, and a farewell message is displayed.

## Technologies Used

- Java
- JDBC (Java Database Connectivity)
- MySQL

## Setup Instructions

1. **Database Configuration:**
   - Create a MySQL database named "hotel_db."
   - Update the `url`, `username`, and `password` variables in the `HotelReservationSystem` class with your database connection details.

2. **Run the Application:**
   - Compile and run the `HotelReservationSystem` class to start the Hotel Reservation System.

3. **Use the System:**
   - Follow the on-screen menu to perform various operations in the Hotel Reservation System.

## Important Notes

- Ensure that the MySQL JDBC driver (`mysql-connector-java`) is included in the project's classpath.

## Additional Information

- This project is a basic implementation and can be extended to include additional features and improvements.
- For security reasons, consider using prepared statements to prevent SQL injection vulnerabilities.
- Handle exceptions and errors gracefully to enhance the robustness of the system.
