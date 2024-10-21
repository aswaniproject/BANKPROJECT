# BANKPROJECT
Python mini project
This mini project is a simple banking system using python. In this project user is allowed to Login to their account throught password which is already set, Deposit and withdraw money, Checking the balance, Add interest to the balance, Show transaction history and changing password.

#Features
Key features included are :
Account Login : Secure login using a password.
Amount Deposit : Deposit money into your account.
Amount withdrawal : Withdraw money if you have enough balance.
Balance check : View your current account balance.
Interest Calculation : Add interest to your account based on a specified rate.
Change Password : Change your account password after confirming your old password.
Transaction History : Review all deposits, withdrawals, and interest added to the account.

#Functions used

1. `__init__(self, account_holder, password, balance=0)`: Initializes account with name, password, and starting balance.
2.  `login(self, input_password)`: Authenticates user login.
3. `deposit(self, amount)`: Deposits the specified amount into the account.
4. `withdraw(self, amount)`: Withdraws money if balance permits.
5.  `check_balance(self)`: Displays the current balance.
6. `add_interest(self, interest_rate)`: Adds interest to the balance based on the provided rate.
7.  `change_password(self, old_password)`: Allows users to change their password after verifying the old password.
8.  `show_transactions(self)`: Shows the transaction history.

