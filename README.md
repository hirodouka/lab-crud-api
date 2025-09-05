# lab-crud-api

A simple CRUD API built with Node.js and Express.

## Overview

This project provides a basic structure for a CRUD (Create, Read, Update, Delete) API. It is designed as a starter template for building RESTful APIs, with a clear folder structure and modular code organization.

## Features

- RESTful endpoints for CRUD operations
- Organized codebase with separate directories for configuration, controllers, and routes
- Easily extendable for more complex business logic

## Project Structure

```
.
├── config/         # Configuration files (DB, environment, etc.)
├── controllers/    # Business logic for API endpoints
├── routes/         # Express route definitions
├── server.js       # Application entry point
├── package.json    # Project metadata and dependencies
└── package-lock.json
```

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/hirodouka/lab-crud-api.git
   cd lab-crud-api
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the development server:

   ```sh
   node server.js
   ```

   The server should now be running on `http://localhost:3000` (or your configured port).

## Usage

- Use tools like [Postman](https://www.postman.com/) or `curl` to interact with the API endpoints.
- Endpoints are defined in the `routes/` and implemented in `controllers/`.

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is released under an open license. See `LICENSE` if available.

---

Created by [hirodouka](https://github.com/hirodouka)
