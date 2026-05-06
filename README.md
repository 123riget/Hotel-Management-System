# Hotel Management System ( A CS112 Project)

![C](https://img.shields.io/badge/Language-C-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)
![Academic](https://img.shields.io/badge/Course-CS112-red.svg)

## System Demo
![Hotel System Demo](myrecording.gif)

A comprehensive, console-based Hotel Management System developed in **C** as part of the **CS112** curriculum. This project demonstrates the practical application of modular programming, advanced data structures, and real-time logic handling. 

## Overview 
This application serves as an all-in-one solution for hotel administration. It manages everything from guest registration and room allocation to restaurant billing, parking systems, and employee attendance registers. 

## Key Features 
- **Guest Management:** Create, view, edit, and delete customer record using dynamic memory allocation.
- **Room Booking:** Real-time room availability tracking and automated booking.
- **Restaurant Module:** Integrated food menu with GST calculationg and bill generation.
- **Service Management:** Provisioning for extra services like laundry, room cleaning, and repairs.
- **Parking System:** ID-based vehicle check-in/out with automated fee calculation based on time duration.
- **Checkout Portal:** Date-based stay calculation (including leap year logic) and automated billing.
- **Staff Attendance:** A dedicated register for tracking various hotel employees (Chefs, Security, Managers, etc.)
- **Feedback & Complaints:** A system for guests to record their experience and log issues.

## Technical Stack & Concepts
- **Languages:** C
- **Data Structures:**
  - **Linked Lists:** Used for managing customer records to allow dynamic growth.
  - **Structures (struct):** Heavily utilized for grouping complex data(Guests, Rooms, Services, Billing).
- **Time Library:** Ingetratiion of `<time.h>` for real-time date/time stamping and parking duration logic.
- **Mathematics:** Implementation of leap year logic and GST Calculations.

## Getting Started 

### Prerequisites
- A C Compiler (GCC, MinGW, or Clang)
- Windows OS( The code utilizes `windows.h` and `system("cls")`)

### Installation 
1. Clone the repository:
```bash
git clone [https://github.com/YourUsername/Hotel-Management-System.git](https://github.com/YourUsername/Hotel-Management-System.git)```

2. Navigate to the project directory
```bash
cd Hotel-Management-System
```
### Compilation 
Compile the code using GCC:
```bash
gcc main.c -o HotelManager
```

### Running the App
```bash
./HotelManager
```
## Default Credentials

To access the system, use the following admin credentials:

- Username: `admin`
- Password: `admin123`

## Project Architecture 

- **Single File Implemenation:** The entire system is contained within Project Code CS112.c for easy compilation and portability.
- **Modular Function:** The logic is partitioned into specialized functions(e.g. `Jmain2` for the restaurant, `executeGA` for parking) to maintain readability and seperation of concerns.

