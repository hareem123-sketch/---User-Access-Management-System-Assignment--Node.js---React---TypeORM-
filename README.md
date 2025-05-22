This is a User Access Management System built using Node.js, Express, and TypeScript. The system allows for user authentication and authorization with role-based access control (RBAC). Users can sign up, log in, and access specific routes based on their roles.

Key Features:
User Registration (Signup): Users can create an account by providing an email, password, and role (Employee, Manager, Admin).

User Login: Existing users can log in with their credentials (email and password).

Role-Based Access Control: Users have different roles (Employee, Manager, Admin) with different access levels.

JWT Authentication: JSON Web Tokens (JWT) are used for securing API routes and ensuring authorized access.

Protected Routes: Certain routes are protected and require the user to be authenticated (i.e., token verification).

Technologies Used:
Node.js and Express for building the backend API.

TypeScript for static typing and improved developer experience.

JWT for secure user authentication.

Sequelize and PostgreSQL for interacting with the database.

Installation:
Clone the repository: git clone https://github.com/yourusername/user-access-system.git

Navigate into the project folder: cd user-access-system

Install dependencies: npm install

Set up your environment variables (e.g., JWT secret key, database connection).

Run the application: npm start
