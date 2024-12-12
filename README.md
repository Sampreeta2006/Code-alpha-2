Name:v.sampreeta
Company:code alpha
Domain:java programming
Duration:15.11.2024-15.12.2024
Task 2:banking application
Overview:
The SimpleBankingApp project is a basic Java application that simulates a simple banking system with three main functionalities:

Deposit Money: Allows the user to deposit a positive amount into their account balance.
Withdraw Money: Lets the user withdraw money from their account, but only if they have enough balance. It ensures that the withdrawal amount is positive and the balance is sufficient.
Check Balance: Displays the current balance in the user's account.
Key Features:
The program uses a Scanner to get user input from the console.
The balance is initially set to zero and is updated based on user actions.
The user can interact with the program by choosing from a menu with options:
Deposit money
Withdraw money
Check balance
Exit the program
Main Components:
Constructor (SimpleBankingApp): Initializes the account with a balance of zero.
Methods:
deposit(double amount): Increases the balance by the specified amount, ensuring it's positive.
withdraw(double amount): Decreases the balance if the withdrawal is possible (positive and within available balance).
checkBalance(): Displays the current balance.



