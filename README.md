Parking Management System

1. Project Title

Parking Management System

2. Introduction

The Parking Management System is a simple project developed to manage vehicle parking information.

It helps to store vehicle details, parking slot details, entry and exit times, parking duration, and parking history.

The system makes parking management easier and helps to keep parking records in an organized way.

3. Objectives

The main objectives of this project are:

- To store vehicle details.
- To manage available parking slots.
- To record vehicle entry and exit.
- To calculate parking duration.
- To maintain parking history.
- To display parking information clearly.
- To reduce manual work in parking management.

4. Features

The main features of the system are:

4.1 Vehicle Details

Stores information such as:

- Vehicle Number
- Vehicle Type
- Owner Name

4.2 Parking Slot

Manages:

- Slot ID
- Slot Number
- Slot Status

4.3 Entry and Exit

Records:

- Entry Date
- Entry Time
- Exit Date
- Exit Time

4.4 Parking Duration

Calculates the total time for which a vehicle is parked.

4.5 Parking History

Stores completed parking records for future reference.

5. System Process

The basic process of the system is:

1. Start the system.
2. Enter vehicle details.
3. Check available parking slots.
4. If a slot is available, assign the slot.
5. Record the vehicle entry date and time.
6. Store vehicle and parking details.
7. When the vehicle exits, enter the vehicle number.
8. Retrieve the entry time.
9. Record the exit date and time.
10. Calculate the parking duration.
11. Make the parking slot available.
12. Store the completed details in Parking History.
13. Display the parking information.
14. Stop the system.

6. Entities Used

The system contains the following main entities:

VEHICLE

- Vehicle_Number – Primary Key
- Vehicle_Type
- Owner_Name

PARKING_SLOT

- Slot_ID – Primary Key
- Slot_Number
- Slot_Status

PARKING_RECORD

- Record_ID – Primary Key
- Vehicle_Number – Foreign Key
- Slot_ID – Foreign Key
- Entry_Date
- Entry_Time
- Exit_Date
- Exit_Time
- Parking_Duration

PARKING_HISTORY

- History_ID – Primary Key
- Record_ID – Foreign Key
- Vehicle_Number
- Slot_ID
- Entry_Time
- Exit_Time
- Parking_Duration

7. Relationship

The main relationships are:

- VEHICLE has PARKING_RECORD.
- PARKING_SLOT is used in PARKING_RECORD.
- VEHICLE is assigned to a PARKING_SLOT.
- PARKING_RECORD is stored in PARKING_HISTORY.

8. Project Requirements

Software Requirements

- Operating System: Windows / Linux / Android
- Programming Language: C / suitable programming language
- Database: MySQL / Oracle / suitable database
- IDE: Any suitable programming IDE

Hardware Requirements

- Computer or Laptop
- Keyboard
- Mouse
- Minimum 4 GB RAM
- Basic storage space

9. Advantages

- Easy to manage parking information.
- Saves time.
- Reduces manual record keeping.
- Makes parking slot management easier.
- Keeps parking history organized.
- Helps to find vehicle records quickly.

10. Future Enhancements

The project can be improved by adding:

- Online parking slot booking.
- Automatic fee calculation.
- QR code-based parking.
- Digital payment.
- Admin login.
- SMS or notification system.
- Search and report generation.
- Real-time parking slot availability.

11. Conclusion

The Parking Management System provides a simple way to manage vehicles and parking slots. It records vehicle entry and exit details, calculates parking duration, updates slot availability, and maintains parking history.

This project demonstrates the basic concepts of database management, system design, algorithms, flowcharts, and ER diagrams.

12. Project Type

BCA Mini Project

Project Name: Parking Management System
