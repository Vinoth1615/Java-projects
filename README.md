ATM System

Description

A simple ATM (Automated Teller Machine) System implemented in Java. The program allows users to perform basic ATM operations like withdrawing money, depositing money, checking balance, and exiting the system.

Installation

Follow these steps to install and set up the project:

git clone https://github.com/your-username/ATM-System.git
cd ATM-System

Usage

Run the program, and you will see a menu with options:

Choose 1 to withdraw money.

Choose 2 to deposit money.

Choose 3 to check your balance.

Choose 4 to exit the program.

Enter the required amount for withdrawal or deposit when prompted.

The system will process the transaction and update your balance accordingly.

Code Explanation

The program uses a while(true) loop to keep the ATM menu running until the user chooses to exit.

User input is taken via Scanner.

A helper method validateInputAmount(Integer amount) ensures that transactions involve positive amounts.

The balance is updated after each transaction.

Sample Output

Automated Teller Machine
Choose 1 for Withdraw
Choose 2 for Deposit
Choose 3 for Check Balance
Choose 4 for EXIT
Choose the operation you want to perform: 2
Enter money to be deposited: 5000
Your Money has been successfully deposited

Choose the operation you want to perform: 3
Balance: 5000

Author

VINOTH KUMAR D

GitHub: Vinoth1615

License

This project is licensed under the MIT License.
