# Student_Enrollment 
In this project, the aim is to develop a student enrollment registration page for a Django web application that allows users to enroll students without refreshing the page (AJAX). It also generates CSV and PDF exports of same student enrollment data. The admin access is also available.

# Set up Django App
django-admin startproject school

cd school

django-admin startapp enrollment

pip install reportlab



# Making Migrations
python manage.py makemigrations

python manage.py migrate

# Run
python manage.py runserver

# Expected Output

