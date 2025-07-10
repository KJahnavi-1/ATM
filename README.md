Simple ATM Console Application in C

Overview

This is a basic console-based ATM (Automated Teller Machine) simulation program written in C. It allows a user to perform fundamental banking operations: checking account balance, withdrawing cash, and depositing cash.

Features

Account Balance Inquiry: View the current balance in the account.
Cash Withdrawal: Withdraw a specified amount from the account, with a check for insufficient balance.
Cash Deposit: Deposit a specified amount into the account.
Continuous Operation: Allows multiple transactions until the user chooses to exit.

How to Use

Once the program is running, follow the on-screen prompts:

1.  You will be presented with a menu of options:
    1: Account Balance
    2: Cash Withdrawal
    3: Cash Deposit

2.  Enter your choice (1, 2, or 3) and press Enter.

3.  Follow subsequent prompts:
    For Withdrawal or Deposit, enter the amount when prompted.
    The program will display the updated account balance (or an "Insufficient Balance" message for withdrawals).

4.  Continue or Exit:
    * After each transaction, you will be asked: "Do you want to continue (Type 5):".
    * Type 5 and press Enter to perform another transaction.
    * Type any other number and press Enter to exit the program.
