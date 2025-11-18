🔐 Python Password Generator
A simple and customizable Password Generator written in Python.
This program allows you to generate strong passwords based on:
Minimum length
Whether numbers should be included
Whether special characters should be included
Repeats until the user chooses to exit

✨ Features
Generates secure, random passwords
Option to include:
✔️ Numbers
✔️ Special characters
Ensures the generated password meets all selected requirements
Runs in a loop until the user types exit
Beginner-friendly and easy to understand

📌 How It Works
Program asks for:
Minimum password length
Whether to include numbers
Whether to include special characters
It builds a password using:
string.ascii_letters → a–z & A–Z
string.digits → 0–9
string.punctuation → special characters
It keeps generating characters until:
The length requirement is met
All user-selected criteria are satisfied

The program prints the password and asks if you want to generate another one.
