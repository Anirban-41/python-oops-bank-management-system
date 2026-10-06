# python-oops-bank-management-system
A console-based Bank Management System built with Python, OOP, and JSON.
# Python OOP Bank Management System

A console-based **Bank Management System** developed using Python and Object-Oriented Programming (OOP). The project allows users to create and manage bank accounts, perform deposits and withdrawals, view account details, update information, and delete accounts.

Account data is stored persistently using a **JSON file**, so the data remains available even after the program is closed.

## Features

* Create a new bank account
* Deposit money
* Withdraw money
* View account details
* Update account information
* Delete an account
* Account authentication using account number and PIN
* Persistent data storage using JSON
* Automatic account number generation
* Basic input validation and exception handling

## OOP Concepts Used

This project was developed to practice and implement Python Object-Oriented Programming concepts, including:

* Classes and Objects
* Class Variables
* Class Methods
* Encapsulation
* Name Mangling using double-underscore methods
* Instance Methods

## Technologies Used

* Python
* JSON
* Pathlib
* Random
* String

## Project Structure

```text
python-oops-bank-management-system/
│
├── bank.py       # Main Python program
├── data.json     # Stores account data
└── README.md     # Project documentation
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Anirban-41/python-oops-bank-management-system.git
```

### 2. Navigate to the project directory

```bash
cd python-oops-bank-management-system
```

### 3. Run the Python program

```bash
python bank.py
```

## Available Operations

When the program starts, the user can select from the following operations:

```text
1. Create an account
2. Deposit money
3. Withdraw money
4. View account details
5. Update account details
6. Delete an account
```

## Data Storage

The application uses a `data.json` file to store account information.

The JSON file acts as a simple persistent data store, allowing account information to remain available when the program is run again.

## Learning Objective

This project was created as part of my journey in learning **Python and Object-Oriented Programming**.

The main objective was to apply Python concepts to a practical problem rather than only solving individual programming exercises.

## Future Improvements

Possible future improvements include:

* Adding a graphical user interface (GUI)
* Adding transaction history
* Adding stronger input validation
* Implementing improved PIN security
* Connecting the application to a proper database such as MySQL
* Adding automated testing

## Author

**Anirban Banerjee**

B.Tech in Electronics & Communication Engineering
Interested in **Python, Data Analytics, Data Science, and AI/ML**
