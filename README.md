README for ATM Machine Application
Overview
This ATM Machine application is a simple graphical user interface (GUI) built using Python's Tkinter library. It allows users to create an account, log in, and perform basic banking transactions such as checking balance, depositing, and withdrawing money.
Features
Account Creation: Users can create a new account by entering their name and a 4-digit PIN.
Login System: Users can log in using their account number and PIN.
Transaction Options: Once logged in, users can:
View account details
Check account balance
Deposit funds
Withdraw funds
Transaction Receipt: Upon exiting, users receive a summary of their transactions.
Requirements
To run this application, ensure you have Python installed on your machine. The Tkinter library is included with Python's standard library, so no additional installation is required.
Installation
Clone the Repository (if applicable):
bash
git clone <repository-url>

Run the Application:
Save the provided code in a file named atm_app.py.
Open a terminal or command prompt.
Navigate to the directory where atm_app.py is located.
Run the application using:
bash
python atm_app.py

Usage Instructions
Creating an Account:
Launch the application.
Enter your name and a 4-digit PIN in the respective fields.
Click on "Create Account." A success message will confirm account creation, and your account number will be displayed.
Logging In:
Click "Proceed to Login."
Enter your account number and PIN.
Click "Login." If successful, you will be directed to the transaction menu.
Performing Transactions:
From the transaction menu, choose one of the following options:
Account Details: View your account holder name, account number, and balance.
Check Balance: Display your current balance.
Deposit: Enter the amount you wish to deposit and click "Submit."
Withdraw: Enter the amount you wish to withdraw and click "Submit."
You can exit the application at any time, and a transaction receipt will be displayed.
Code Structure
The application is structured as a class ATMApp, which contains methods for each functionality:
__init__: Initializes the application and sets up the main window.
create_account_screen: Displays the account creation interface.
create_account: Handles account creation logic.
login_screen: Displays the login interface.
validate_login: Validates user credentials.
transaction_menu: Displays options for transactions.
deposit and withdraw: Handle deposit and withdrawal logic, respectively.
exit_app: Displays a transaction receipt upon exiting.
Troubleshooting
Ensure all fields are filled correctly during account creation and login.
If you encounter issues running the application, check that Python is properly installed and that you are using a compatible version.
