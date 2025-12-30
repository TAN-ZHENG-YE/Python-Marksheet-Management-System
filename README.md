# Python Marksheet Management System

## Overview
The Python Marksheet Management System is a console-based application designed to help lecturers manage student assessment records efficiently. The system calculates final marks and grades automatically, manages student records across semesters, and generates grade distributions based on a predefined grading scheme.

## Problem Statement
Managing student marks manually can be time-consuming and prone to errors. Lecturers need a reliable system to store assessment data, calculate weighted final scores, assign grades, and review grade distributions for each semester.

## Solution
This project provides a structured, menu-driven program that allows lecturers to add, edit, delete, search, save, and load student marks. Final marks are automatically calculated based on assessment weightings, and grades are assigned according to an academic grading system.

## Key Features
- Menu-driven console interface for easy navigation
- Object-oriented design using a `PythonMarksheet` class
- Automatic calculation of weighted final marks
- Grade assignment based on a predefined grading scheme
- Search, edit, and delete student records using student ID
- Display all student marks on screen
- Save student records to external text files by semester
- Load and update previous semester records
- Grade distribution generation after data loading

## Grading System
| Final Mark (%) | Grade |
|:--------------:|:------:|
| x < 50         | F      |
| 50 ≤ x < 55    | PS2    |
| 55 ≤ x < 60    | PS1    |
| 60 ≤ x < 65    | CR2    |
| 65 ≤ x < 70    | CR1    |
| 70 ≤ x < 75    | DI2    |
| 75 ≤ x < 80    | DI1    |
| 80 ≤ x < 85    | HD2    |
| x ≥ 85         | HD1    |

## Technical Implementation
- Developed using Python
- Object-oriented programming with a custom `PythonMarksheet` class
- Student records stored using dictionaries (no lists or tuples used)
- Modular program design using multiple functions
- Input validation using string handling to prevent runtime errors
- File handling for saving and loading semester-based data

## Skills Demonstrated
- Python programming
- Object-Oriented Programming (OOP)
- File handling
- Data validation
- Dictionary-based data structures
- Menu-driven application design
- Problem-solving and logical thinking


## Future Improvements
- Add a graphical user interface (GUI)
- Export grade distributions as charts or reports
- Support CSV or database storage
- Add user authentication

## How to Run the Program
1. Ensure Python is installed on your system
2. Clone this repository or download the project files
3. Run the main Python file in a terminal or IDE
4. Follow the on-screen menu instructions
