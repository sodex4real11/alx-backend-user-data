User authentication service; The ALX Project
This project implements a user authentication service using Flask, SQLAlchemy, and bcrypt for password hashing. The authentication service includes functionality for user registration, login,logout,profile access,password reset,and password update.

The project is organized into multiple modules:

main.py: Contains functions to test various functionalities of the authentication service.
auth.py: Implements the Auth class, which interacts with the authentication database.
db.py: Defines the DB class responsible for database operations.
user.py: Declares the SQLAlchemy model User representing the users table.
