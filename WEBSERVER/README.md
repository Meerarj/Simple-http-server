# WEBSERVER 

 This is a simple Go project that demonstrates a basic web server with two handlers: one for handling a form submission and another for a simple "hello" message.
## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)

## Features

- **Form Handler:** Accepts POST requests with form data and displays the submitted values.
- **Hello Handler:** Responds with a "hello!" message for GET requests to the "/hello" endpoint.

### Prerequisites

Ensure you have the following installed:

- Go (version X.X.X)


## Getting Started
- Clone the repository and build the project.
- Run the server using 
```bash
git clone https://github.com/yourusername/your-go-webserver.git
cd your-go-webserver
go build
go run main.go
```
Access the following endpoints in your web browser or using tools like curl:

    http://localhost:8080/ (serves static files)
    http://localhost:8080/form (form handler)
    http://localhost:8080/hello (hello handler)
