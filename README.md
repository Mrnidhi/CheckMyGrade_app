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

> If the class diagram does not display, consider removing spaces from the folder/file name.

![Class Diagram](<./README files/draw.io_final.png>)

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

Below are embedded images demonstrating the terminal outputs. If the images do not render, rename your files/folders to remove spaces or percent-encode them.

### Terminal Screenshot 1: Application Launch and Main Menu

![Screenshot 1](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.47.22 PM.png>)

### Terminal Screenshot 2: Login Operations

![Screenshot 2](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.47.27 PM.png>)

- **Signup a new user**  
  ![Signup](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.47.58 PM.png>)

- **After signup, login check of the new user**  
  ![Login check](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.48.14 PM.png>)

- **Change of Password of the user**  
  ![Change Password](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.48.44 PM.png>)

### Terminal Screenshot 3: Student Operations

- **Student operations**  
  ![Student operations](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.49.00 PM.png>)

- **Display all students**  
  ![All students](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.49.02 PM.png>)

- **Search Student Record**  
  ![Search student](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.49.19 PM.png>)

- **Add New Student**  
  ![Add student](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.50.05 PM.png>)

- **Update student and checking the grades**  
  ![Update student](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.51.01 PM.png>)

- **Check Marks**  
  ![Check marks](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.51.18 PM.png>)

- **Delete Student**  
  ![Delete student](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.51.28 PM.png>)

### Terminal Screenshot 4: Professor Operations

- **Display all professors**  
  ![All professors](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.51.52 PM.png>)

- **Add New Professor**  
  ![Add professor](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.52.27 PM.png>)

- **Modify professor details**  
  ![Modify professor](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 1.53.10 PM.png>)

- **Show Professor course details**  
  ![Professor course details](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.04.27 PM.png>)

- **Delete Professor**  
  ![Delete professor](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.04.52 PM.png>)

### Terminal Screenshot 5: Course Operations

- **Display all courses**  
  ![All courses](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.05.10 PM.png>)

- **Add new Course and display**  
  ![Add course](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.05.45 PM.png>)

- **Delete course**  
  ![Delete course](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.05.53 PM.png>)

### Terminal Screenshot 6: Grade Operations

- **Display grade operations**  
  ![Display grades](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.06.10 PM.png>)

- **Adding a new grade**  
  ![Add grade](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.06.49 PM.png>)

- **Modifying a Grade**  
  ![Modify grade](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.07.26 PM.png>)

- **Delete a grade**  
  ![Delete grade](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.07.44 PM.png>)

### Terminal Screenshot 7: Reports & Stats Operations

- **Sort by name**  
  ![Sort by name](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.08.00 PM.png>)

- **Sort by student marks**  
  ![Sort by marks](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.08.07 PM.png>)

- **Average marks of course ID DATA200**  
  ![Average marks](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.08.22 PM.png>)

- **Median marks of all courses**  
  ![Median marks](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.08.35 PM.png>)

- **Course-wise report**  
  ![Course-wise report](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.08.45 PM.png>)

- **Professor-wise report**  
  ![Professor-wise report](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.09.05 PM.png>)

- **Student-wise Report**  
  ![Student-wise report](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.09.18 PM.png>)

### Terminal Screenshot 8: End of the Operations

At the end of the operation, when we exit the code, the program automatically saves all the data before exiting:

![End of operations](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.09.28 PM.png>)

### Terminal Screenshot 9: Unit Testing Operation

This tests the performance of the code:

![Unit testing](<./README files/Terminal screenshots/Screenshot 2025-03-16 at 2.09.55 PM.png>)

## Conclusion

The CheckMyGrade Application effectively meets the project requirements for managing student grades and related academic data. The modular design and robust implementation ensure that the system is both maintainable and scalable. Unit tests confirm that the major functionalities operate as expected, providing a solid foundation for further enhancements.

## Appendices

- **Source Code:** Refer to `checkmygrade_app.py` and `test_checkmygrade_app.py` for the complete codebase.
- **Data Files:** CSV files (`Student.csv`, `Course.csv`, `Professor.csv`, `Grades.csv`, `Login.csv`) store persistent data.
- **Class Diagram:** See the image linked above for the visual representation of the system architecture.
- **Terminal Screenshots:** All relevant terminal screenshots are attached above.

---

*End of Report*
