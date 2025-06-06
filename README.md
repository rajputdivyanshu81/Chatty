💬 Chat-App

A real-time chat application built with Socket.IO, React, Express, and Node.js featuring JWT-based authentication, 10+ beautiful themes, and a modern user interface. Includes demo images and a video walkthrough for easy understanding and onboarding.

🚀 Features

🔐 JWT Authentication – Secure login & registration

🧠 Socket.IO – Real-time messaging powered by websockets

🎨 10+ Customizable Themes – Choose your favorite look

👥 Private & Group Chats

🖼️ Image Sharing Support

🔔 Real-Time Notifications

📱 Responsive Design – Works great on all devices

🔒 Secure Backend – Token validation & user session management

🖼️ Preview
Light Theme:

![image](https://github.com/user-attachments/assets/67858db0-8fce-4ac3-aaba-c92e700aa91b)

Dark Theme:

![image](https://github.com/user-attachments/assets/c7383f71-f0b0-4066-a3ad-59bec2050b4f)


Chat Window:

🎥 Video Walkthrough
📺 Watch this video for a full explanation of the app’s functionality and how to get started:

https://drive.google.com/file/d/185d9dGOogOhS61nqRO627Pz6akyeYz_z/view?usp=sharing



🛠️ Tech Stack
Frontend	Backend	Realtime	Auth
React	Node.js	Socket.IO	JWT
Tailwind / CSS Modules	Express.js	WebSockets	bcrypt

📦 Installation
Clone the repo

bash
Copy
Edit
git clone https://github.com/yourusername/chat-app.git
cd chat-app
Install dependencies for backend and frontend

bash
Copy
Edit
cd server
npm install
cd ../client
npm install
Set up environment variables

Create a .env file in the /server directory with:

env
Copy
Edit
PORT=5000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongodb_connection_string
Start the app

Start the backend:

bash

Copy

Edit

cd backend

npm run dev

Start the frontend:

bash

Copy

Edit

cd ../frontend

npm run dev

⚙️ Project Structure

bash

Copy

Edit

chat-app/
├── frontend/           # React frontend
├── backend/           # Node.js + Express backend
├── README.md

🙌 Contributing
Contributions are welcome! Please open issues or submit pull requests for suggestions, improvements, or bug fixes.
