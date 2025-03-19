# Bank-management-system
Banking System

A simple banking system implemented in C++ that allows users to create accounts, deposit and withdraw money, manage loans, and view account transactions.

Features

✅ Create a new bank account

✅ Deposit money into an account

✅ Withdraw money from an account

✅ View account details and transaction history

✅ Delete an account

✅ Display all existing accounts

✅ Search for an account by account number

✅ Add interest to an account

✅ Request and manage loans

✅ Repay loans

✅ Display loan details

Installation and Compilation

To compile and run the project, follow these steps:

Using g++ (For Windows, Linux, MacOS)

Open a terminal or command prompt.

Navigate to the folder where the source code is saved.

Compile the code using:

g++ banking_system.cpp -o banking_system

Run the compiled executable:

./banking_system

How to Use

Once the program starts, you will see a menu with multiple options:

Create Account - Enter account number, name, and initial deposit to create a new account.

Deposit - Enter an account number and deposit amount.

Withdraw - Enter an account number and withdrawal amount.

Display Account - View account details including balance and transactions.

Delete Account - Remove an existing account.

Display All Accounts - View a list of all accounts.

Search Account by Number - Find an account using the account number.

Add Interest - Apply interest to a specific account.

Request Loan - Apply for a loan with an interest rate.

Repay Loan - Make payments towards a loan balance.

Display Loan Info - View loan details such as amount, interest rate, and remaining balance.

Exit - Close the application.

Code Structure

Transaction class: Stores transaction details (type and amount).

Account class: Manages account details, balance, transactions, and loans.

Bank class: Handles all banking operations.

main function: Provides the user interface through a menu system.

Example Usage

Creating an Account

Enter Account Number: 12345
Enter Account Holder's Name: John Doe
Enter Initial Deposit: 5000
Account created for John Doe with an initial balance of 5000

Depositing Money

Enter Account Number: 12345
Enter Amount to Deposit: 1000
|| Deposited 1000 into account 12345. New balance || 6000

Withdrawing Money

Enter Account Number: 12345
Enter Amount to Withdraw: 2000
|| Withdrew 2000 from account 12345. New balance || 4000

Requesting a Loan

Enter Account Number: 12345
Enter Loan Amount: 5000
Enter Interest Rate: 5
|| Loan of 5000 approved for account 12345 at an interest rate of 5% ||

Future Enhancements

🔹 Implement a graphical user interface (GUI)

🔹 Save account details to a file for persistent storage

🔹 Add user authentication for security

License

This project is open-source and available under the MIT License.

Contributions

Pull requests are welcome. If you have any suggestions for improvement, feel free to contribute!

Enjoy coding! 😊

