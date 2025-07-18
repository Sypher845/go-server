# Go Server Project

This is a simple Go server project that serves static files and handles basic HTTP requests.

## Features
- Serves static HTML files from the `static` directory.
- Handles a form submission via the `/form` endpoint.
- Provides a simple "Hello, World!" endpoint at `/hello`.

## Project Structure
```
d:\Go\src\go-server\
│
├── static\
│   ├── index.html   # Static homepage
│   ├── form.html    # Form submission page
│
├── main.go          # Main Go server code
└── README.md        # Project documentation
```

## Prerequisites
- Go installed on your system (https://golang.org/dl/).

## Setup Instructions
1. Clone the repository or copy the project files to your local machine.
2. Navigate to the project directory:
   ```bash
   cd d:\Go\src\go-server
   ```
3. Run the Go server:
   ```bash
   go run main.go
   ```

## Usage
1. Open your browser and navigate to `http://localhost:8080/` to view the static homepage.
2. Visit `http://localhost:8080/form.html` to access the form submission page.
3. Submit the form to see the server process the input and display the submitted data.
4. Access `http://localhost:8080/hello` to see the "Hello, World!" message.

## Endpoints
- `/` - Serves static files from the `static` directory.
- `/form` - Handles POST requests for form submissions.
- `/hello` - Responds with "Hello, World!" for GET requests.


