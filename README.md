# ChatRoom

ChatRoom is a simple chat room application built using HTML, CSS, JavaScript, PHP, and MySQL. It allows users to register, log in, and chat with each other in real-time.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Registration: New users can register with a username and password.
- User Login: Returning users can log in with their credentials.
- Real-time Chat: Users can send and receive messages in real-time.
- User Authentication: Ensures that only registered users can access the chat room.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/HEYADITI1/ChatRoom.git
Navigate to the project directory:

sh
Copy code
cd ChatRoom
Set up the database:

Import the provided SQL file (chatroom.sql) into your database management system (e.g., phpMyAdmin).
Update the database configuration in php/db.php with your database credentials.
Start the local server (e.g., using XAMPP, WAMP, or MAMP):

Move the project directory to the htdocs folder if you're using XAMPP.
Start Apache and MySQL from the XAMPP control panel.
Usage
Open your web browser and navigate to http://localhost/ChatRoom.
Register a new account or log in with an existing account.
After logging in, you will be redirected to the main chat room page.
Start chatting with other registered users in real-time.
Folder Structure
sql
Copy code
ChatRoom/
├── css/
│   ├── login.css
│   └── style.css
├── js/
│   └── script.js
├── php/
│   ├── addmsg.php
│   ├── db.php
│   ├── index.php
│   ├── login.php
│   └── readMsg.php
├── sql/
│   └── chatroom.sql
├── index.html
└── README.md
Screenshots
Login Page

Registration Page

Chat Room

Technologies Used
Frontend:

HTML
CSS
JavaScript
Backend:

PHP
MySQL
Contributing
Contributions are welcome! Please follow the steps below to contribute to this project:

Fork the repository.
Create your feature branch (git checkout -b feature/new-feature).
Commit your changes (git commit -am 'Add some feature').
Push to the branch (git push origin feature/new-feature).
Create a new Pull Request.

sql








