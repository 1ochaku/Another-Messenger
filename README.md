# A Chat Application

A real-time chat application built with React, Axios. Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.

## Tech Stack

**Frontend**:
- React
- Chakra UI
  
**Backend**:
- Node.js
- Express

**Database**
- MongoDB

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
## Features
### Authentication

![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/Login.png)
![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/SignUp.png)

### Chat Box Window && User Profile plus LogOut Window

![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/UserProfile%26Logout.png)

### Live Chatting and Notifications

![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/Live%20Chat%20and%20Typing%20Indicator.png)
![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/Notifications.png)

### Search Users

![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/Search%20Tab.png)

### View User Profile

![](https://github.com/1ochaku/Another-Messenger/blob/main/ScreenShots/Profile.png)


