# Spring-Boot-Web-Security
This project demonstrates the integration of Spring Security with basic form-based authentication, role-based access control (RBAC), and a simple in-memory user management system. The application is designed to provide secure login and access control to various pages based on user roles.
Features
Authentication:

A simple form-based authentication system for login.
User credentials are verified using an in-memory user store.
Role-Based Access Control (RBAC):

Users can be assigned roles (e.g., USER).
Specific endpoints are protected and require the user to be authenticated before accessing them.
In-Memory User Store:

A user with the username profound and the password 12345 is configured as the default user.
The user is granted the USER role.
Custom Security Configuration:

/home and / (home page) are publicly accessible.
/login is the login page, accessible to all users.
All other pages require authentication.
Logout Functionality:

A simple logout form allows the user to log out from the session.

