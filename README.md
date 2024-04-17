# hostel-accommodation-using-mysql
How to create Hostel Accommodation System in c++ using MySQL & OOP.

This project is a simple Hostel Management System implemented in C++. It provides functionalities to reserve beds in a hostel, update bed availability, and interact with a MySQL database to store hostel information.

## Prerequisites
- C++ compiler
- MySQL server

## Setup
1. Clone the repository: `git clone <repository-url>`
2. Compile the program using a C++ compiler.
3. Make sure MySQL server is running.
4. Update the database connection details in the code (`HOST`, `USER`, `PW`, `DB`).
5. Run the executable file.

## Features
- Reserve beds for students.
- Update bed availability.
- Interaction with a MySQL database to store hostel information.

## Usage
1. Run the executable file.
2. Choose from the options displayed:
    - Option 1: Reserve Bed
    - Option 2: Exit
3. If you choose to reserve a bed:
    - Enter student name.
    - If a bed is available, it will be reserved, and the student will be prompted to pay the fee.
    - If no beds are available, a message indicating the unavailability will be displayed.
4. If you choose to exit, the program will terminate.
