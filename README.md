## GO, MARY KIERINE
## BSIT-32E1
## IT ELECTIVE 3 - MIDTERM 
### MIDTERM ASSIGNMENT LOGIN: Onion Architecture, MVC, and Web API (.NET Core)

### Introduction:
This ReadMe outlines the architecture and functionality of a web application built with Onion Architecture. The application focuses on implementing basic authentication features without relying on external libraries like ASP.NET Identity or Entity Framework.

### Workflow:
1. **User Registration:**
   - Validates input for username and password.
   - Securely stores credentials in memory.
   - Redirects user upon successful registration.

2. **User Login:**
   - Validates user credentials.
   - Establishes user session upon successful authentication.
   - Limits login attempts and provides informative error messages.
## USER REGISTRATION
**When a new user tries to register, the register action in login. This action takes the username, email, and password as parameters.**
## USER LOGIN 
**When the user wants to login it would likely involve a similar action that takes a username, password, checks if a user with those credentials exists and if so logs the user in and redirects to a secure page.**
**

### Conclusion:
The Onion Architecture approach emphasizes security, separation of concerns, and scalability. However, this demonstration lacks features like password reset and persistent storage, which would be essential in a production environment.
