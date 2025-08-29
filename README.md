# Student-Attendance-System-
a GUI-based desktop application for automated student attendance tracking

Student Management System in Python
python gui database licnese

Introduction :
Student Management System is made using python with tkinter gui and Database used is mysql. This management system consists of the Superadmin login,admin login, faculty login, student login. This can make the work of the college more simple.


Modules Used :
Tkinter
mysql-connector python
tkcalendar
tktooltip
PIL (Python Imaging Library)
Working :
✳️Types of Login -

Super Admin - Super admin can add the admin and manages the admin or he can update the admin or can change his own password.
Admin - Admin can add the faculty, manage the faculty, add the student, manages the Student and can update the fees record or add the fees record.
Faculty - Faculty can mark the attendance for the specified date by selecting the class and division. Faculty can also view the student records. Faculty can assign the class teacher by themselves only.
Student - Student can see his profile and can view his attendance history or fees paid history.

✳️ Database Design -

The database is design in such a way that when a student, admin or faculty is added the database automatically assigns the id to them. I have used the concept like stored procedure, function and triggers to do this process. Also the attendance can be recorded and used such query.

Project Video Link :
If you want to see the detail output of my project - Click here

Installation Process :
If you want to do this project then fork this project or clone using the following command :

git clone [https://github.com/devikakumawat08/Student-Attendance-System-.git]
Please Make Sure : The Mysql database should be installed. The following python modules should be installed mentioned below the introduction. To Install the Python Module : Use the following command

pip install pillow

pip install tkcalendar

pip install tktooltip

pip install mysql-connector

Make the database using the dump folder in the Reports folder or just execute one by one query in report folder filename *sql_file.sql*.
In the config.ini file insert your database user, host and password otherwise the error will be occured.


Run these python file :
py app.py
Author : Devika Kumawat
