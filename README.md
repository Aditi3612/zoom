# 🔗 Zoom Clone – Full Stack Video Conferencing App

A **full-stack video conferencing web application** built with React, WebRTC, and Node.js. This project replicates the core features of Zoom — real-time video and audio communication, dynamic room creation, and interactive peer-to-peer communication — using modern web technologies.

---

## 🚀 Features

- 🎥 Real-time video & audio using WebRTC
- 🔗 Unique room generation and joining system
- 🧑‍🤝‍🧑 Peer-to-peer media connection
- ⚡ Socket.IO for signaling between clients
- 💻 React + Node.js full-stack architecture

---

## 📸 Application Flowchart



![Zoom Clone Architecture](assets/zoom-flowchart.png)

> This diagram shows the end-to-end flow: from joining a room to peer-to-peer video communication setup using WebRTC and Socket.IO.

---

## 🛠️ Tech Stack

| Frontend | Backend     | Communication |
|----------|-------------|----------------|
| React    | Node.js     | WebRTC         |
| Webpack  | Express.js  | Socket.IO      |
| CSS      |             |                |

---

## 📂 Project Structure

```
zoom/
├── client/        # React frontend
│   ├── public/
│   └── src/
├── server/        # Node.js/Express backend
├── assets/        # Flowchart or other images
└── README.md
```

---

## 🧑‍💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Aditi3612/zoom.git
cd zoom
```

### 2. Install Dependencies

Frontend:

```bash
cd client
npm install
```

Backend:

```bash
cd ../server
npm install
```

### 3. Run the App Locally

Start the backend server:

```bash
cd server
npm start
```

Start the frontend React app:

```bash
cd ../client
npm start
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📦 Available Scripts (Frontend)

Inside the `client/` directory:

- `npm start` – Start the React app in development mode.
- `npm test` – Run test watcher.
- `npm run build` – Create production build.
- `npm run eject` – Eject CRA config (irreversible).

---

## 🌐 Deployment

You can deploy:

- **Frontend** → Vercel, Netlify, GitHub Pages
- **Backend** → Render, Railway, Heroku

To prepare the frontend for deployment:

```bash
npm run build
```

Then deploy the `build/` folder.

---

## 📘 Learn More

- [React Docs](https://reactjs.org/)
- [Create React App Docs](https://create-react-app.dev/)
- [WebRTC API Guide](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)
- [Socket.IO Docs](https://socket.io/docs/)

---

## 🙌 Acknowledgements

- Inspired by Zoom UI/UX
- Powered by WebRTC and Socket.IO
- Bootstrapped with Create React App

---


