# BankManagment


This C++ program implements a basic banking management system. Here's a summary of the code:

*Program Overview*:
The program defines a struct named Account containing members for account number (integer), account holder's name (string), and balance (float).

The main function presents a menu-driven interface for users, allowing them to perform various banking operations: create an account, deposit money, withdraw money, view account details, and exit the program.



*Functions*:
void create_account(vector<Account> &accounts):
Asks the user for an account number, checks if it already exists, and creates a new account if not.
void deposit(vector<Account> &accounts):
Asks the user for an account number and deposit amount, adds the amount to the account's balance if the account exists.
void withdraw(vector<Account> &accounts):
Asks the user for an account number and withdrawal amount, subtracts the amount from the account's balance if sufficient funds are available.
void view_account(const vector<Account> &accounts):
Asks the user for an account number and displays the account details if the account exists.



*Program Flow*:
The user is presented with a menu to choose an operation.
Depending on the choice, the corresponding function is called, and the user is prompted for necessary inputs.
The program performs the chosen operation and provides appropriate feedback to the user.
The menu continues to be displayed until the user chooses to exit.
Key Points:
The program uses a vector<Account> to store account information, allowing dynamic addition of accounts.
Error messages are displayed for invalid inputs or non-existing accounts.
The program provides basic account management functionalities: creation, deposit, withdrawal, and viewing account details.

   



