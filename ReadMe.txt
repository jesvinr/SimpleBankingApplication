Simple Banking System
Overview
    This is a basic banking system implementation that allows users to create accounts,
log in, make transactions, and transfer funds between accounts.
    It uses MVVM (Model View ViewModel) pattern.

Features:
1. Create Account:
    Allows users to create a new account with the following details:
        a) Name
        b) Age
        c) Initial deposit amount
        d) Password
        e) Phone number
        f) Automatically generates a unique account number.


2.Sign In:
    Users can log in with their account number and password to view their account details.

3.Withdraw:
    Users can withdraw money from their account by providing account number, password, and the amount to withdraw.
Fund Transfer:

4.Money transfer:
    Allows users to transfer money from one account to another.
    Two options for fund transfer:
        a) Provide own account number, password, recipient's account number, and the amount.
        b) Provide recipient's account number and the amount (assuming the user has cash on hand).