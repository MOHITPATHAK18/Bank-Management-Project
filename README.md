# 🏦 Bank Management System

## Project Overview

The Bank Management System is a Python-based application developed using
Object-Oriented Programming (OOP) principles to simulate the core
functionalities of a real-world banking system.

This project allows users to create and manage bank accounts efficiently
while performing various banking operations such as deposits, withdrawals,
updating account information, viewing account details, and deleting accounts.

The application uses JSON files as a lightweight database solution for
persistent data storage and demonstrates how Python can be used to build
real-life management systems without relying on external databases.

The primary goal of this project is to implement concepts such as:

- Object-Oriented Programming (OOP)
- File Handling
- JSON Data Management
- Data Validation
- Class Methods
- Exception Handling
- Random Data Generation
- Account Management Systems
- Banking Operations
- Persistent Storage

---

## Features

### Account Management

- Create a new bank account.
- Generate unique account numbers automatically.
- Store user information securely.
- Validate age requirements before account creation.
- Validate PIN length during registration.
- Maintain account balances dynamically.

### Deposit Functionality

- Deposit money into an account.
- Verify account number and PIN before transactions.
- Restrict invalid deposits.
- Automatically update account balances.
- Save changes permanently inside the JSON database.

### Withdrawal Functionality

- Withdraw money securely.
- Validate user credentials.
- Prevent withdrawals exceeding the available balance.
- Automatically update account information.

### Account Details

- Display complete user information.
- View:
  - Name
  - Age
  - Email Address
  - Account Number
  - Current Balance

### Update User Information

Users can update:

- Name
- Email Address
- PIN Number

Protected Information:

- Age
- Account Number
- Balance

remain unchanged to preserve data integrity.

### Account Deletion

- Delete existing accounts.
- Confirmation is required before deletion.
- Data is permanently removed from the JSON database.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| JSON | Data Storage |
| OOP | Project Architecture |
| pathlib | File Handling |
| random | Account Generation |
| string | Random Character Generation |
| Exception Handling | Error Management |

---

## Concepts Implemented

The project demonstrates the implementation of:

- Classes
- Objects
- Class Methods
- Encapsulation
- File Handling
- JSON Operations
- List Comprehensions
- Conditional Statements
- Functions
- Exception Handling
- Data Validation
- Banking Logic
- Persistent Data Storage

---

## Functionalities Included

- Create Account
- Deposit Money
- Withdraw Money
- Show Account Details
- Update User Details
- Delete Account
- Balance Management
- JSON Database Handling
- Automatic Data Saving
- Credential Verification

---

## Project Workflow

```
                User
                  |
                  |
                  ▼
          Create Account
                  |
                  ▼
          Account Verification
                  |
                  ▼
            JSON Database
                  |
                  ▼
         Deposit / Withdraw
                  |
                  ▼
          Update Balance
                  |
                  ▼
           Save Information
                  |
                  ▼
           Display Details
                  |
                  ▼
             Delete Account
```

---

## Account Creation Workflow

```
User Details
     |
     ▼
 Name Validation
     |
     ▼
 Age Validation
     |
     ▼
 PIN Validation
     |
     ▼
Generate Account Number
     |
     ▼
 Store Information
     |
     ▼
 Update JSON Database
     |
     ▼
 Account Created Successfully
```

---

## Banking Operations

The system currently supports:

- Account Creation
- Deposits
- Withdrawals
- User Authentication
- Account Updates
- Account Deletion
- Persistent Data Management

Every banking operation validates:

- Account Number
- PIN Number
- Available Balance
- Deposit Limits
- User Information

before updating the stored data.

---

## Learning Outcomes

This project helped in understanding:

- Python OOP Concepts
- JSON File Handling
- Data Persistence Techniques
- Banking System Design
- User Authentication
- Data Validation Techniques
- Exception Handling
- Real-World Project Development
- Software Design Principles
- Problem Solving Using Python

---

## Future Enhancements

The following features can be added in future versions:

- Streamlit User Interface
- SQLite Database Integration
- Money Transfer Functionality
- Transaction History
- Login Authentication System
- OTP Verification
- Password Encryption
- Dashboard and Analytics
- CSV Statement Generation
- PDF Report Download
- Email Notifications
- Interest Calculations
- Admin Panel
- Monthly Transaction Reports
- Data Visualization Dashboards

---

## Project Highlights

- Developed entirely using Python.
- Implements Object-Oriented Programming principles.
- Uses JSON files for persistent storage.
- Supports multiple banking operations.
- Provides user credential verification.
- Handles invalid operations gracefully.
- Designed with scalability and future enhancements in mind.
- Suitable for demonstrating Python development and software design skills.

---

## Conclusion

The Bank Management System is a practical Python project that demonstrates
how real-world banking operations can be modeled using Object-Oriented
Programming and JSON-based data management. The project emphasizes clean
logic implementation, data validation, and persistent storage mechanisms,
making it an excellent demonstration of Python programming fundamentals
and application development concepts.
