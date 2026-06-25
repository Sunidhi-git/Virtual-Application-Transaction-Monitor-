# Virtual Application Transaction Monitor

## Overview

The Virtual Application Transaction Monitor is a Robotic Process Automation (RPA) project developed using UiPath. The automation interacts with a virtual banking application to process transactions, monitor transaction status, and capture the generated Transaction ID. The project demonstrates automation of banking operations in a virtual environment while handling different transaction scenarios.

## Project Objectives

- Automate transaction processing in a virtual banking application.
- Enter account number, amount, and transaction type automatically.
- Capture and display the generated Transaction ID.
- Handle different transaction outcomes effectively.
- Reduce manual effort and improve operational accuracy.

## Technologies Used

- UiPath Studio
- Windows Operating System
- Virtual Banking Application
- Excel (for input data, if applicable)

## System Architecture

User Input
    │
    ▼
UiPath Robot
    │
    ▼
Virtual Banking Application
    │
    ▼
Transaction Processing
    │
    ▼
Transaction Validation
    │
    ├── Successful Transaction
    ├── Insufficient Balance
    └── Transaction Limit Exceeded
    │
    ▼
Transaction ID Capture & Display

## Methodology

1. Launch the virtual banking application.
2. Read transaction details.
3. Enter account number.
4. Enter transaction amount.
5. Select transaction type.
6. Submit the transaction.
7. Capture the generated Transaction ID.
8. Display the transaction result.
9. Handle exceptions and validation messages.

## Features

- Automated data entry
- Virtual application interaction
- Transaction ID extraction
- Error handling
- Transaction monitoring
- Multiple test case validation
  
## Test Cases and Results

### 1. Successful Transaction

**Description:**  
The transaction is processed successfully when sufficient balance is available and the transaction amount is within the allowed limit.

![Successful Transaction](Screenshots/Successful_Transaction.png)

---

### 2. Insufficient Balance

**Description:**  
The transaction is rejected when the account balance is lower than the requested transaction amount.

![Insufficient Balance](Screenshots/Insufficient_Balance.png)

---

### 3. Transaction Limit Exceeded

**Description:**  
The transaction is rejected when the entered amount exceeds the maximum transaction limit allowed by the system.

![Transaction Limit Exceeded](Screenshots/Transaction_Limit_Exceeded.png)


## Expected Outcome

- Successful processing of valid transactions.
- Accurate capture of generated Transaction IDs.
- Proper handling of insufficient balance scenarios.
- Proper handling of transaction limit violations.
- Improved efficiency through automation.

---

## Conclusion

The Virtual Application Transaction Monitor successfully automates banking transactions in a virtual environment. The bot accurately captures Transaction IDs for successful transactions and appropriately handles error conditions such as insufficient balance and transaction limit exceeded, demonstrating the effectiveness of UiPath-based automation.

## Author

**Sunidhi Datta**

Bachelor of Engineering 

This project is developed for educational and academic purposes.
