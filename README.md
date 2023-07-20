# EduPro
Project contains the 3 roles:
1)Admin
2)Teacher
3)student

A. Admin Users Can
See Overall Summary Charts of Students Performances, Staff Performances, Courses, Subjects, Leave, etc.
Manage Staff (Add, Update and Delete)
Manage Students (Add, Update and Delete)
Manage Course (Add, Update and Delete)
Manage Subjects (Add, Update and Delete)
Manage Sessions (Add, Update and Delete)
View Student Attendance
Review and Reply Student/Staff Feedback
Review (Approve/Reject) Student/Staff Leave
B. Staff/Teachers Can
See the Overall Summary Charts related to their students, their subjects, leave status, etc.
Take/Update Students Attendance
Add/Update Result
Apply for Leave
Send Feedback to HOD
C. Students Can
See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
View Attendance
View Result
Apply for Leave
Send Feedback to HOD

Running Process Of The Project:
1)MySqlSetUphttps://www.youtube.com/watch?v=YSOY_NyOg40
2) student-management-using-django/student_management_system/settings.py
update the file:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'Databasename', //Dbname
        'USER': 'root',
        'PASSWORD': 'password', //Password of the sql at the time of the sql installation
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
3)After unzipping  the file :
->python -m venv venv
->venv\scripts\activate
->cd student-management-using-django
pip install Django
pip3 install -r requirements.txt
python manage.py createsuperuser
->Give the details in the terminal
->python manage.py makemigrations
python manage.py migrate

Note:Only admin can add the students and staff 
