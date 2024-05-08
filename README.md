## GO, MARY KIERINE
## BSIT-32E1
## IT ELECTIVE 3 - MIDTERM 
### MIDTERM ASSIGNMENT: Onion Architecture, MVC, and Web API (.NET Core)

### Introduction:
This ReadMe outlines the architecture and functionality of a web application built with Onion Architecture. The application focuses on implementing basic authentication features without relying on external libraries like ASP.NET Identity or Entity Framework.

### Workflow:
1. **User Registration:**
   - Validates input for username and password.
   - Securely stores hashed credentials in memory.
   - Redirects user upon successful registration.

2. **User Login:**
   - Validates user credentials against stored hashes.
   - Establishes user session upon successful authentication.
   - Limits login attempts and provides informative error messages.

### Conclusion:
The Onion Architecture approach emphasizes security, separation of concerns, and scalability. However, this demonstration lacks features like password reset and persistent storage, which would be essential in a production environment.
