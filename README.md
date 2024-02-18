# GroceryStore
A grocery e-cart application using pure core java and java8 features but resembling full stack features

# ATM
Write a program for a simplified ATM (Automated Teller Machine) that performs two basic operations: deposit and withdraw. The ATM should handle transactions in denominations of 100, 200, 500, and 2000 rupee notes. Implement a simple menu-driven program where the user can choose to deposit or withdraw money. Ensure that the program updates the available cash in the ATM accordingly. 
 
The program should initialize the ATM with some initial amount of cash.
Implement functions/methods for deposit and withdraw operations.
Display the available cash in the ATM after each transaction.
The program should continue running until the user chooses to exit
Deposit: Customer inputs the number of currency notes in each denomination
D.1) If any input values are negative, print "Incorrect deposit amount".
D.2) If all the input values are zero, print "Deposit amount cannot be zero".
D.3) If the input values are valid, increment the balances of corresponding rupee notes and print 
the available new balances in each denomination and the total balance.
Withdraw: Customer input the amount to withdraw. ATM dispenses the 2000, 500, 200, and 100 rupee
notes needed.
W.1) If the input amount is zero, negative, or over the current balance, print "Incorrect or 
insufficient funds".
W.2) If the input amount is in valid range, print the number of currency notes dispensed in each 
denomination. Use the available higher denomination first. Also, print the available new 
balances in each denomination and the total balance.
