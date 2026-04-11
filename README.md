# ST10513568_PROG5121_Part1
Part 1 Repository
ChatApp Login System

A simple Java application to manage user login, including validation for username, password, and phone number.

Features
Username Validation:
The username must contain an underscore (_) and be at most 5 characters long.
Password Validation:
Must be at least 8 characters.
Must contain at least one uppercase letter, one digit, and one special character.
Phone Number Validation:
Must follow South African phone number format: +27 followed by 9 digits.
Login:
Verifies user credentials by matching the registered username and password.
Setup

Clone the repository:

git clone https://github.com/yourusername/chatapp-login.git
cd chatapp-login

Compile and Run:

You can use any Java IDE (e.g., IntelliJ IDEA, Eclipse) to compile and run the code, or use the following commands for command-line execution:
javac Login.java
java Login

Run Unit Tests:

The project includes unit tests to verify the functionality of the login system. To run the tests, ensure you have JUnit set up and use:
# If using Maven
mvn test

# If using Gradle
gradle test
Code Overview
Login Class

Contains methods for registering and validating:

Username: Checks if the username contains an underscore and is no more than 5 characters long.
Password: Validates that the password has a minimum length of 8 characters and contains an uppercase letter, a number, and a special character.
Phone Number: Ensures the phone number is in the South African format (+27 followed by 9 digits).
Login: Checks if the provided username and password match the registered credentials.
Unit Tests

The LoginTest class includes JUnit tests for the following:

Username Validation
Password Complexity
Phone Number Format
Login Functionality (valid and invalid logins)
