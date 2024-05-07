# HTTP and Socket Server

- Master of Science: Data Science and Data Analytics

This is a simple HTTP and Socket server implementation in Python using multiprocessing for concurrency and MongoDB for storing data.

## Features

- HTTP server serving static files such as HTML, CSS, and images.
- Socket server receiving data from the HTTP server and storing it in MongoDB.
- Provides error handling for 404 Not Found errors.

## File Structure

- `server.py`: Main script containing the HTTP and Socket server implementations.
- `front-init/`: Directory containing static files served by the HTTP server.
- `front-init/ error.html`: Error page for 404 responses.

## Requirements

- Python 3.x
- MongoDB
- Docker

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
