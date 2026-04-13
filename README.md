# Student Information 
Masonwabe Nqam 
ST10513568 
PROG5121 Part 1 

# Part 1 Repository
ChatApp Login System

# Information 
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

Compile and Run:

Run Unit Tests:

The project includes unit tests to verify the functionality of the login system. To run the tests, ensure you have JUnit set up and use:
# If using Maven
mvn test

Contains methods for registering and validating:

Username: Checks if the username contains an underscore and is no more than 5 characters long.
Password: Validates that the password has a minimum length of 8 characters and contains an uppercase letter, a number, and a special character.
Phone Number: Ensures the phone number is in the South African format (+27 followed by 9 digits).
Login: Checks if the provided username and password match the registered credentials.
