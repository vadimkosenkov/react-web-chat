# 💬 React Web Chat

A real-time chat application built with React and Socket.IO. Pick a nickname, join the room, and chat with everyone currently online — see who's connected, exchange messages instantly, and get notified as users join or leave.

🔗 Live Demo: https://react-web-chat-8c5c51.netlify.app/

🔗 Repository: https://github.com/vadimkosenkov/react-web-chat

🔗 Backend: https://github.com/vadimkosenkov/node-web-chat-server

![WebChat Preview](https://github.com/user-attachments/assets/e062ddce-5fcb-4e4d-b1a2-2990b9b9e289)

---

## 🚀 Key Features

- Nickname-based entry with input validation (required, up to 16 characters) — no password, no signup.
- Real-time messaging over WebSockets via Socket.IO, with automatic fallback to polling.
- Live online users list, updated instantly as people connect and disconnect.
- System notifications in the chat feed when users join or leave.
- Auto-scroll to the latest message.
- Custom scrollbars for the message and user list panes.
- Client-side routing with protected access to the chat screen (redirects to the nickname screen if not authenticated).
- Fully responsive layout built with React Bootstrap and SCSS.

---

## 🛠️ Tech Stack

### Frontend
- React 18
- React Router
- React Bootstrap
- Socket.IO Client
- Sass / SCSS
- react-free-scrollbar

### Backend
- Node.js
- Socket.IO

---

## ⚙️ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/vadimkosenkov/react-web-chat.git
cd react-web-chat
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

The application will be available at:

http://localhost:3000

By default the client connects to the deployed backend.
