# -Project-on-ATM
Sample Operations of an ATM 

This repository contains the implementation of an Automated Teller Machine (ATM) Simulation System, designed to mimic real-life ATM functionalities in a simplified manner. The project demonstrates how core banking operations can be managed programmatically, and is ideal for beginners or intermediate developers seeking to practice essential coding concepts.

### 📌 Project Overview:
The ATM System enables users to perform basic banking transactions through a simulated interface. The main functionalities include:

### ✅ User Authentication: Secure login using user ID and PIN
 - Secure login using account number and PIN.
 - Limited login attempts for security.
 - PIN is either user-defined or system-generated.

### 💳 Pin Generation: Creating a Pin
 - New users can generate a 4-digit PIN.
 - Existing users can reset their PIN after verification.
 - PIN is validated for length and numeric format.

### ➕ Deposit: Add money to the account
 - Allows users to deposit an amount into their account.
 - Validates the input to prevent invalid entries.
 - Updates the balance and logs the transaction.

### ➖ Withdraw: Withdraw money with balance validation
 - Enables cash withdrawal from the account.
 - Checks for sufficient balance before processing.
 - Updates account balance and records the transaction.

### 🧾 Mini Statements: Providing mini statements
 
### 🚪 Exit: End the session securely
 - Securely exits the system with a friendly message.
 - Optionally logs the user out or clears the session.

### 🛠 Technologies Used
- **Language:** Python 
- **IDE:** VS Code / Eclipse / IntelliJ
- **Data Handling:** Text Files / JSON / Database (Optional)
- **Concepts:** Control structures, functions, OOP (optional), exception handling

 ### 🗂 Project Structure
   ATM-System-Project/
│
├── main.py                      # Main ATM program
├── users.txt                     # Stores user account details
├── transactions.txt              # Stores transaction history
├── utils.py                      # Helper functions (PIN generation, validations, etc.)
├── README.md                     # Project documentation
└── requirements.txt              # (Optional) List of dependencies if used

