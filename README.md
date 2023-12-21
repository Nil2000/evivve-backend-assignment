# evivve-backend-assignment

# Socket.io Chat Server

This is a simple chat server using Node.js, Express, and Socket.io.

## Prerequisites

- Node.js installed on your machine.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Nil2000/evivve-backend-assignment.git
   cd evivve-backend-assignment
   ```

2. Install dependencies:

   ```bash
   npm i
   ```

3. Run the server:

   ```bash
   npm start
   ```

The server will be running on http://localhost:3000.

## Usage

- Open your browser and navigate to http://localhost:3000.
- You will see the chat application.
- Users can join different rooms and exchange messages.

## Server Configuration

The server is configured in the `server.js` file.

- `app.get("/")`: Serves the HTML file for the chat application.
- `io.on("connection")`: Handles socket connections, room joining, message sending, and disconnection events.

## Socket Events

- `join room`: Allows users to join a specific chat room.
- `chat message`: Sends and receives chat messages within a room.
- `disconnect`: Handles user disconnection events.

## Configuration

The server is set to run on port `3000` by default. You can configure the port by setting the `PORT` environment variable.
