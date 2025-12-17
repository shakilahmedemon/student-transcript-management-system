# Student Transcript Management System

## 1. Project Overview
The **Student Transcript Management System** is a Python-based command-line application that simulates a basic academic record management system. It allows users to create, view, query, modify, and delete student transcript records through a menu-driven interface.

The system uses Python data structures such as **lists** and **dictionaries**, and demonstrates fundamental **software engineering and data structure concepts**. Student records are stored persistently in a CSV file (`student.csv`) when the program exits.


## 2. Key Features

- **CRUD Operations**
  - Create new student records
  - Read and query existing records
  - Update student information
  - Delete student records

- **Persistent Storage**
  - All student records are automatically saved to `student.csv` when the user selects **SAVE AND QUIT**

- **Custom Sorting Algorithms**
  - **Bubble Sort**: Sorts student records by **Student ID**
  - **Quick Sort**: Sorts student records by **Score**

- **Modular Program Structure**
  - Code is divided into multiple modules (`main`, `menu`, `student`, `sorting`, `storage`) for better readability and maintainability


## 3. How to Run

### Requirements
- Python **3.8 or higher**
- No external libraries required (uses only Python standard library)

### Execution Steps
1. Clone or download this repository.
2. Navigate to the project root directory.
3. Run the application using the command:
   ```bash
   python src/main.py
