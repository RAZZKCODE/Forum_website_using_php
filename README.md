E-idea - Forum Web Application

Overview

E-idea is a simple and interactive forum-based web application where users can engage in discussions by posting and replying to threads. The platform provides a structured environment for sharing ideas and opinions on various topics.

Features

User Authentication: Login system with session management.

Thread Management: Users can create, view, and reply to discussion threads.

Responsive UI: Built with Bootstrap for mobile-friendly design.

Database Connectivity: Uses MySQL for storing user details and forum posts.

Image Support: Supports images within discussions.

Installation

Prerequisites

A web server with PHP support (e.g., XAMPP, WAMP, LAMP)

MySQL database

A browser to access the application

Steps

Clone or Download the Repository:

git clone https://github.com/your-repo/E-idea.git

Move the Files to Your Web Server Directory:

For XAMPP: Copy the files to htdocs/

For WAMP: Copy the files to www/

Setup the Database:

Import the provided database.sql file into MySQL.

Update db_connect.php with your database credentials.

Run the Application:

Start your server and navigate to http://localhost/E-idea/ in your browser.

File Structure

E-idea/
│-- aboutus.php
│-- Index.php
│-- login.php
│-- Threads.php
│-- Threadlist.php
│-- ViewThreads.php
│-- Part/ (contains reusable components like navbar, database connection)
│-- Images/ (contains UI assets)

Security Considerations

Use password hashing instead of storing passwords in plain text.

Implement proper input validation to prevent SQL injection.

Future Enhancements

User registration system.

Admin panel for managing users and threads.

Email verification during signup.

Author

Rajveer

License

This project is open-source. Modify and use as needed!
