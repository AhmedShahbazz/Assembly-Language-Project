# Restaurant Management System

This Restaurant Management System is an assembly language program designed to run on MS-DOS operating systems. It offers a simple interface for managing restaurant menus and processing customer orders. The system supports different roles, including admin and customer, each with specific functionalities such as viewing menus, placing orders, and admin access to manage and view stored data.

## Features

- **User Authentication**: Secure admin login to access sensitive data.
- **Menu Viewing**: Different menus for Breakfast, Lunch, Dinner, Drinks, Snacks, and Sweets.
- **Order Management**: Users can place orders and view their total bill.
- **File Handling**: Reading from and writing to files to store user data and order details.
- **Data Management**: Admins can read data stored in files to view customer orders and other relevant information.

## Prerequisites

To run this program, you will need:
- An MS-DOS environment (or a compatible emulator like DOSBox).
- An assembler like NASM, MASM, or TASM to compile the assembly code.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/restaurant-management-system.git
   cd restaurant-management-system
   
2. **Compile the Code**
   Use your preferred assembler to compile the code. For example, if you are using MASM,
   ## you might run:
   ```bash
   ml /Fl /Sn /Zi /DMASM /FeRestaurant.exe main.asm

1. **Run the Program**
   ```bash
   Restaurant.exe


## Usage

Start the Program: Run the executable to start the program.
Choose User Type: Select whether to log in as Admin or as a Customer.
Admin: Requires a password. After login, you can view and manage data.
Customer: Browse through various food menus, place orders, and view bills.


## File Structure
main.asm: The main assembly file containing all the logic.
data/: Directory containing text files for user data, menu details, etc. (ensure you create this if it doesn't exist).
README.md: This file.

## Contributing
Contributions to the Restaurant Management System are welcome. Please ensure to update tests as appropriate.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
