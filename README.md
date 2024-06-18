# BusResverationProject
The project allows passengers to book seats on available buses.
Passengers can enter their name, choose a bus number, and specify the booking date.
The system checks if a seat is available on the chosen bus for the selected date.
If a seat is available, the booking is confirmed and added to the bookings list.
If a seat is not available, the passenger is informed that the bus is full, and they can try another bus or date.
The program continues to run until the user chooses to exit.
# Bus Reservation System

This Java-based Bus Reservation System allows users to book seats on various buses based on availability. It consists of three main classes: `Bus`, `Booking`, and `BusDemo`.

## Features
- **Bus Class**:
  - Stores information about each bus, including bus number, whether it's air-conditioned, and its seating capacity.
  - Provides accessor (getter) and mutator (setter) methods for bus attributes.
  - Displays bus information.

- **Booking Class**:
  - Handles booking details, including passenger name, bus number, and booking date.
  - Checks if a booking is available based on the bus capacity and existing bookings.

- **BusDemo Class**:
  - Main class that initializes bus and booking lists.
  - Displays bus information.
  - Allows users to book seats on buses and confirms the booking based on availability.

## Prerequisites
- Java Development Kit (JDK) 8 or above

## Setup Instructions

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/BusReservationSystem.git
   cd BusReservationSystem
   ```

2. **Compile the Java files**:
   ```sh
   javac -d bin src/busResv/*.java
   ```

3. **Run the application**:
   ```sh
   java -cp bin busResv.BusDemo
   ```

## Usage

1. **Initialize Buses**:
   The system initializes with a predefined list of buses:
   - Bus 1: AC, Capacity 2
   - Bus 2: Non-AC, Capacity 50
   - Bus 3: AC, Capacity 48

2. **Display Bus Information**:
   The system displays the information of all available buses.

3. **Booking a Seat**:
   - Enter `1` to book a seat.
   - Provide passenger name, bus number, and date of travel in the specified format (dd-MM-yyyy).
   - The system checks the availability and confirms the booking if seats are available, otherwise informs the user that the bus is full.

4. **Exit**:
   - Enter `2` to exit the application.

## Example

```sh
Bus No: 1 AC: true Total Capacity: 2
Bus No: 2 AC: false Total Capacity: 50
Bus No: 3 AC: true Total Capacity: 48
Enter 1 to Book and 2 to exit
1
Enter name of passenger:
John
Enter bus no:
1
Enter date dd-mm-yyyy
15-06-2024
Your booking is confirmed
Enter 1 to Book and 2 to exit
2
```

## Contributing

1. Fork the repository.
2. Create a new feature branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```sh
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature-branch
   ```
5. Create a new Pull Request.



## Contact

For any questions or issues, please contact mssonasp@gmail.com
