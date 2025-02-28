# MERN Chat Application

This is a real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.io for real-time communication.

## Features

- Real-time messaging
- User authentication
- File and image uploads
- Responsive UI

## Prerequisites

- Node.js
- MongoDB

## Installation

1. Clone the repository:
    ```bash
    git clone 
    cd mern-chat-app
    ```

2. Install server dependencies:
    ```bash
    cd server
    npm install
    ```

3. Install client dependencies:
    ```bash
    cd ../client
    npm install
    ```

4. Create a `.env` file in the `server` directory and add your MongoDB connection string:
    ```ini
    MONGO_URI=mongodb://localhost:27017/databasename
    ```

## Running the Application

1. Start the server:
    ```bash
    cd server
    npm run dev
    ```

2. Start the client:
    ```bash
    cd ../client
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Enter your username when prompted.
- Type a message and press Enter or click the Send button to send a message.
- Click the paperclip icon to upload and send files or images.

## License

This project is licensed under the MIT License.
