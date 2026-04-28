<h1 align="center">
  <br>
  <img src="./public/logo.png" alt="Sync Code Logo" width="200">
  <br>
  Sync Code: Real-time Collaborative Code Editor
  <br>
</h1>

<h4 align="center">A powerful, real-time collaborative code editor built for developers and teams.</h4>

<p align="center">
  <a href="https://reactjs.org/"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"></a>
  <a href="https://expressjs.com/"><img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="Express.js"></a>
  <a href="https://socket.io/"><img src="https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101" alt="Socket.io"></a>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#installation">Installation</a> •
  <a href="#docker">Docker Setup</a> •
  <a href="#open-source-contribution">Contribute</a>
</p>

---

## 🚀 Introduction

Are you tired of sending code snippets back and forth, struggling to debug and collaborate with your team? Look no further! **Sync Code** is here to revolutionize the way you code together. 

This intuitive collaborative code editor is designed to empower developers and teams to work seamlessly in real-time, regardless of their location. Code together, debug together, and ship faster!

<br>
<p align="center">
  <img src="./public/screenshot.png" alt="Sync Code Editor Preview" width="100%">
</p>
<br>

## ✨ Features

- **👨‍💻 Real-time Collaboration:** Multiple users can join a single room and edit code simultaneously.
- **⚡ Instant Sync:** All code changes, cursor movements, and user join/leave events are reflected instantly.
- **🎨 Customization:** Multiple editor themes to suit your coding preferences.
- **🌐 Multi-Language Support:** Robust syntax highlighting for a variety of programming languages.
- **📋 Easy Sharing:** 1-click button to copy the Room ID to your clipboard.
- **💾 State Persistence:** Safely leave a room and rejoin later without losing progress.

## 🛠 Tech Stack

- **Frontend:** React.js, React-Toastify, CodeMirror
- **Backend:** Node.js, Express.js
- **Real-Time Engine:** Socket.io
- **Containerization:** Docker & Docker Compose

## 💻 Installation

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PratikshaVaya/Real-Time-Code-Collaboration-Platform.git
   cd Real-Time-Code-Collaboration-Platform
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Setup:**
   Create a `.env` file in the root folder (or use the one automatically generated) and add the following:
   ```env
   REACT_APP_BACKEND_URL=http://localhost:5000
   SERVER_PORT=5000
   ```

4. **Start the backend server:**
   ```bash
   npm run server:dev
   ```

5. **Start the React frontend (in a separate terminal):**
   ```bash
   npm start
   ```

6. Open `http://localhost:3000` in your browser. Create a new room, enter a username, and start collaborating!

---

<a name="docker"></a>
## 🐳 Running via Docker (Recommended)

Running the application using Docker ensures you have a clean, reproducible environment.

1. **Ensure Docker is installed and running** on your machine.
2. **Run Docker Compose:**
   ```bash
   docker-compose up --build
   ```
3. Once built, the frontend will be available at `http://localhost:3000` and the backend will run securely on `http://localhost:5000`.

## 🤝 Open Source Contribution

Contributions, issues, and feature requests are always welcome! 

1. Fork this repository.
2. Clone your forked repository:
   ```bash
   git clone https://github.com/your-username/Real-Time-Code-Collaboration-Platform.git
   ```
3. Navigate into the directory and create a new branch:
   ```bash
   git checkout -b feature/my-awesome-feature
   ```
4. Commit your changes and push them to your branch.
5. Open a Pull Request on this repository!

<br>

<p align="center">
  <i>Built with ❤️ by <a href="https://github.com/PratikshaVaya">Pratiksha Vaya</a></i>
</p>
