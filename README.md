# Chat Application

A real-time chat application built with React, Axios, and Socket.io.
Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.

## Tech Stack

**Frontend**:
- React
- Axios 
- Socket.io-client
- Chakra UI
  
**Backend**:
- Node.js
- Express
- Socket.io
- MongoDB
- Mongoose
- JWT (JSON Web Token) for authentication
- bcryptjs (for password hashing)

## Installation

To get a local copy up and running, follow these steps:

```bash
git clone https://github.com/1ochaku/Another-Messenger/
cd Another-Messenger
npm install
```


Frontend Setup
- Navigate to the frontend directory.
```bash
cd frontend/
npm install
```

- Create a .env file and add the following environment variables:
```js
PORT=...
MONGO_DB_URI=...
JWT_SECRET=...
NODE_ENV=...
```

- Start the backend server.
```bash
npm run start
```

- Start the frontend server.
```bash
cd frontend/
npm start
```

