# Node.js Express Server with Socket.io

This project consists of a Node.js backend server built with Express and Socket.io, along with a frontend that interacts with the server.

## Prerequisites

- Node.js and npm installed on your machine.
- Git installed on your machine.

## Backend Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Dibyendu-13/Dock-Mgmt-System.git
    cd server
    ```

2. **Install backend dependencies:**

    ```bash
    npm install
    ```

3. **Create the CSV file:**

    Ensure you have a CSV file named `dock-in-promise-updated.csv` in the `backend` directory. This file should contain your route master data.

4. **Start the backend server:**

    ```bash
    npm start
    ```

5. **Server will be running at:**

    ```
    http://localhost:5000
    ```

## Frontend Setup

1. **Navigate to the frontend directory:**

    ```bash
    cd client
    ```

2. **Install frontend dependencies:**

    ```bash
    npm install
    ```

3. **Start the frontend server:**

    ```bash
    npm start
    ```

4. **Frontend will be running at:**

    ```
    http://localhost:3000
    ```

## Dependencies

### Backend

- express: Web framework for Node.js
- body-parser: Middleware for parsing incoming request bodies
- cors: Middleware for enabling CORS
- http: Node.js HTTP server
- socket.io: Real-time bidirectional event-based communication
- path: Utility for working with file and directory paths
- fs: File system module for reading files
- csv-parser: Module for parsing CSV files

### Frontend

- axios: Promise-based HTTP client for the browser and node.js
- socket.io-client: Client-side library for Socket.io
- bootstrap: CSS framework for developing responsive and mobile-first websites


## Acknowledgments

- [Express](https://expressjs.com/)
- [Socket.io](https://socket.io/)
- [Bootstrap](https://getbootstrap.com/)
