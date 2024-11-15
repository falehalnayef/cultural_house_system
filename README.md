# cultural_house_system

The **Cultural House System (CHS)** is a backend application designed to manage orders, bookings, and users within an organization that provides entertainment offers. It supports functionalities like creating, updating, and deleting orders, managing bookings, and handling user accounts and Real-time communication through Server-Sent Events.

## Project Status

This project is designed to provide comprehensive functionality for managing a cultural house in real-life scenarios. It was developed as part of a university project.

## Features

- **Order Management**:
  - Create, update, and delete orders.
  - Track order status (e.g., checked in/out).
  - View booking history.

- **Booking Management**:
  - Create, join, search for, and interact with bookings.
  - Add/remove users from bookings.
  - Delete bookings and manage booking ownership.

- **User Management**:
  - Create, login, and retrieve user accounts.
  - Secure authentication and authorization for users.

- **Real-Time Communication**:
  - Implements **Server-Sent Events (SSE)** to provide real-time updates for orders, bookings, and user actions.

## Installation

### 1. Clone the Repository

git clone https://github.com/falehalnayef/cultural_house_system.git




2. **Install Dependencies**:

    go to the project directory
    npm install


3. **Set Up Environment Variables**:

    - Create a `.env` file in the root directory.
    - Configure environment variables as needed. Example:

  ```
        DB_HOST=localhost
        DB_PORT=5432
        DB_NAME=chs
        DB_USER=postgres
        DB_PASSWORD=7119
        PORT=3000
        SECRET=skjfasd3as1d2sf13sd51fSADASD
        EMAIL=your_email@example.com
        EMAIL_PASSWORD=your_email_password
        UPLOAD_PATH=/uploads

  ```

## Usage

- **Start the Application**:

    npm start


    - The application will be running at `http://localhost:3000` by default.

## Dependencies

- Express.js
- Sequelize (ORM for PostgreSQL)
- bcrypt (Password hashing)
- cors (Cross-Origin Resource Sharing)
- jsonwebtoken (JWT authentication)
- morgan (HTTP request logging)
- pg (PostgreSQL client)
- dotenv (Environment variables)
- SSE: Real-time communication through Server-Sent Events.
