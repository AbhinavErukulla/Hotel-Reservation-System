# Hotel Reservation System

This is a simple hotel reservation system implemented in Java. It allows users to search for available rooms, make reservations, and view booking details.

## Features

- Search for available rooms
- Make a reservation
- View booking details

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher. You can download it from [Oracle's website](https://www.oracle.com/java/technologies/javase-downloads.html).

### Project Structure

├── src
│ ├── HotelReservationSystem.java
│ ├── Room.java
│ └── RoomType.java
└── build


### Installation

1. Clone the repository or download the source code.

	sh
git clone https://github.com/AbhinavErukulla/HotelReservationSystem.git

Navigate to the dictionary

	cd HotelReservationSystem

Compilation

	javac -d build src/*.java

Running the Application

	java -cp build HotelReservationSystem

Usage

Upon running the application, you will see a menu with the following options:

1. Search for available rooms
2. Make a reservation
3. View booking details
4. Exit
Enter your choice: 

-->Search for available rooms: Lists all available rooms that are not booked.
-->Make a reservation: Prompts you to enter a room number to book. If the room is available, it will be booked.
-->View booking details: Lists all rooms that are currently booked along with their details.
-->Exit: Exits the application.