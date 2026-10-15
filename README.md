# Python-ATM-Withdrawal-Program

## 📌 Project Overview

The **ATM Withdrawal Program** is a beginner-friendly Python mini project that simulates the basic operations of an Automated Teller Machine (ATM). It allows users to securely access a simulated account using a PIN, check their account balance, withdraw money, and view their transaction history.

The project is developed using fundamental Python programming concepts, including functions, conditional statements, loops, lists, and exception handling. It demonstrates how these concepts can be used to solve a practical problem.

**Note:** This is an educational simulation and is not connected to any real bank or financial institution.

## 🎯 Objectives

- To develop a simple ATM simulation using Python.
- To implement PIN verification with a limited number of attempts.
- To allow users to check their account balance.
- To implement cash withdrawal with appropriate validation.
- To maintain a transaction history during the program session.
- To handle invalid inputs and errors using exception handling.
- To apply Python programming concepts to a real-world scenario.

## ✨ Features

### 1. PIN Verification
- Users must enter the correct PIN to access the ATM menu.
- A maximum of three attempts is allowed.
- Access is denied after three incorrect attempts.

### 2. Balance Inquiry
- Displays the current account balance.
- Updates the displayed balance after successful withdrawals.

### 3. Cash Withdrawal
- Allows users to enter the amount they want to withdraw.
- Rejects zero or negative amounts.
- Accepts withdrawal amounts in multiples of ₹100.
- Prevents withdrawals exceeding the available balance.
- Updates the balance after a successful withdrawal.

### 4. Transaction History
- Records successful withdrawals.
- Displays transactions in numbered order.
- Shows a message when no transactions have been made.

### 5. Input Validation and Exception Handling
- Handles non-numeric withdrawal amounts.
- Handles invalid menu inputs.
- Displays appropriate messages for invalid operations.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Concepts:** Functions, loops, conditional statements, lists, variables, arithmetic operators, and exception handling.
- **Development Tools:** Python IDLE, VS Code, or any Python-compatible editor.
- **Version Control:** GitHub

## 📚 Python Concepts Implemented

| Concept | Usage in the Project |
|---|---|
| Functions | Separate functions handle balance inquiry, withdrawal, and transaction history. |
| Conditional Statements | Validate the PIN, withdrawal amount, and menu selection. |
| `for` Loop | Limits PIN attempts and displays transaction records. |
| `while` Loop | Keeps the ATM menu running until the user exits. |
| Lists | Store successful withdrawals during the current session. |
| `try-except` | Handles invalid numeric inputs using `ValueError`. |
| Arithmetic Operators | Calculate the remaining balance and validate withdrawal amounts. |

## ⚙️ Requirements

- Python 3 installed on your computer.
- A code editor such as IDLE or VS Code.
- Basic knowledge of running Python programs.

No external Python libraries are required.

## 🚀 How to Run the Project

1. Clone or download this repository to your computer.
2. Open the project folder.
3. Run the following command in your terminal:

   ```bash
   python atm_withdrawal.py
   ```

   If your system uses the `python3` command, run:

   ```bash
   python3 atm_withdrawal.py
   ```

4. Enter the sample PIN when prompted.
5. Select an operation from the ATM menu.

## 🔐 Sample Login Details

| Detail | Value |
|---|---|
| Initial PIN | `1234` |
| Starting Balance | ₹10,000 |
| Maximum PIN Attempts | 3 |

These values are predefined in the source code for demonstration purposes.

**Security note:** The PIN is hardcoded and is not securely stored. Do not use this program for real banking or sensitive financial information.

## 🖥️ Sample Output

```text
===== WELCOME TO PYTHON ATM =====
Enter your 4-digit PIN: 1234

Login successful!

===== ATM MENU =====
1. Check Balance
2. Withdraw Money
3. Transaction History
4. Exit

Enter your choice: 2
Enter withdrawal amount: Rs. 2000

Please collect your cash.
Remaining balance: Rs. 8000.00

===== ATM MENU =====
1. Check Balance
2. Withdraw Money
3. Transaction History
4. Exit

Enter your choice: 4
Thank you for using Python ATM!
```

## 🧪 Test Cases

| Test Case | Expected Result |
|---|---|
| Correct PIN | Login successful |
| Incorrect PIN three times | Access denied |
| Check balance | Current balance is displayed |
| Withdraw ₹2,000 | Balance decreases by ₹2,000 |
| Withdraw more than available balance | Insufficient balance message |
| Enter a negative amount | Invalid amount message |
| Enter a non-numeric amount | Error message is displayed |
| Select an invalid menu option | Invalid choice message |

## 📂 Project Structure

```text
python-atm-withdrawal-program/
│
├── atm_withdrawal.py
└── README.md
```

## ⚠️ Limitations

- The account balance is predefined.
- The PIN is hardcoded in the program.
- Transaction history is stored only while the program is running.
- Data is reset when the program is restarted.
- The project does not connect to a real ATM or banking system.

## 🔮 Future Improvements

- Store account details and transactions in files.
- Allow users to change their PIN.
- Add deposit functionality.
- Generate a transaction receipt.
- Support multiple simulated bank accounts.
- Add a graphical user interface.

## 🎓 Conclusion

The ATM Withdrawal Program demonstrates the practical application of fundamental Python programming concepts. It provides basic ATM operations, including PIN verification, balance inquiry, cash withdrawal, and transaction history, while using validation and exception handling to manage incorrect inputs.

This mini project strengthens understanding of Python functions, loops, lists, conditional statements, and exception handling. It serves as a useful foundation for developing more advanced banking simulations.

## 👨‍🎓 Project Information

- **Project Title:** ATM Withdrawal Program using Python
- **Project Type:** Python Programming Mini Project
- **Student Name:** Mohit Chandorkar
- **College:** Pimpri Chinchwad University (PCU)
- **Subject:** Python Programming
- **GitHub Repository:** Add your repository URL here

