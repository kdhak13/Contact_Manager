
# Contact Management System
A simple console-based Contact Management System built with C++ that allows users to add, view, and search for contacts. The application stores data persistently in a CSV file (data.csv), making it a lightweight yet efficient tool for managing basic contact information.

# Features
1. Add Contact
Add new contacts with the following details:
Phone Number
Name
Address
Description
Data is appended to the file data.csv.

2. Show All Contacts
Display all saved contacts in a readable format.

3. Search Contact
Search for a specific contact using the phone number. If found, the details are displayed.

4. Persistent Storage
Contacts are stored in data.csv to ensure data is retained even after the program exits.

# Code Structure
Class temp
Methods:
addContact(): Adds a new contact and appends it to data.csv.

showAll(): Reads and displays all contacts from data.csv.

searchContact(): Searches for a contact by phone number and displays the result.

main() Function
Handles the user interface and calls appropriate methods based on user input.
