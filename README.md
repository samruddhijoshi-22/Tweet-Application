# Tweet-Application
A simple, Twitter-like web application built with Django. This project lets users register, log in, post tweets, upload images, and interact with the platform through a clean and responsive user interface. Perfect for learning Django while implementing core social media features.

 Key Features
1. Tweet Management: Create, edit, and delete tweets with ease
2. Image Uploads: Attach images to tweets for enhanced media sharing
3. User Authentication: Register, log in, and securely manage user sessions
4. Admin Panel: Manage users and tweets through the Django Admin interface
5. Responsive UI: Mobile-friendly design using HTML, CSS, and Bootstrap
6. Basic CRUD Operations: Full Create, Read, Update, and Delete functionality for tweets

Tech Stack:
• Backend: Django, Python
• Frontend: HTML5, CSS3, Bootstrap
• Database: SQLite (default, can be switched to PostgreSQL/MySQL)
• Other Tools: Django Admin, Django Media handling for image uploads

Before starting the project, make sure Django is installed on your system.
Getting Started
1. Install Dependencies
Before starting the project, make sure Django is installed on your system.
pip install django

3. Set Up the Project
Navigate to the project directory and run the following commands to set up the database:
python manage.py migrate

3. Start the Development Server
Now, command to run the server:
python manage.py runserver

Project Structure:
main/ – Main Django project directory.
tweet/ – Django app handling tweet creation, editing, and deletion.
tweet/templates/ – Contains HTML templates for tweet-related forms.
main/registration/ – Holds templates for login and logout pages.

Future Enhancements
• User Profiles – Add profile pictures, bios, and follower/following features.
• Like and Comment System – Allow users to like tweets and leave comments.
• Hashtags and Search – Enable hashtag usage and search functionality for tweets and users.










