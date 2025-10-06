# python-mini-project1-ATM-
💳 ATM Simulation System (Python Mini Project)
📘 Overview

The ATM Simulation System is a Python-based mini project designed to mimic the basic functionalities of a real-world ATM. It allows users to check their account balance, deposit money, withdraw cash, and change their PIN securely. This project provides an excellent learning experience for beginners to understand core Python concepts like loops, conditional statements, functions, file handling, and data validation.

🧠 Project Objectives

Simulate key ATM operations in Python.

Implement user authentication using PIN verification.

Learn and apply basic file handling for storing account details.

Strengthen understanding of decision-making and control flow statements.

Provide a console-based, user-friendly interface.

⚙️ Features

✅ User Authentication: Login using a valid PIN.
✅ Check Balance: Display current account balance.
✅ Deposit Money: Add amount to the account securely.
✅ Withdraw Money: Withdraw funds if balance is sufficient.
✅ Change PIN: Update the existing PIN after verification.
✅ Exit Option: Safely terminate the session.

🧩 Technologies Used

Language: Python 3.x

Concepts Covered:

Loops (while, for)

Conditional Statements (if-else)

Functions

Dictionaries / File Handling

Exception Handling

🏗️ Project Structure
ATM-Project/
│
├── atm.py                # Main program file
├── users.txt             # Optional file to store account data
└── README.md             # Project documentation

🚀 How It Works

The program starts with a login screen asking for the user’s PIN.

Once authenticated, a menu is displayed with available options (Check Balance, Deposit, Withdraw, Change PIN, Exit).

The user can select any operation, and the corresponding function is executed.

The system performs necessary validations (like checking sufficient balance during withdrawal).

Data is updated and displayed accordingly.

💡 Sample Output
Welcome to Python ATM 💳
Enter your 4-digit PIN: ****

1. Check Balance
2. Deposit
3. Withdraw
4. Change PIN
5. Exit

Enter your choice: 1
Your current balance is ₹10,000

🔐 Future Enhancements

Add multiple user accounts.

Implement database storage using SQLite.

Add GUI using Tkinter or PyQt.

Enable transaction history tracking.

🎯 Learning Outcomes

Through this project, you will learn how to:

Use functions to organize code efficiently.

Manage user input and validation.

Work with file handling for data persistence.

Apply control structures effectively.
