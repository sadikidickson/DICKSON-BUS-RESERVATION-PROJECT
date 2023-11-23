# DICKSON-BUS-RESERVATION-PROJECT
This is a Bus Reservation System written in C. The program allows users to view the list of buses, book tickets, cancel bookings, and check the status of buses.

## Features
- View Bus List: Displays a list of available buses with details such as bus number, source, destination, days of operation, and departure times.
- Book Tickets: Allows users to book tickets by selecting a bus and entering the number of tickets they want to book.
- Cancel Booking: Enables users to cancel a booked ticket by entering the bus number and seat number.
- Bus Status Board: Displays the current status of each seat in a selected bus.
- Login: Users must log in with a username and password to access the reservation system.

## Files
- `bus_reservation.c`: The main C source code file containing the implementation of the bus reservation system.
- `tr1.txt`, `tr2.txt`, `tr3.txt`, `tr4.txt`, `tr5.txt`: Text files storing the number of available seats for each bus.
- `status*.txt`, `number*.txt`: Text files storing the status and seat numbers for each booking.

## How to Run
1. Compile the program using a C compiler (e.g., GCC).
   ```bash
   gcc bus_reservation.c -o bus_reservation
   ```
2. Run the compiled executable.
   ```bash
   ./bus_reservation
   ```

## Usage
Follow the on-screen instructions to navigate through the menu options. Log in with the provided username and password to access the reservation system features.

