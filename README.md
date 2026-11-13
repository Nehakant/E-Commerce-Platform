
# E-Commerce Platform

A full-stack e-commerce web application developed as part of **Seasons of Code, Web and Coding Club, IIT Bombay**.

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Frontend:** EJS, HTML, CSS, JavaScript
- **Authentication:** bcrypt, session-based authentication

## Features

- **User Authentication:** Secure registration and login with password hashing and session management.
- **Product Management:** Browse and view available products.
- **Shopping Cart:** Add, remove, and manage products with quantity validation.
- **Database Integration:** PostgreSQL integration using relational tables and SQL queries.
- **Order Processing:** Transaction-based checkout with order creation, inventory updates, and cart clearing.
- **Data Integrity:** SQL transactions with rollback handling to maintain database consistency.

## Project Structure

```text
.
├── app.js
├── views/
└── README.md
```

## Installation and Setup

### 1. Set Up PostgreSQL

Create the required database and configure the database schema before running the application.

### 2. Start the Application

```bash
node app.js
```

Open your browser and navigate to:

```text
http://localhost:3000
```

## Key Implementation Details

- Used parameterized SQL queries to help prevent SQL injection.
- Implemented password hashing using bcrypt.
- Used session-based authentication to manage user sessions.
- Used PostgreSQL transactions (`BEGIN`, `COMMIT`, `ROLLBACK`) for checkout operations.

## Author

**Neha Kant**  
IIT Bombay  
[GitHub](https://github.com/Nehakant)
