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

Below are the terminal screenshots demonstrating the working of the application. All images are embedded using HTML `<img>` tags with fixed dimensions.

### Terminal Screenshot 1: Application Launch and Main Menu

<img 
    width="882px" 
    height="550px" 
    alt="Application Launch and Main Menu" 
    src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.47.22%E2%80%AFPM.png" />

### Terminal Screenshot 2: Login Operations

<img 
    width="882px" 
    height="550px" 
    alt="Login Operations" 
    src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.47.27%E2%80%AFPM.png" />

- **Signup a New User:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Signup a New User" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.47.58%E2%80%AFPM.png" />

- **After Signup, Login Check of the New User:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Login Check After Signup" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.48.14%E2%80%AFPM.png" />

- **Change of Password of the User:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Change Password" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.48.44%E2%80%AFPM.png" />

### Terminal Screenshot 3: Student Operations

- **Student Operations:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Student Operations" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.49.00%E2%80%AFPM.png" />

- **Display All Students:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display All Students" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.49.02%E2%80%AFPM.png" />

- **Search Student Record:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Search Student Record" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.49.19%E2%80%AFPM.png" />

- **Add New Student:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Student" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.50.05%E2%80%AFPM.png" />

- **Update Student and Checking the Grades:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Update Student and Check Grades" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.01%E2%80%AFPM.png" />

- **Check Marks:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Check Marks" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.18%E2%80%AFPM.png" />

- **Delete Student:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Student" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.28%E2%80%AFPM.png" />

### Terminal Screenshot 4: Professor Operations

- **Display All Professors:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display All Professors" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.51.52%E2%80%AFPM.png" />

- **Add New Professor:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Professor" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.52.27%E2%80%AFPM.png" />

- **Modify Professor Details:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Modify Professor Details" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%201.53.10%E2%80%AFPM.png" />

- **Show Professor Course Details:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Professor Course Details" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.04.27%E2%80%AFPM.png" />

- **Delete Professor:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Professor" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.04.52%E2%80%AFPM.png" />

### Terminal Screenshot 5: Course Operations

- **Display All Courses:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display All Courses" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.05.10%E2%80%AFPM.png" />

- **Add New Course and Display:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Course" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.05.45%E2%80%AFPM.png" />

- **Delete Course:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Course" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.05.53%E2%80%AFPM.png" />

### Terminal Screenshot 6: Grade Operations

- **Display Grade Operations:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Display Grade Operations" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.06.10%E2%80%AFPM.png" />

- **Adding a New Grade:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Add New Grade" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.06.49%E2%80%AFPM.png" />

- **Modifying a Grade:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Modify Grade" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.07.26%E2%80%AFPM.png" />

- **Delete a Grade:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Delete Grade" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.07.44%E2%80%AFPM.png" />

### Terminal Screenshot 7: Reports & Stats Operations

- **Sort by Name:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Sort by Name" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.00%E2%80%AFPM.png" />

- **Sort by Student Marks:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Sort by Student Marks" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.07%E2%80%AFPM.png" />

- **Average Marks of Course ID DATA200:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Average Marks of Course DATA200" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.22%E2%80%AFPM.png" />

- **Median Marks of All Courses:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Median Marks of All Courses" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.35%E2%80%AFPM.png" />

- **Course-wise Report:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Course-wise Report" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.08.45%E2%80%AFPM.png" />

- **Professor-wise Report:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Professor-wise Report" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.05%E2%80%AFPM.png" />

- **Student-wise Report:**  
  <img 
      width="882px" 
      height="550px" 
      alt="Student-wise Report" 
      src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.18%E2%80%AFPM.png" />

### Terminal Screenshot 8: End of the Operations

At the end of the operation, when we exit the code, the program automatically saves all the data before exiting:

<img 
    width="882px" 
    height="550px" 
    alt="End of Operations" 
    src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.28%E2%80%AFPM.png" />

### Terminal Screenshot 9: Unit Testing Operation

This tests the performance of the code:

<img 
    width="882px" 
    height="550px" 
    alt="Unit Testing Operation" 
    src="https://github.com/Mrnidhi/CheckMyGrade_app/blob/main/README%20files/Terminal%20screenshots/Screenshot%202025-03-16%20at%202.09.55%E2%80%AFPM.png" />

## Conclusion

The CheckMyGrade Application effectively meets the project requirements for managing student grades and related academic data. The modular design and robust implementation ensure that the system is both maintainable and scalable. Unit tests confirm that the major functionalities operate as expected, providing a solid foundation for further enhancements.

## Appendices

- **Source Code:** Refer to `checkmygrade_app.py` and `test_checkmyGrade_app.py` for the complete codebase.
- **Data Files:** CSV files (`Student.csv`, `Course.csv`, `Professor.csv`, `Grades.csv`, `Login.csv`) store persistent data.
- **Class Diagram:** See the image above for the visual representation of the system architecture.
- **Terminal Screenshots:** All relevant terminal screenshots are embedded above.

---

*End of Report*
