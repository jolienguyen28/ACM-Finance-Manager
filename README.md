# Finance-Management-Tool
# User Management API

This project is a RESTful API built with Node.js and Express, using an SQLite database to store and manage user information. The API provides endpoints for CRUD (Create, Read, Update, Delete) operations on user data. It includes Swagger documentation for easy exploration of available endpoints.

## Features

- **Express.js**: Backend framework for building APIs.
- **SQLite Database**: Stores user data locally, initialized from an SQL schema file.
- **CRUD Operations**: Endpoints to create, retrieve, update, and delete user records.
- **CORS**: Allows cross-origin requests.
- **Swagger Documentation**: Provides detailed API documentation for easy testing and integration.

## Requirements

- Node.js (>= 14.x)
- npm (Node Package Manager)

## Setup and Installation

1. **Clone the repository**:

   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Initialize the SQLite Database**:
   - Ensure there is an `mysql.sql` file containing the SQL schema for initializing the database.

4. **Run the server**:

   ```bash
   node server.js
   ```

5. **Access Swagger Documentation**:
   - After starting the server, access the API documentation at `http://localhost:3000/api-docs`.

## Project Structure

```plaintext
├── server.js            # Main server file with API endpoints and database setup
├── db.db                # SQLite database file
├── mysql.sql            # SQL schema file for initializing the database
├── swagger.js           # Custom Swagger setup for API documentation
└── public/              # Static files served by the application
```

## Technologies Used

- **Express.js**: Web application framework.
- **SQLite3**: Local database for data storage.
- **Swagger**: API documentation tool.
- **body-parser**: Middleware to parse JSON request bodies.
- **CORS**: Middleware to handle cross-origin requests.
- **File System (fs)**: For reading the SQL schema file during initialization.

## License

This project is licensed under the MIT License.
--- 


