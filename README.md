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

<img 
    width="882px" 
    height="550px" 
    alt="Class Diagram" 
    src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/draw.io_final.png" />

## Implementation Details

The project is implemented in Python, with file I/O operations performed via CSV files for data storage.

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

Below are the terminal screenshots demonstrating the working of the application. All screenshots are embedded using HTML `<img>` tags with fixed dimensions.

### Terminal Screenshot 1: Application Launch and Main Menu

<img 
    width="882px" 
    height="550px" 
    alt="Application Launch and Main Menu" 
    src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.47.22_PM.png" />

### Terminal Screenshot 2: Login Operations

<img 
    width="882px" 
    height="550px" 
    alt="Login Operations" 
    src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.47.27_PM.png" />

- **Signup a New User:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Signup a New User" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.47.58_PM.png" />

- **After Signup, Login Check of the New User:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Login Check After Signup" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.48.14_PM.png" />

- **Change of Password of the User:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Change Password" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.48.44_PM.png" />

### Terminal Screenshot 3: Student Operations

- **Student Operations:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Student Operations" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.49.00_PM.png" />

- **Display All Students:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display All Students" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.49.02_PM.png" />

- **Search Student Record:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Search Student Record" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.49.19_PM.png" />

- **Add New Student:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Student" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.50.05_PM.png" />

- **Update Student and Checking the Grades:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Update Student and Check Grades" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.51.01_PM.png" />

- **Check Marks:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Check Marks" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.51.18_PM.png" />

- **Delete Student:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Student" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.51.28_PM.png" />

### Terminal Screenshot 4: Professor Operations

- **Display All Professors:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display All Professors" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.51.52_PM.png" />

- **Add New Professor:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Professor" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.52.27_PM.png" />

- **Modify Professor Details:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Modify Professor Details" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_1.53.10_PM.png" />

- **Show Professor Course Details:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Professor Course Details" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.04.27_PM.png" />

- **Delete Professor:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Professor" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.04.52_PM.png" />

### Terminal Screenshot 5: Course Operations

- **Display All Courses:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display All Courses" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.05.10_PM.png" />

- **Add New Course and Display:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Course" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.05.45_PM.png" />

- **Delete Course:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Course" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.05.53_PM.png" />

### Terminal Screenshot 6: Grade Operations

- **Display Grade Operations:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display Grade Operations" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.06.10_PM.png" />

- **Adding a New Grade:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Grade" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.06.49_PM.png" />

- **Modifying a Grade:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Modify Grade" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.07.26_PM.png" />

- **Delete a Grade:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Grade" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.07.44_PM.png" />

### Terminal Screenshot 7: Reports & Stats Operations

- **Sort by Name:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Sort by Name" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.08.00_PM.png" />

- **Sort by Student Marks:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Sort by Student Marks" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.08.07_PM.png" />

- **Average Marks of Course ID DATA200:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Average Marks of Course DATA200" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.08.22_PM.png" />

- **Median Marks of All Courses:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Median Marks of All Courses" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.08.35_PM.png" />

- **Course-wise Report:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Course-wise Report" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.08.45_PM.png" />

- **Professor-wise Report:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Professor-wise Report" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.09.05_PM.png" />

- **Student-wise Report:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Student-wise Report" 
      src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.09.18_PM.png" />

### Terminal Screenshot 8: End of the Operations

At the end of the operation, when we exit the code, the program automatically saves all the data before exiting:

<img 
    width="882px" 
    height="550px" 
    alt="End of Operations" 
    src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.09.28_PM.png" />

### Terminal Screenshot 9: Unit Testing Operation

This tests the performance of the code:

<img 
    width="882px" 
    height="550px" 
    alt="Unit Testing Operation" 
    src="./README_files/Terminal_screenshots/Screenshot_2025-03-16_2.09.55_PM.png" />

## Conclusion

The CheckMyGrade Application effectively meets the project requirements for managing student grades and related academic data. The modular design and robust implementation ensure that the system is both maintainable and scalable. Unit tests confirm that the major functionalities operate as expected, providing a solid foundation for further enhancements.

## Appendices

- **Source Code:** Refer to `checkmygrade_app.py` and `test_checkmygrade_app.py` for the complete codebase.
- **Data Files:** CSV files (`Student.csv`, `Course.csv`, `Professor.csv`, `Grades.csv`, `Login.csv`) store persistent data.
- **Class Diagram:** See the image above for the visual representation of the system architecture.
- **Terminal Screenshots:** All relevant terminal screenshots are embedded above.

---

*End of Report*
