# Basketball Coach
#### Video Demo:  <https://youtu.be/Ola2WrhVhAE>
#### Description
Individual training sessions to boost your basketball career.

* _You need to signup to my account to be able to register for training sessions ._
* 6 Days training sessions. Double ,Only mornings or only in Afternoon
* Register today to see the schedules *

# Features

The application was made with Python ,Flask framework,Sqlite HTML, little bit JavaScript to view the schedule as slideshow, and CSS.

* Python
* Flask
* Sqlite3
* HTML
* CSS
* Javascript

How the webpage works?
The idea is simple. The user can register. During registration you need to enter these fields:

Email
Name
Password: it is checked to match, must be at least 6 symbols long and is hashed after checks are done
Checkbox for what type of user you will be (student or teacher)
Student registration allows you to access student dashboard, where you can see created homework. Entering the homework you can upload a file. Once the teacher grades and reviews your submission it will appear instead of .


# Details
My Final project is a website that allows the user to register and schedule indiviudal basketball training sessions.

Also allows the Coach to use the website as Admin and see all the registrants and all the schedules that users signed up for.

Sessions
The webpage uses sessions to confirm that user is registered. Once the user logins, his credentials are checked. Once everything passes a session is created in flask session (serialized and deserialized) and stored in the cookies. The server attaches user to subsequent requests, so the back-end can easily access the details, like roles: student, teacher.

Database
Database stores all users, admin, schedules. The tables, uses foreign keys to relate users to submitted schedules.

## 🛠 Skills
Python, HTML, CSS SQL
#  🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/grishase)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/serqagrin)
* _@grishase_


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

Learned implementation of routues  or paths,GET AND POST METHODS , HTML , CSS, PYTHON SQL TABLES, working with relational databases.

Planning to follow up with the Back-end Development course from META.


Files
app.py - main file with code that controls page behavior
basketball.db - database with two tables:
1.table of users.
2.Appointments table.
layout.html - Top Nav also shows the session user_id  and adming rights .
about.html-  Home Page with videos and Image Changer make with Java Script.
register.html - registration form.
login.html - login form.
schedule.html / shows the schedule . You can also delete the appointment or booking .
admin.html shows the scheme of applicants that have booked in a training session.
registrants.html made for admin to see which user has signed up and to be able to delete the user id.


About CS50
CS50 is a openware course from Havard University and taught by David J. Malan

Introduction to the intellectual enterprises of computer science and the art of programming. This course teaches students how to think algorithmically and solve problems efficiently. Topics include abstraction, algorithms, data structures, encapsulation, resource management, security, and software engineering. Languages include C, Python, and SQL plus students’ choice of: HTML, CSS, and JavaScript (for web development).

Thank you for all CS50.


