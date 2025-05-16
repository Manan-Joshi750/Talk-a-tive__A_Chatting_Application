# 💬 Talk-A-Tive

**Talk-A-Tive** is a real-time full-stack chat application designed for seamless communication between users. It features secure user authentication, one-to-one and group chats, instant messaging with typing indicators, user search, and advanced group management—all built with the MERN stack and powered by Socket.io for live communication.  

With a responsive frontend and a robust backend, Talk-A-Tive offers an intuitive and fast messaging experience backed by MongoDB for data persistence.

![image](https://github.com/user-attachments/assets/0bd6d9b0-c4c9-4002-a32c-72101834e20f)

---

## 🚀 Features

- 🔐 **User Authentication**
  - Secure login and signup
  ![image](https://github.com/user-attachments/assets/c9820c7c-749a-4419-85b8-05bab7fa26a7)
  ![image](https://github.com/user-attachments/assets/11be02b2-960a-4f2c-bf40-a5a7128768fa)

  - Encrypted password storage
  ![image](https://github.com/user-attachments/assets/7b9451ec-e80a-47ca-937b-2a39c06f101b)

- 💬 **Real-Time Messaging**
  - Instant chat updates using Socket.io
  - Typing indicators
  ![image](https://github.com/user-attachments/assets/dc105b82-0a18-4fba-9c71-7fa06631f6af)

- 👤 **One-to-One Chat**
  - Personal messaging between users
  

- 👥 **Group Chats**
  - Create, rename, and manage group conversations
  ![image](https://github.com/user-attachments/assets/6960eb41-3759-4802-afa1-aa4da690cb39)

- 🔎 **User Search**
  - Search for users to start chatting instantly
  ![image](https://github.com/user-attachments/assets/652755a0-8cc3-45ca-9344-85d91e529ff2)

- 🛎️ **Notifications**
  - Real-time message alerts and unread indicators
  ![image](https://github.com/user-attachments/assets/63b684cb-fe40-4c35-a11c-3e56f5b8462c)

- ➕➖ **Group User Management**
  - Add or remove members in real-time
  ![image](https://github.com/user-attachments/assets/d253b2bb-b619-4748-a711-5d3a59f231c4)

- 👁️ **View Profiles**
  - View detailed profiles of other users
  

---

## 🧪 Tech Stack

| 🌐 Technology     | 📖 Documentation                                   |
|-------------------|----------------------------------------------------|
| **React**         | [React Docs](https://react.dev/)                   |
| **Node.js**       | [Node.js Docs](https://nodejs.org/)                |
| **Express.js**    | [Express Docs](https://expressjs.com/)             |
| **MongoDB**       | [MongoDB Docs](https://www.mongodb.com/docs/)      |
| **Socket.io**     | [Socket.io Docs](https://socket.io/docs/)          |

---

## 💻 Run Locally

Clone the project

```bash
git clone https://github.com/piyush-eon/mern-chat-app
```

Go to the project directory

```bash
cd mern-chat-app
```

Install server dependencies

```bash
npm install
```

Navigate to the frontend directory and install dependencies

```bash
cd frontend/
npm install
```

---

### 📄 Setup Environment Variables

Before starting the application, create a `.env` file in the root directory of the project (`mern-chat-app/`) with the following structure:

```env
PORT=your_port_number
MONGO_URI=your_mongodb_url
JWT_SECRET=your_jwt_secret
```

---

### ▶️ Start the Server

```bash
npm run start
```

### ▶️ Start the Client

```bash
cd frontend
npm start
```

---
