
# e-Learning Management System
A learning management and online assessment system for academic education.





## Features

- Admin adds courses, teachers, and students and assigns them courses.
- The teacher creates course content, announcements, assignments, quizzes, takes attendance, etc. A teacher can see the details and analysis of the assessments.
- Students can enroll in the courses using the access key, see the course content of the enrolled courses, participate in assessments and see their results in detail.
- Discussion section for both teacher and student.

## Relational Schema
![schema](https://user-images.githubusercontent.com/87283264/187967219-55bea00e-3151-488a-a4be-d2a95b9d8a5c.png)

## Tech Stack
1. Django 4.0.4
2. Bootstrap 5.0.2
3. jQuery 3.6.0
5. Chart.js v3.9.1
4. Animate.css 4.1.1

##UI
![Screenshot (65)](https://user-images.githubusercontent.com/87283264/194387627-47bc4506-5acb-46da-8ae0-70ea1e7e4eb8.png)
![Screenshot (70)](https://user-images.githubusercontent.com/87283264/194387776-552bdd11-9252-4be2-8139-10e0f270c09f.png)
![Screenshot (67)](https://user-images.githubusercontent.com/87283264/194387798-77c6ba2c-9089-4469-88e0-282191535211.png)
![Screenshot (68)](https://user-images.githubusercontent.com/87283264/194387811-bd22cd8c-854c-4849-9aa9-0a71b53494a2.png)
![Screenshot (69)](https://user-images.githubusercontent.com/87283264/194387822-649bd890-cb57-47b5-b380-4e30499ae142.png)


## Run Locally

1. Clone the project
```bash
git clone https://github.com/nz-m/eLMS-SWE.git
```
2. Go to the project directory
```bash
cd eLMS-SWE
```
3. Create a virtual environment and activate it (Windows)
```bash
python -m venv env
```
```bash
env\Scripts\activate
```
4. Install dependencies

```bash
pip install -r requirements.txt
```
5. Make migrations and migrate
```bash
python manage.py makemigrations
```
```bash
  python manage.py migrate
```
6. Create admin/superuser
```bash
python manage.py createsuperuser
```
7. Finally run the project
```bash
python manage.py runserver
```
Now the project should be running on http://127.0.0.1:8000/

Login as admin and add some courses, teacher and students.


## License
[The MIT License (MIT)](https://github.com/nz-m/eLMS-SWE/blob/main/LICENCE)


