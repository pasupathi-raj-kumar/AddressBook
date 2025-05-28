# 📒 Address Book - C Console Application

A simple console-based Address Book application written in C that allows users to manage contact information such as name, phone number and email.

## 📌 Features

- Add new contacts
- View all contacts
- Search for a contact by name or phone number
- Edit contact information
- Delete a contact
- Save and load contact data from a file
- User-friendly console interface

## 🛠️ Built With

- Language: **C**
- Compiler: GCC or any standard C compiler
- Platform: Cross-platform (Tested on Linux and Windows)

## 🗂️ Project Structure

ADDRESS_BOOK_MAIN 
 - add_contact.c # Add new contacts
 - contact.csv # CSV file for storing contact data
 - contact.h # Header file with structure and function declarations
 - delete_contact.c # Delete existing contacts
 - dummy_contact.c # Test/stub functions (for development or debugging)
 - edit_contact.c # Edit contact details
 - file.c, file.h # File operations for reading/writing CSV
 - list_contacts.c # List all saved contacts
 - main.c # Entry point of the application
 - search_contact.c # Search contacts by name or phone
 - validate.c # Input validation logic

## 💾 Data Handling
 - All contacts are stored in contact.csv
 - CSV makes it easy to view and manipulate the data in any spreadsheet application

## 🔧 Compilation Command (Linux/macOS/Windows with GCC)
 - gcc *.c (or) gcc main.c add_contact.c delete_contact.c dummy_contact.c edit_contact.c file.c list_contacts.c search_contact.c validate.c -o address_book
 - **./address_book**     # On Linux/macOS
 - **address_book.exe**   # On Windows (if compiled with .exe extension)


## 🙋‍♂️ Author
Developed by Pasupathi Raj Kumar M.

## 📄 License
This project is licensed under the MIT License - feel free to use, modify, and share.

