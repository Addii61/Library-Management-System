Library Management System
The Library Management System is a console-based application designed in C for managing books and student records within a library. This system provides functionalities like adding books, displaying book lists, removing books, issuing books to students, and maintaining an issue log.

Table of Contents
[Features](https://chat.openai.com/c/1fa1aadc-7a6d-4dae-b432-216c8895ed3b#features)
[How to Use](https://chat.openai.com/c/1fa1aadc-7a6d-4dae-b432-216c8895ed3b#how-to-use)
[File Structure](https://chat.openai.com/c/1fa1aadc-7a6d-4dae-b432-216c8895ed3b#file-structure)
[Compilation and Execution](https://chat.openai.com/c/1fa1aadc-7a6d-4dae-b432-216c8895ed3b#compilation-and-execution)
[Contributing](https://chat.openai.com/c/1fa1aadc-7a6d-4dae-b432-216c8895ed3b#contributing)
[License](https://chat.openai.com/c/1fa1aadc-7a6d-4dae-b432-216c8895ed3b#license)
Features
Add Book - Allows the addition of new books to the library with book ID, name, author, and automatic entry of the current date.
Books List - Displays the list of available books with their details.
Remove Book - Removes a book based on its ID from the library records.
Issue Book - Enables the issuance of books to students by associating the book with the student's name, class, roll number, and the current date.
Issued Book List - Displays a log of books issued to students with relevant details.
How to Use
Compilation: Compile the source code using a C compiler like GCC.
gcc library_management_system.c -o library_management_system
Execution: Run the compiled executable.
./library_management_system
Follow the on-screen prompts to navigate through the application and perform various operations.
File Structure
library_management_system.c: Contains the source code of the Library Management System.
books.txt: File to store book records.
issue.txt: File to maintain book issuance records.
temp.txt: Temporary file used during book deletion process.
Compilation and Execution
To compile the source code, make sure you have a C compiler installed. Use the following commands:
gcc library_management_system.c -o library_management_system
To execute the program:
./library_management_system
Contributing
Contributions to this project are welcome! Feel free to fork the repository, make changes, and create a pull request
