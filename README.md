# HRJ_Bank
Create a basic bank management application using core Java, without the need for databases. Manage accounts, sort by ID, update balances, and remove accounts. Implement user authentication securely with user data stored in a users.properties file. Ideal for showcasing core Java skills in a beginner-friendly project."
HRJ Bank Management Application
Overview
This GitHub repository contains a simple yet comprehensive Java bank management application that allows users to perform basic banking operations. The application was created using core Java knowledge, and it does not rely on databases. It is an excellent project to showcase your fundamental Java programming skills.

Features
Account Creation: Users can create new bank accounts by providing an account ID, account holder name, and an initial balance.

Account Sorting: The application allows sorting of accounts based on their unique account IDs.

Account Updates: Users can update the balance for existing accounts by specifying the account ID.

Account Removal: Accounts can be removed from the system by providing the account ID.

Account Display: Users can view the details of all the bank accounts currently in the system.

User Authentication: The application offers secure user authentication, ensuring that only authorized users can access their accounts. User credentials (username and password) are stored in a users.properties file, guaranteeing data privacy and security.

Repository Structure
BankMain.java: The main Java class containing the bank management application logic.
UserProperties.java: A custom class for managing user properties, including loading, saving, and authenticating users.
users.properties: A text file that stores user credentials (username and password).
Other necessary files and resources.
Usage
Clone the Repository: Clone this repository to your local machine.

Compile and Run: Use a Java compiler to compile the BankMain.java file, and run the resulting class. This will launch the bank management application.

Follow the Menu: The application presents a menu with options to create accounts, sort accounts, update account balances, remove accounts, display accounts, and perform user authentication.

User Authentication: To use the user authentication feature, you can enter a username and password, which are checked against the stored credentials in the users.properties file.

Exit and Save: The application allows you to exit the program gracefully, saving user information to the users.properties file.
