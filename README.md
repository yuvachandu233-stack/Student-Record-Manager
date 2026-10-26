# Student-Record-Manager

A menu-driven Student Record Management System developed using C++ and Object-Oriented Programming (OOP).

## About the Project

Student Record Manager is a console-based application designed to simplify student record management. It allows users to add, display, search, modify, and delete student records, along with generating academic result reports.

## Features

1. **Add Student Record** — Add new student information.
2. **Display All Records** — View stored student records.
3. **Search by Roll Number** — Find a student using their roll number.
4. **Search by Name** — Search for a student by name.
5. **Modify Record** — Update existing student details.
6. **Delete Record** — Remove a student record.
7. **Result & Class Report** — Calculate marks, percentages, grades, class average, and results.

## Technologies Used

* C++
* Object-Oriented Programming
* File Handling
* Fixed-Size Arrays

## C++ Libraries

The project uses three standard libraries:

* `iostream`
* `fstream`
* `string`

## Data Storage

Student records are stored in `students.dat` using file handling. The application uses a fixed-size array with a maximum capacity of 100 student records.

## OOP Concepts

* Classes and Objects
* Encapsulation
* Inheritance
* Polymorphism
* Abstraction
* Constructors

## How to Run

1. Clone or download this repository.
2. Open `src/main.cpp` in a C++ IDE or editor.
3. Compile the program using a C++ compiler.

Example using g++:

```bash
g++ src/main.cpp -o student_manager
```

4. Run the program.

On Windows:

```bash
student_manager.exe
```

On Linux or macOS:

```bash
./student_manager
```

## Project Team

* K. Sai Sashank
* G. Yuva Chandu
* Ch. Hariswar
* P. Monish

## Academic Project

Department of Artificial Intelligence & Machine Learning
Aditya University

## Future Enhancements

* Database integration
* User authentication
* Web-based interface
* Advanced attendance management
* Printable and exportable reports

