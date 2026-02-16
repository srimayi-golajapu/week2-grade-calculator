# week2-grade-calculator
## Grade Calculator System
## Objective

Build a structured Python console application that:
Collects student academic data
Calculates averages and assigns grades
Displays structured results and class statistics
Implements input validation and error handling
Demonstrates clean modular programming
This project focuses on applying core Python fundamentals in a real mini-system instead of writing isolated scripts.

## Tech Stack Used

Python 3.x
Standard Python Library
Built-in functions
Exception handling
File handling
Terminal / Command Line Interface
No external libraries are used.

## Features

Input validation for all user entries
Menu-driven system
Grade assignment system:
A: 90–100
B: 80–89
C: 70–79
D: 60–69
F: Below 60
Automatic average calculation

## Class statistics:

Class average
Highest score
Lowest score
Student search functionality
Save results to a text file
Color-coded grade display in terminal
Error handling using try/except

## Program Structure

The application follows a modular structure using functions:

grade_calculator.py

## Main Components:

Grade Logic Functions
get_grade()
get_comment()
Input Validation Functions
get_positive_integer()
get_valid_mark()
Data Collection
collect_data()
Display System
display_results()
Search Functionality
search_student()
File Handling
save_to_file()
Menu Controller
main()
Each feature is separated into functions to improve:
Readability
Reusability
Maintainability
Debugging efficiency

## Future Implementations

Convert to Object-Oriented Programming structure

Add ranking system

Export results to CSV format

Store data in a database

Add graphical interface using Tkinter

Add percentage distribution of grades

Add login system for admin access
