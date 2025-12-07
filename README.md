#Student Record Management System

This project is a simple console-based Student Record Management System developed in the C
programming language. It uses structures, arrays, and file handling to store and manage student
information efficiently. The system includes a role-based login feature, allowing different levels of
access for Admin, Staff, and Guest users.
#Features
- Role-based login system:
- Admin: Add, View, Search, Update, Delete
- Staff: Add, View, Search, Update
- Guest: View and Search only
- Add new student records
- Display all student records
- Search for a student by roll number
- Update existing student details
- Delete student records (Admin only)
- Stores data permanently in text files
- Simple and user-friendly console interface
#Files Used
- main.c – Source code file
- students.txt – Stores student records (auto-created if missing)
- credentials.txt – Stores usernames, passwords, and user roles
Example credentials.txt:
admin admin123 admin
staff1 staff123 staff
guest1 guest123 guest
How to Compile and Run
1. Compile the program:
gcc main.c -o student
2. Run the program:
./student
Student Record Format (students.txt)
Example:
1 John 85.5
2 Priya 91.0
3 Rahul 78.2
Future Enhancements
- Support for multi-word names
- Sorting student records
- GUI-based interface
- Password encryption
- Database integration (MySQL/SQLite)
- Dynamic data structures (linked list, BST)
Conclusion
This project demonstrates fundamental concepts of C programming such as file handling, structures,
arrays, and modular coding. It provides an effective and simple solution for managing student records
in an educational environment.
