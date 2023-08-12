# STUDENT-RECORD-SYSTEM
Simple Student Database Management System in C - README
Overview
This C code implements a basic student database management system using a stack data structure. The program allows users to enter and manage student records, including details such as name, roll number, year of education, fee, course, and grade. Users can perform operations like adding student records, displaying records, sorting based on roll numbers or year of education, and deleting records.

Features
Adding Student Records: Users can enter details for multiple students, including name, roll number, year of education, fee, course, and grade. Student records are stored in a stack data structure.

Displaying Student Records: The program can display the data of all students present in the database.

Sorting Records: Users can sort student records in ascending order of roll numbers or year of education.

Deleting Student Records: Users can delete a student record based on their roll number.

Getting Started
Follow these steps to run the program:

Compile the code using a C compiler (e.g., GCC).

sh
Copy code
gcc student_database.c -o student_database
Run the compiled executable.

sh
Copy code
./student_database
The program will display a menu of options. Follow the on-screen instructions to navigate through the different functionalities.

Code Organization
The code is organized into several functions to manage the student database:

push(): Adds a student record to the stack, checking for stack overflow.

display(): Displays the details of all students in the database.

bubblesort_rollnumber() and bubblesort_year(): Implement bubble sort to sort student records based on roll numbers or year of education.

deletion(): Deletes a student record based on the given roll number.

main(): The main function drives the program's flow. It presents a menu to the user and handles user choices to perform various operations.

Important Notes
The program uses a stack data structure to store student records, but it has limitations like a fixed size.

The max_size constant defines the maximum number of students that can be stored.

The code could be further enhanced with additional error handling and input validation.

License
This code is provided under the MIT License. You are free to modify and use it for educational and personal purposes. Refer to the LICENSE file for more details.

Disclaimer
Please note that this code is a simplified simulation and should not be used for critical applications. It lacks advanced features and security measures typically required for real-world systems.

Feel free to expand upon this README to provide more detailed explanations and instructions for users who want to run and understand the provided C code.
