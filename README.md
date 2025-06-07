<div align="center">
  <br />
    <a href="https://drive.google.com/file/d/185d9dGOogOhS61nqRO627Pz6akyeYz_z/view?usp=sharing" target="_blank">
      
![screenshot-for-readme (1)](https://github.com/user-attachments/assets/76e6758c-12af-42bc-a2e0-9bb4793019ce)
 </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
    <img src="https://img.shields.io/badge/-Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.IO" />
    <img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/-Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  </div>

  <h3 align="center">Chat-App - Real-Time Messaging with React & Socket.IO</h3>

  <div align="center">
    Build this project step by step with our detailed video walkthrough on <a href="https://drive.google.com/file/d/185d9dGOogOhS61nqRO627Pz6akyeYz_z/view?usp=sharing" target="_blank"><b>Google Drive</b></a>. Join the conversation!
  </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🖼️ [Assets](#assets)
6. 🚀 [Contributing](#contributing)

## 🚨 Video Walkthrough

This repository contains the code for a real-time chat application, demonstrated in a comprehensive video tutorial. Watch the walkthrough to learn how to build this app from scratch in a beginner-friendly way!

<a href="https://drive.google.com/file/d/185d9dGOogOhS61nqRO627Pz6akyeYz_z/view?usp=sharing" target="_blank">
  Video
</a>

![image](https://github.com/user-attachments/assets/2defcbb6-3072-49ee-be56-04530baafa34)

## <a name="introduction">🤖 Introduction</a>

Chat-App is a modern, real-time messaging platform built with React, Socket.IO, Node.js, and Express. Featuring JWT-based authentication, 10+ customizable themes, and a sleek, responsive UI, it supports private and group chats, image sharing, and real-time notifications. Whether you're connecting with friends or collaborating with teams, Chat-App delivers a seamless and secure communication experience.



## <a name="tech-stack">⚙️ Tech Stack</a>

- **[React](https://react.dev/)**: A JavaScript library for building fast, interactive user interfaces with reusable components.
- **[Socket.IO](https://socket.io/)**: Enables real-time, bidirectional communication between clients and servers using WebSockets.
- **[Node.js](https://nodejs.org/)**: A runtime environment for executing JavaScript on the server, powering the backend.
- **[Express](https://expressjs.com/)**: A minimalist web framework for Node.js, used to build robust APIs for the chat app.
- **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework for designing custom, responsive interfaces efficiently.
- **[JWT](https://jwt.io/)**: JSON Web Tokens for secure user authentication and session management.
- **[bcrypt](https://www.npmjs.com/package/bcrypt)**: A library for hashing passwords to ensure secure storage.
- **[MongoDB](https://www.mongodb.com/)**: A NoSQL database for storing user data, chat history, and messages.

## <a name="features">🔋 Features</a>

👉 **Real-Time Messaging**: Instant chat with Socket.IO-powered WebSockets for seamless communication.  
👉 **JWT Authentication**: Secure user sign-up and login with token-based validation.  
👉 **Customizable Themes**: Choose from 10+ beautiful themes, including light and dark modes.  
👉 **Private & Group Chats**: Engage in one-on-one or group conversations with ease.  
👉 **Image Sharing**: Share images directly in chats for richer interactions.  
👉 **Real-Time Notifications**: Get instant alerts for new messages and updates.  
👉 **Responsive Design**: Enjoy a consistent experience across desktops, tablets, and mobiles.  
👉 **Secure Backend**: Robust token validation and user session management.  
👉 **Modern UI/UX**: Clean, intuitive interface built with Tailwind CSS and CSS Modules.  
👉 **Scalable Architecture**: Modular codebase for easy maintenance and scalability.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the Chat-App locally on your machine.

**Prerequisites**

Ensure you have the following installed:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Cloning the Repository**

```bash
git clone https://github.com/yourusername/chat-app.git
cd chat-app
```

**Installation**

Install dependencies for both backend and frontend:

```bash
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
```

**Set Up Environment Variables**

Create a `.env` file in the `/server` directory with the following:

```env
PORT=5000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongodb_connection_string
```

Replace `your_jwt_secret` with a secure key and `your_mongodb_connection_string` with your MongoDB connection string from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

**Running the Project**

Start the backend and frontend servers:

```bash
# Backend
cd server
npm run dev

# Frontend (in a new terminal)
cd client
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## <a name="assets">🖼️ Assets</a>

Explore the Chat-App's design with these demo images:

**Light Theme**  
<img src="https://github.com/user-attachments/assets/67858db0-8fce-4ac3-aaba-c92e700aa91b" alt="Light Theme Preview">

**Dark Theme**  
<img src="https://github.com/user-attachments/assets/c7383f71-f0b0-4066-a3ad-59bec2050b4f" alt="Dark Theme Preview">

Additional assets and snippets are available in the [video walkthrough](https://drive.google.com/file/d/185d9dGOogOhS61nqRO627Pz6akyeYz_z/view?usp=sharing).

## <a name="contributing">🚀 Contributing</a>

We welcome contributions! To get started:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

Please report bugs or suggest improvements via [GitHub Issues](https://github.com/yourusername/chat-app/issues).
