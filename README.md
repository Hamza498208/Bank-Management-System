# Bank-Management-System
🧾 Customer Management System in C++
This is a simple Customer Management System written in C++ for administrative operations like customer onboarding, transaction handling, and basic account management. It is designed to work with file storage (customers.txt) and runs through a text-based menu for an admin to interact with the system.

📌 Features

✅ Add New Customers with basic information (name, email, phone).

🔁 Persist Customer Data using file input/output.

🔄 Update Customer Status (active or inactive).

💳 Record Transactions (credits/debits).

📄 View Transaction History for individual customers.

💸 Transfer Money between two customers with transaction logging.

🔐 Admin Menu for controlling all functionalities via a command-line interface.

📂 File Structure

main.cpp – The full implementation of the Customer Management System.

customers.txt – Data file used to store customer information persistently.
🚀 How It Works
   Classes
   Customer

Stores data like ID, name, email, phone, status, and transactions.

Handles parsing data from files and writing data back.

Supports transaction addition and displays history.

Admin

Manages an array of customers (max 100).

Handles all user inputs from the terminal (admin side).

Provides an interactive admin menu to perform operations.

⚠️ Notes

Ensure customers.txt is in the same directory as the executable for proper loading and saving of customer data.

All transactions are stored as a comma-separated list of integers under each customer's record.

No authentication or validation mechanisms are implemented — it's a basic simulation tool.

📌 Future Improvements

Add file locking to prevent data corruption.

Replace fixed-size arrays with dynamic data structures (e.g., vector).

Implement user authentication and logging.

Develop a GUI or web interface for better usability.

