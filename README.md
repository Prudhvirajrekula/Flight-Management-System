# Flight Management System in Python

## Overview

The **Flight Management System** is a desktop application developed using Python and Tkinter, providing a graphical user interface (GUI) for managing flight operations. The system is designed specifically for the **admin side**, enabling administrators to efficiently handle various flight-related tasks, such as managing passengers, adding or upgrading flights, displaying flight data, and canceling flights.

This system focuses on **CRUD operations** (Create, Read, Update, Delete) with an integrated search feature, making it user-friendly and easy to operate for administrators. It is an open-source project, and the source code is free to download and use.

## Features

- **Admin Panel**: This Flight Management System is designed for administrative use, where the admin can:
  - Add new flights or update existing flight details.
  - Handle passenger data.
  - View and manage flight records.
  - Cancel flights as needed.
- **CRUD Operations**: Supports all basic CRUD operations, including:
  - **Create**: Add new flights and passengers.
  - **Read**: View and retrieve flight data.
  - **Update**: Modify existing flight and passenger details.
  - **Delete**: Remove flights or passengers.
- **Search Functionality**: Allows admins to search for specific flights, passengers, or flight-related data.
- **Graphical User Interface (GUI)**: Developed using **Tkinter**, the application has a simple and intuitive interface, making it easy to use.

## Prerequisites

- Python 3.x installed.
- Tkinter library for GUI development (usually comes pre-installed with Python).
  
### Required Libraries

To install the necessary libraries, you can use pip (if not already installed):

```bash
pip install tk
```

## Features Walkthrough

### Admin Operations

1. **Manage Flights**: Admin can add new flights, update flight details (e.g., time, seat availability), and cancel flights.
   
2. **Manage Passengers**: Admin can add, update, or remove passenger details and track their status for each flight.

3. **Flight Data**: The system allows the admin to view the full list of available flights, including details like flight number, destination, and capacity.

4. **Search Function**: Admins can easily search for specific flights or passengers based on flight number, destination, or other details.

## Running the Project

1. **Clone or Download the Source Code**:
   - Clone the repository or download the source code as a ZIP file.

2. **Run the Flight Management System**:
   - Navigate to the project directory and run the following command to launch the GUI application:
   
   ```bash
   python flight.py
   ```

3. **Use the Admin Panel**:
   - Upon launching, the admin can use the available options to add, update, or manage flights and passengers.

## Code Structure

- **flight.py**: Contains the main code that powers the Flight Management System, including all functions for handling flight records, passengers, and the GUI.

## Conclusion

The **Flight Management System** is a simple yet effective tool for managing flight-related operations. It allows administrators to perform CRUD operations on flight data and passengers easily through a user-friendly interface built with Tkinter.

This open-source project is ideal for developers learning about Python, Tkinter, and managing data through CRUD operations. It can be expanded or customized to suit more complex requirements in real-world flight management systems.
