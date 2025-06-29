# Go CRUD API

A lightweight and easy-to-understand RESTful API built with Go. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations using native Go packages, making it ideal for beginners looking to understand how APIs work in Go without relying on third-party frameworks.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project serves as a minimal yet functional template for building REST APIs in Go. It handles HTTP requests and provides endpoints to perform CRUD operations on an in-memory dataset or a MySQL backend (if extended). The goal is to make understanding Go’s `net/http` and `encoding/json` packages easier through real-world application.

## Features

- Clean and minimal codebase
- In-memory CRUD operations
- JSON request and response handling
- Modular function separation
- Easily extensible to include a database like MySQL or PostgreSQL

## Technologies Used

- **Go**: The primary language used to build the API.
- **net/http**: Standard Go library for HTTP server.
- **encoding/json**: Standard Go library for JSON marshaling and unmarshaling.

## Project Structure

```
CRUD_Api_Go-main/
├── main.go             # Entry point for the API server
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites

Ensure that you have Go installed:

```bash
go version
```

### Clone the Repository

```bash
git clone https://github.com/mrkankilic27/crud-api-go.git
cd crud-api-go
```

### Run the API

```bash
go run main.go
```

The API server will start on:

```
http://localhost:8080
```

## Usage

You can use tools like **Postman**, **cURL**, or any HTTP client to interact with the API.

Example using `curl`:

```bash
curl http://localhost:8080/products
```

## API Endpoints

| Method | Endpoint           | Description             |
|--------|--------------------|-------------------------|
| GET    | /products          | Get all products        |
| GET    | /products/{id}     | Get product by ID       |
| POST   | /products          | Create a new product    |
| PUT    | /products/{id}     | Update a product        |
| DELETE | /products/{id}     | Delete a product        |

## Contributing

Contributions are welcome. If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

**Author:**  
[Mertcan Kankılıç](https://github.com/mrkankilic27)  
mertcankankilic27@gmail.com