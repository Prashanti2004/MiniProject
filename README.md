#Coding Club Management System#
This project is a simple Coding Club Management System implemented using SQLite3 and Python. It allows administrators to manage members and events for a coding club. The system supports the following key features:

#Features:#
Manage Members: Add, view, update, and delete members of the coding club. Each member has a name, email, and role (e.g., student, mentor).
Manage Events: Schedule coding events with details like event name, date, and speaker.
Database Integration: All member and event data is stored in an SQLite database, ensuring persistence and easy retrieval.

#Key Functions:#
View Members: Displays a list of all members in the club, including their ID, name, email, and role.
Add Member: Allows the admin to add a new member by providing their name, email, and role. Duplicate emails are not allowed.
Update Member Details: Admins can update a member's information (name, email, or role). If no new information is provided, the existing values remain unchanged.
Delete Member: Admins can remove members from the database by providing their member ID.
Schedule Events: Allows the admin to schedule events with event name, date, and speaker information.
#Technologies Used:#
SQLite: Used for database management to store member and event details.
Python: Programming language for implementing the system's logic.
#Requirements:#
Python 3.x
SQLite3 (comes bundled with Python)
#How to Use:#
Clone this repository to your local machine.
Install Python if not already installed.
Run the Python script (main.py) to start the management system.
Follow the prompts in the terminal to add, update, delete members, and schedule events.
#Example:#
bash
Copy code
$ python main.py
--- Coding Club Management ---
1. View Members
2. Add Member
3. Update Member Details
4. Delete Member
5. Schedule Coding Event
6. Exit
Enter your choice: 2
Enter name: John Doe
Enter email: john.doe@example.com
Enter role: Member
Member added successfully!
License:
This project is licensed under the MIT License - see the LICENSE file for details.
