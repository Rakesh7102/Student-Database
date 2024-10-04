The Student Database Management System is a desktop application developed using Python's Tkinter for the front end and SQLite for the back end. It allows users to manage student records, including adding, updating, deleting, and searching for information through an intuitive graphical interface.

Front End (Tkinter)
User Interface Components:

Main Window: A visually appealing interface titled "Student Database Management System," featuring a cadet blue background.
Input Fields: Fields for Student ID, First Name, Surname, Date of Birth, Age, Gender, Address, and Mobile Number, each clearly labeled.
Buttons: Action buttons for adding, displaying, clearing, deleting, searching, updating records, and exiting the application.
Listbox with Scrollbar: Displays student records, enabling users to select and interact with entries easily.
Back End (SQLite)
Database Operations:

Initialization: Creates a SQLite database (student.db) with a student records table upon startup.
CRUD Functions:
Create: Adds new student records.
Read: Retrieves all records or searches specific entries.
Update: Modifies existing records.
Delete: Removes selected records.
Security: Utilizes parameterized queries to prevent SQL injection.
Conclusion
This system effectively combines a user-friendly interface with a robust database backend, providing essential functionalities for managing student information in educational institutions. Its modular design allows for future enhancements and updates.
