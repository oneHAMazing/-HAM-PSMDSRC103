The School Enrollment System
Final Project: Enrollment System using Python and SQL
Submitted by: Hazel Anne Mozo

This project is my take on the requirements of the project. This is an enrollment system for a school named 'The School'. It was written using Python and sqlite3. Pandas was also used to process the data and matplotlib was used to create bar charts and a pie chart. The program is aimed for student use to create an account, add subjects, remove subjects, finalize their Course List, and get their Timetables. A secret admin menu was also implemented to simulate the reality that there would be an admin backdoor to the system updating things. Also, a part of the requirement was to generate reports and a professor roster. I thought it would make much more sense if that part of the program was in the admin menu rather than the student menu.

We were given a .csv file as our dataset. From that, I built the 6 .csv files. These were used to seed the program as it is. In order to make it work, the FinalProject.ipynb should be in the same folder as the 6 .csv files.

Features:
- import data from CSV files into SQLite tables
- enroll students into available course sections
--- validation: no duplicate enrollments per course
--- validation: unit caps per students
--- validation: class capacity limits
- visual reports

Note on the secret admin menu. It is accessible on the student menu by choosing '7'. It isn't written on the options.
