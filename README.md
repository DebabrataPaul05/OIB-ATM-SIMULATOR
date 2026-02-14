# OIB-ATM-SIMULATOR
Multi-Bank ATM System (using Java)

The Multi-Bank ATM System is a console-based Java application that simulates essential banking operations in a structured and realistic manner. The system allows users to create accounts, securely log in using a PIN, perform deposits and withdrawals, transfer funds between accounts across different banks, and view detailed transaction history. All account and transaction data are stored using Java Serialization to ensure persistence across multiple program executions.

The application supports multiple banks, including State Bank of India, Bank of Baroda, and Punjab National Bank. Each bank maintains its own collection of accounts, and account numbers are automatically generated using a bank-specific prefix combined with a unique random number. This ensures uniqueness while simulating real-world banking account structures.

Users can open new accounts by selecting a bank and setting a four-digit PIN. After authentication, the ATM menu provides options to check balance, deposit funds, withdraw funds with proper validation, transfer money to other accounts (including cross-bank transfers), and view transaction history with timestamps. For each financial operation, the system generates a formatted receipt displaying transaction details, account information, and updated balance.

The project demonstrates the implementation of core Java concepts such as object-oriented programming, file handling, serialization and deserialization, exception handling, and the use of collections like HashMap and ArrayList. The modular design includes separate classes for Transaction, Account, Bank, and the main ATMSystem controller, ensuring clean structure and maintainability.

This system can be further enhanced by integrating database connectivity, PIN encryption for improved security, graphical user interfaces, or additional banking features such as interest calculation and administrative controls.
