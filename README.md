# FL BlogSpace

A Python and Flask-based web application that allows users to register, log in, and create persistent blog posts.  
This project demonstrates core backend web development concepts including routing and authentication using Python Flask and database integration using SQLite.

## Features

* User registration and login system with password hashing
* Session-based authentication
* Create and view blog posts
* SQLite database integration
* Modular Flask structure that uses Blueprints
* Clean responsive UI using HTML and CSS styling
* Error messages for user feedback

## Technologies Used

* Python
* Flask
* SQLite
* Werkzeug Security (for password hashing)
* HTML
* CSS

## Build Instructions
1) Download/Clone the repo
2) Use Python version 3.13 or later
3) Download Python Flask
4) Go to Terminal
5) Set your current terminal directory to the project directory (FL BlogSpace)
6) Use the command 'flask --app flask_app:create_app init-db' to initialise/reset the SQLite database
7) Use the command 'flask --app flask_app:create_app run' to run the app
8) Go to http://127.0.0.1:5000 on your browser to access the app locally
