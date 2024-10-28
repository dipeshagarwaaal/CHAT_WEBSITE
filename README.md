# MERN Stack Project: Build and Deploy a Real Time Chat App | JWT, Socket.io
Some Features:

-   🌟 Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
-   🎃 Authentication && Authorization with JWT
-   👾 Real-time messaging with Socket.io
-   🚀 Online user status (Socket.io and React Context)
-   👌 Global state management with Zustand
-   🐞 Error handling both on the server and on the client

## Tech Stack

### Frontend
- **React.js**: User interface and component management.
- **TailwindCSS & DaisyUI**: Styling framework for a sleek, responsive layout.
- **Zustand**: Lightweight state management.

### Backend
- **Node.js**: JavaScript runtime environment.
- **Express.js**: Framework for handling server requests and routes.
- **MongoDB**: Database for storing user and chat data.

### Real-Time Communication
- **Socket.io**: Real-time messaging and connection management.
- **JWT (JSON Web Tokens)**: For secure user authentication and authorization.

---

## Installation

To set up the chat application locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
   ```

2. **Install Frontend Dependencies:**
   ```bash
   cd frontend
   npm install
   ```

3. **Install Backend Dependencies:**
   ```bash
   cd ../backend
   npm install
   ```

4. **Set Up Environment Variables:**
   - Create a `.env` file in the backend directory with your configurations (see [Environment Variables](#environment-variables)).

5. **Run the Application:**
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend server:
     ```bash
     cd ../frontend
     npm start
     ```

6. **Open the App:**
   - Go to `http://localhost:3000` in your browser.

---

## Environment Variables

In the backend `.env` file, include the following configurations:

```plaintext
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
SOCKET_PORT=socket_server_port
```

Optional configurations:
- `PORT`: Define server port.
- `NODE_ENV`: Set to `development` or `production`.

---

## Usage

1. **Register or Log In**: Create an account or log in if you already have one.
2. **Find Online Users**: Check the list of online users for messaging.
3. **Start Chatting**: Select an online user to start a private chat.
4. **Real-Time Updates**: Experience instant message delivery and online/offline status updates.

---
