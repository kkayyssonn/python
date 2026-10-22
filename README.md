Project Overview
The Student Gradebook System is a system designed to manage student records, track their grades for each subject (Maths, Agriculture, Statistics and Biology). It also allows the user to calculate the student's overall grades

Setup Instructions
1. Download the Pycharm software application
2. Download and load the Phemo Thabatshe sec F.py file into Pycharm
3. In Pycharm make sure you are running the current file which is the Phemo Thabatshe sec F.py tab
4. After running the code you are greeted with a Menu in the output that gives you 7 choices that allow the user to interact with the system.

Features List
- Add student: function that adds new students together with their grades
- Update student: function that modifies or changes the grades of an existing student
- Remove student: removes a chosen student's data
- Search student: finds a specific student by name and displays their grades and average
- Show summary: prints a table showing all the student's grades and the averages for each subject
- Sort by Average: Sorts the student data (using bubble sort) to identify top performing students
- Exit: exits the program

Class Architecture
Student Class: this represents a single entity that handles an individual student's name and average calculations
Gradebook Class: this class is the manager of the student data. It handles the student data and allows operations like adding, sorting, searching, removing and show the summary of student data
I also have custom exception classes being:

- StudentNotFoundError: raised when the user tries operating on a student that does not exist
- InvalidGradeError:  raised when a grade is not within the given range between 0 to 100

Example Input/Output
<img width="1920" height="1080" alt="Screenshot (395)" src="https://github.com/user-attachments/assets/815f15c8-54d7-4d7c-9b3a-d2610e2610af" />
<img width="1920" height="1080" alt="Screenshot (396)" src="https://github.com/user-attachments/assets/5b6c3a18-bffc-4ea1-bdc0-190730dbc285" />

Assumptions and Limitations
- Student names are case-sensitive. E.g. Phemo and phemo are treated as 2 different people
- Grades are limited to only numeric values that are in between 0 and 100
- When the program is stopped or is exited, all student data is lost
- The subjects (Maths, Agriculture, Statistics and Biology) cannot be changed by the user
- the names are restricted to letters, spaces, hyphens and apostrophes

Testing Summary
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f97f93bb-1e4c-46db-862a-f141ccd3aa4a" />

Known Issues
As said in the limitations, when the program is closed or exited in the menu, all data is lost

References
Lambert, K. A. (2019). Fundamentals of Python: First Programs (2nd ed.). Cengage Learning.
