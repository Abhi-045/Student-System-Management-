Overview:
Student Class: This class stores the details of a student, including ID, name, age, and course. It has methods for getting and displaying student data.

StudentManagementSystem Class: This class manages the list of students. It can add, display, update, delete, and search for students. The class also handles saving and loading data to/from a binary file (students.dat).

Features:
Add Student: Allows the user to input a new student's details and save it to the list.
Display Students: Displays a list of all students.
Update Student: Updates the details of a student by ID.
Delete Student: Removes a student from the list by ID.
Search Student: Finds and displays a student by ID.
Exit: Exits the program.
Menu:
A menu is displayed in the console, allowing the user to choose between the various options. The program loops until the user chooses to exit.

Persistence:
The students' data is saved to a binary file (students.dat) every time a change is made.
The data is loaded from the file when the program starts, so the students' list persists between runs.
Usage:
Compile and run the program. The menu will prompt you to select an option.
Enter the appropriate information for each action, and the program will handle the rest.


Example:

Student Management System
1. Add Student
2. Display Students
3. Update Student
4. Delete Student
5. Search Student
6. Exit
Enter your choice: 1
Enter Student ID: 101
Enter Student Name: John Doe
Enter Student Age: 20
Enter Student Course: Computer Science
