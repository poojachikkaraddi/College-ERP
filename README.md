# College-ERP
A college management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table.

Installation
Python and Django need to be installed

pip install django
Usage
Go to the College-ERP folder and run

python manage.py runserver

Login
The login page is common for students and teachers.
The username is their name and password for everyone is 'project123'.

Example usernames:
student- 'samarth'
teacher- 'trisila'

Also a new admin user can be created using

python manage.py createsuperuser

Users
New students and teachers can be added through the admin page. A new user needs to be created for each.

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.
Added method to reset attendance time range in Django Admin page.
alt_text
Start Date: Start Date of Attendance period
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range.
