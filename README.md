# Parking Management System

This Parking Management System is a Python-based application designed to manage parking lot operations efficiently. The system allows users to perform operations such as vehicle entry, removal, viewing parked vehicles, checking available spaces, and generating parking bills. It provides a simple command-line interface to interact with the system.

## Features

- **Vehicle Entry**: Registers the vehicle in the parking system with details such as vehicle number, type, name, owner name, date, and time.
- **Remove Entry**: Allows removal of a vehicle from the system.
- **View Parked Vehicles**: Displays a list of all currently parked vehicles with relevant details.
- **View Left Parking Spaces**: Shows the available parking spaces for bicycles, bikes, and cars.
- **Parking Rate Details**: Displays the parking rates for different vehicle types.
- **Generate Bill**: Generates the parking bill based on the vehicle type and duration of parking.
- **User-Friendly Interface**: The system is designed to be intuitive with simple menu options for the user to navigate easily.

## Project Setup

### Requirements

To run this project, you need Python installed on your system. The script uses standard Python libraries, so no additional installations are required.

- **Python**: Version 3.x and above

### How to Run

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/parking-management-system.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd parking-management-system
    ```

3. Run the program:
    ```bash
    python parking_management_system.py
    ```

### Operations Menu

Upon running the program, you will be presented with the following options:

1. **Vehicle Entry**: Enter vehicle details such as vehicle number, type, name, owner name, date, and time.
2. **Remove Entry**: Remove a vehicle from the system by entering its vehicle number.
3. **View Parked Vehicle**: Display all parked vehicles along with details such as vehicle number, type, name, owner name, date, and time.
4. **View Left Parking Space**: View the available parking spaces for bicycles, bikes, and cars.
5. **Amount Details**: View the parking rates for bicycles, bikes, and cars.
6. **Bill**: Generate a parking bill based on the number of hours a vehicle has been parked.
7. **Close Program**: Exit the program and close the application.

### Example of Parking Entry:

When the user selects option 1 (Vehicle Entry), they will be prompted to input various details:

```bash
Enter vehicle number (XXXX-XX-XXXX) - ABCD-12-3456
Enter vehicle type(Bicycle=A/Bike=B/Car=C): B
Enter vehicle name - Intruder
Enter owner name - John Doe
Enter Date (DD-MM-YYYY) - 12-12-2022
Enter Time (HH:MM:SS) - 14:30:00
