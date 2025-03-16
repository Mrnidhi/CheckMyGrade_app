# Final Report for CheckMyGrade Application

## Abstract

This document serves as the final report for the CheckMyGrade Application, a Python-based student grade management system developed for academic course management. The application provides functionalities for managing student records, courses, professors, grades, and user login. Extensive unit tests have been implemented to ensure the robustness of the system.

## Introduction

The CheckMyGrade Application is designed to streamline the management of academic data and enhance the user experience by offering an intuitive command-line interface. Key features include:

- **Student Operations:** Add, update, delete, and search student records using a linked list structure.
- **Course and Professor Management:** Manage courses and professors, and display associated details.
- **Grade and Report Generation:** Process grade information and generate various reports (e.g., course-wise, professor-wise, and student-wise).
- **User Authentication:** Secure login operations with password encryption.
- **Data Persistence:** Store and retrieve data using CSV files.

## Project Architecture and Design

The application employs an object-oriented design with a modular structure. The main components are:

- **Student:** Manages individual student details.
- **StudentLinkedList:** Handles the collection of student records.
- **Grades:** Manages grade details and operations.
- **Course:** Contains course-specific information.
- **Professor:** Maintains professor data and their course associations.
- **LoginUser:** Implements user login, password encryption, and authentication.
- **CheckMyGradeApp:** Acts as the main controller that integrates all modules and presents a menu-driven interface.

### Class Diagram

![Class Diagram](./README%20files/draw.io_final.png)

## Implementation Details

The project is implemented in Python, with file I/O operations performed via CSV files for data storage:

- **Source Code Files:**
  - `checkmygrade_app.py` – Main application code.
  - `test_checkmygrade_app.py` – Unit tests for validating application functionalities.

- **Data Files:**
  - `Student.csv`
  - `Course.csv`
  - `Professor.csv`
  - `Grades.csv`
  - `Login.csv`

The code is structured to ensure ease of maintenance, modularity, and scalability, making it straightforward to add new features or modify existing ones.

## Testing and Terminal Outputs

The functionality of the application has been validated through comprehensive testing. Below are the updated paths for the terminal screenshots that demonstrate the working of the application:

### Terminal Screenshot 1: Application Launch and Main Menu

`./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.47.22%20PM.png`

### Terminal Screenshot 2: Login Operations

`./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.47.27%20PM.png`

- **Signup a new user:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.47.58%20PM.png`

- **After signup, login check of the new user:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.48.14%20PM.png`

- **Change of Password of the user:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.48.44%20PM.png`

### Terminal Screenshot 3: Student Operations

- **Student operations:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.49.00%20PM.png`
  
- **Display all students:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.49.02%20PM.png`
  
- **Search Student Record:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.49.19%20PM.png`
  
- **Add New Student:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.50.05%20PM.png`
  
- **Update student and checking the grades:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.01%20PM.png`
  
- **Check Marks:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.18%20PM.png`
  
- **Delete Student:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.28%20PM.png`

### Terminal Screenshot 4: Professor Operations

- **Display all professors:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.52%20PM.png`
  
- **Add New Professor:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.52.27%20PM.png`
  
- **Modify professor details:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.53.10%20PM.png`
  
- **Show Professor course details:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.04.27%20PM.png`
  
- **Delete Professor:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.04.52%20PM.png`

### Terminal Screenshot 5: Course Operations

- **Display all courses:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.05.10%20PM.png`
  
- **Add new Course and display:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.05.45%20PM.png`
  
- **Delete course:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.05.53%20PM.png`

### Terminal Screenshot 6: Grade Operations

- **Display grade operations:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.06.10%20PM.png`
  
- **Adding a new grade:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.06.49%20PM.png`
  
- **Modifying a Grade:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.07.26%20PM.png`
  
- **Delete a grade:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.07.44%20PM.png`

### Terminal Screenshot 7: Reports & Stats Operations

- **Sort by name:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.00%20PM.png`
  
- **Sort by student marks:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.07%20PM.png`
  
- **Average marks of course ID DATA200:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.22%20PM.png`
  
- **Median marks of all courses:**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.35%20PM.png`
  
- **Course-wise report (enter course ID to get report):**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.45%20PM.png`
  
- **Professor-wise report (enter professor email id to get report):**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.05%20PM.png`
  
- **Student-wise Report (enter student email id to get report):**  
  `./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.18%20PM.png`

### Terminal Screenshot 8: End of the Operations

At the end of the operation when we exit from the code, the program automatically saves all the data before exiting:

`./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.28%20PM.png`

### Terminal Screenshot 9: Unit Testing Operation

This tests the performance of the code:

`./README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.55%20PM.png`

## Conclusion

The CheckMyGrade Application effectively meets the project requirements for managing student grades and related academic data. The modular design and robust implementation ensure that the system is both maintainable and scalable. Unit tests confirm that the major functionalities operate as expected, providing a solid foundation for further enhancements.

## Appendices

- **Source Code:** Refer to `checkmygrade_app.py` and `test_checkmygrade_app.py` for the complete codebase.
- **Data Files:** CSV files (`Student.csv`, `Course.csv`, `Professor.csv`, `Grades.csv`, `Login.csv`) store persistent data.
- **Class Diagram:** See `draw.io_final.png` for the visual representation of the system architecture.
- **Terminal Screenshots:** All relevant terminal screenshots are attached in the above sections with updated relative paths.

---

*End of Report*
![image](https://github.com/user-attachments/assets/7e7f8930-fd09-4dc5-85a0-1cee30dfc67c)
