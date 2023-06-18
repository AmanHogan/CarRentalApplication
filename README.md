# Car Rental Application

This is a simple car rental application implemented using Python and SQLite. It allows users to manage customers, vehicles, and rentals. The application provides functionalities to add new customers, add new vehicles, add new rentals, return rentals, find customers, and find vehicles.

## Prerequisites

- Python 3.x
- SQLite

## Installation

1. Clone the repository or download the source code.
2. Install the required dependencies by running the following command:
   ```
   pip install tkinter
   ```
3. Make sure you have the `p2.db` file in the same directory as the Python script. This file serves as the SQLite database for the application.

## Usage

Run the application by executing the Python script `car_rental.py`. The main GUI window of the application will appear.

### Main Menu

The main menu of the application provides options to modify and find/list information.

#### Modify Menu

- **Add New Customer**: Clicking this button opens a new window where you can add a new customer to the database. Enter the customer's name and phone number, and click "Add Customer" to save the information.
- **Add New Vehicle**: Clicking this button opens a new window where you can add a new vehicle to the database. Enter the vehicle details, such as the vehicle ID, description, year, type, and category, and click "Add Vehicle" to save the information.
- **Add New Rental**: Clicking this button adds a new rental entry to the database.
- **Returns**: Clicking this button opens a new window where you can process the return of a rental.

#### Find/List Menu

- **Find Customer**: Clicking this button opens a new window where you can search for a customer by name or phone number.
- **Find Vehicle**: Clicking this button opens a new window where you can search for a vehicle by its ID.

### Closing the Application

Once you are done using the application, you can close it by clicking the close button on the main window.

## Database

The application uses an SQLite database (`p2.db`) to store customer, vehicle, and rental information. The database file must be present in the same directory as the Python script.

## Notes

- This is a simplified version of a car rental application and may not include all the features you might find in a complete commercial application.
- The application utilizes the Tkinter library for the graphical user interface (GUI).
