# Security-project

# Overview

This project is a secure web application designed to handle escape room session bookings. The application includes features for user registration, login, room browsing, session booking, and an admin dashboard for managing rooms. Emphasis is placed on ensuring security in various aspects of web development, including input validation, secure password storage, protection against SQL injection, Cross-Site Scripting (XSS), session management, and role-based access control.

# Features

- User Registration: Allows users to create an account with secure password storage.
- User Login: Users can log in securely, with protection against session hijacking.
- Room Browsing: Users can view available escape rooms and book sessions.
- Session Booking: Users can book a session for their desired escape room.
- Admin Dashboard: Administrators can manage rooms, including adding, editing, and deleting room details.
- Security Measures:
  - Protection against SQL injection.
  - Prevention of XSS attacks.
  - Secure password hashing using bcrypt and encryption.
  - Session management to prevent hijacking.
  - Role-based access control for admin and user functionalities.

# Steps to Run the Application

git clone https://github.com/RemasAlmanea/CSC429Security-Project.git
cd CSC429Security-Project

# Testing the Application
User Registration: Navigate to register.php to create a new user account.
User Login: Use login.php to log in with your credentials.
Room Browsing: After logging in, you can browse available escape rooms.
Session Booking: Book sessions for available rooms.
Admin Dashboard: Admin users can add, edit, or delete rooms and manage bookings.
