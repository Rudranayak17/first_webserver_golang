# Simple Go Web Server

This is a simple web server written in Go (Golang) using the standard library's `net/http` package.

## Features

- Serves static files from the `./static` directory.
- Handles a form submission and prints the submitted data.
- Responds with "Hello!" on a GET request to `/hello`.

## Prerequisites

- Go (Golang) installed on your machine.

## How to Use

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/Rudranayak17/first_webserver_golang
    ```

2. Navigate to the project directory:

    ```bash
    cd cd first_webserver_golang
    ```

3. Run the web server:

    ```bash
    go run main.go
    ```

4. Open your web browser and visit `http://localhost:8080` to see the server in action.

## Routes

- `/` : Serves static files from the `./static` directory.
- `/form` : Handles form submissions and prints the submitted data.
- `/hello` : Responds with "Hello!" on a GET request.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
