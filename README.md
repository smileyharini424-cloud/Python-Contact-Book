# Python Contact Book

## Explanation

This project is a simple contact book application developed using Python. It allows users to store contact names and phone numbers and perform basic contact management operations.

## Problem Statement

Create a Python program that allows users to add, search, update, delete, and display contacts.

## Features

* Add a contact
* Search for a contact
* Update a contact
* Delete a contact
* Display all contacts
* Menu-driven interface

## How It Works

1. The program creates an empty dictionary to store contacts.
2. The user selects an operation from the menu.
3. Contact details are added, searched, updated, or deleted.
4. The display option shows all stored contacts.
5. The program continues until the user selects Exit.

## Technologies Used

* Python
* Dictionary
* Functions
* Loops
* Conditional statements

## Data Structure Used

* Dictionary

The contact name is used as the key and the phone number is stored as the value.

## Methods Used

* `input()`
* `print()`
* `get()`
* `del`
* Dictionary operations
* Functions
* `while` loop

## Program Flow

1. Start the program.
2. Create an empty contact dictionary.
3. Display the menu.
4. Accept the user's choice.
5. Perform the selected operation.
6. Return to the menu.
7. Exit when the user selects option 6.

## Sample Input

```text
1
Harini
9876543210
1
Anu
9123456780
5
2
Harini
3
Harini
9999999999
4
Harini
5
6
```

## Sample Output

```text
===== Contact Book =====

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 1
Enter contact name: Harini
Enter phone number: 9876543210
Contact added successfully.

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 1
Enter contact name: Anu
Enter phone number: 9123456780
Contact added successfully.

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 5
Contacts:
Harini : 9876543210
Anu : 9123456780

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 2
Enter contact name to search: Harini
Phone number: 9876543210

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 3
Enter contact name to update: Harini
Enter new phone number: 9999999999
Contact updated successfully.

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 4
Enter contact name to delete: Harini
Contact deleted successfully.

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 5
Contacts:
Anu : 9123456780

1. Add Contact
2. Search Contact
3. Update Contact
4. Delete Contact
5. Display Contacts
6. Exit
Enter your choice: 6
Program ended.
```

## Time Complexity

* Add: O(1) average
* Search: O(1) average
* Update: O(1) average
* Delete: O(1) average
* Display: O(n)

## Space Complexity

O(n), where n is the number of contacts.

## Key Learning

* How to use dictionaries for storing key-value data.
* How to create a menu-driven program.
* How to use functions.
* How to add, search, update, and delete data.
* How to build a simple real-world Python application.

## File Location

```text
Python-Contact-Book/contact_book.py
```

## Repository Structure

```text
Python-Contact-Book/
│
├── contact_book.py
└── README.md
```

## Author

V.Harini
