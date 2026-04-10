Bank System ~ A basic command-line banking application for managing user accounts and financial operations.

Bank System is a Python-based console application that simulates basic banking operations like account creation, login, transactions, and account management. It is designed to provide a structured understanding of how user data, authentication, and financial operations are handled in a simple system.

Features:

* Account creation with auto-generated credentials
* Secure login system for users and admin
* Deposit, withdrawal, and fund transfer functionality
* OTP-based password recovery and account closure (via email)
* Random password generator for new accounts
* SQLite-based database for storing user data
* Simple text-based terminal interface

How to Use:

1. Run project.py in your terminal
2. Choose between Admin or User login
    * Admin Login Credentials:
        ACN: 0
        Password: Admin
    * User Login:
        Use account number (ACN) and password generated during account creation
3. Create a new account using admin access, then log in as a user
4. Perform operations like deposit, withdrawal, transfer, or password recovery

Built With:

* Python 3
* SQLite3 (database handling)
* Random module (password generation)
* SMTP / Gmail module (email functionality)

Design:

* Console-based, beginner-friendly structure
* Modular code using separate files (dbhandler, mailer, generator)
* Clear flow for authentication and transaction handling
* Focused on backend logic and functionality

License:
This project is licensed under the MIT License.

Contributions: Feel free to contribute or suggest improvements. Open an issue or submit a pull request.
