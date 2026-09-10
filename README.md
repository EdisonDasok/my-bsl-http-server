# BSL HTTP Server

## Project Description

This project is a low-level HTTP web server developed using the Bonezegei Scripting Language (BSL) and the BSL_Socket library. It demonstrates how a web server creates a TCP socket, listens on port 8080, accepts browser requests, identifies the requested path, and returns a complete HTTP response.

The server supports a default landing page, an About page, and a custom 404 error page for unmapped routes.

## Learning Objectives

This project demonstrates the following concepts:

- Creating and initializing a TCP socket
- Binding a web server to port 8080
- Listening for and accepting client connections
- Reading HTTP GET requests
- Extracting and evaluating request paths
- Constructing HTTP response headers and HTML bodies
- Returning correct HTTP status codes
- Closing each client connection after sending a response

## Technologies Used

- Bonezegei Scripting Language
- BSL_Socket Library
- GitHub Codespaces
- Visual Studio Code
- HTTP/1.1
- TCP sockets

## Repository Structure

```text
my-bsl-http-server/
├── .gitattributes
├── LICENSE
├── README.md
├── src/
│   └── http.bzg
└── documentation/
    ├── home.png
    ├── about.png
    ├── 404.png
    └── terminal.png