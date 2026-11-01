# Student Records Persistence & Export System

## About the Project
Student Records Persistence & Export System is a Python-based command-line project that helps manage student information and academic records.

It allows users to add student records, search student details, display saved records, export data to CSV, and store student information permanently using JSON files.

This project demonstrates Python file handling, JSON operations, and CSV file management.

## Features
- Add student records.
- Store student ID and name.
- Store department details.
- Store marks of three subjects.
- Validate student records.
- Prevent duplicate student IDs.
- Save records permanently in JSON.
- Load previously saved records.
- Search students by ID.
- Display all student records.
- Export records to CSV.
- Maintain activity logs.
- Read and write text files.

## Technologies Used
- Python
- Command Line Interface (CLI)
- JSON
- CSV

## Python Modules Used
- json – Store and retrieve student records.
- csv – Export student records into CSV format.
- os – Check whether files exist.
- datetime – Generate timestamps for activity logs.

## Python Concepts Used
- File Handling
- File Modes (r, w, a)
- with open()
- read()
- readline()
- readlines()
- write()
- writelines()
- JSON Serialization
- json.dump()
- json.load()
- json.dumps()
- json.loads()
- CSV Handling
- Dictionaries and Lists
- Exception Handling

## Project Structure

```text
student_records_system/
│
├── main.py
├── students.json
├── students.csv
└── activity_log.txt
```

## How to Run the Project

1. Install Python on your computer.
2. Download or clone this repository.
3. Open the project folder in VS Code.
4. Run the following command:

```bash
python main.py
```

## Example Output

```text
1. Add Student
2. Export Records to CSV
3. Search Student
4. Display All Records

Student ID: S101
Name: Aman
Department: CSE

Python marks: 78
Maths marks: 65
DBMS marks: 88

Record saved to students.json.

CSV export completed: students.csv

Search Student:
Enter ID: S101

Name: Aman
Department: CSE
Python: 78
Maths: 65
DBMS: 88
```

## File Storage
- students.json – Stores student records permanently.
- students.csv – Stores exported student data.
- activity_log.txt – Stores timestamped activity records.

## Project Purpose
The main purpose of this project is to understand Python file handling and JSON operations and learn how to save, retrieve, update, and export data using different file formats.

## Author
Md Wajaullah

## Project Level
Intermediate – Python File Handling & JSON