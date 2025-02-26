# Simple REST API with Node.js

This project is a simple REST API built using Node.js without any external libraries. It uses the built-in `http` module to handle HTTP requests and the `fs/promises` module to store data in a `db.json` file.

## Features

- Basic CRUD operations (Create, Read, Update, Delete)
- Data storage in a JSON file (`db.json`)

## Getting Started

### Prerequisites

- Node.js installed on your machine

### Installation

1. Clone the repository:
  ```sh
  git clone https://github.com/Cassiano26/project-01-fundamentals-backend.git
  ```
2. Navigate to the project directory:
  ```sh
  cd project-01-fundamentals-backend
  ```

### Usage

1. Start the server:
  ```sh
  npm run dev
  ```
2. The server will be running on `http://localhost:3333`.

### API Endpoints

- `GET /users` - Retrieve all users
- `GET /users/:id` - Retrieve a single users by ID
- `POST /users` - Create a new user
- `PUT /users/:id` - Update an existing user by ID
- `DELETE /users/:id` - Delete an user by ID

## License

This project is licensed under the MIT License.
