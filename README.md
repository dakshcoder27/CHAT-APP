This project is a full-stack chat application built using the MERN stack (MongoDB, Express, React, Node.js). The app features a sleek, real-time chat interface with several modern functionalities like online status indicators, file uploads, auto-scrolling, and more. It provides a seamless chat experience for users, making it perfect for learning and building interactive real-time applications.

🚀 Project Overview:
This chat app allows users to:

Send/receive messages in real-time using WebSockets (Socket.IO).
View online status of other users, with indicators for active/inactive users.
Upload files like images, videos, and documents, and share them within the chat.
Auto-scroll the chat window to always display the latest messages.
User Authentication: Secure login and registration system using JWT tokens.
Chat Rooms: Users can create or join multiple chat rooms for group discussions.
📚 Technologies Used:
Frontend: React, Redux, React Router, Axios
Backend: Node.js, Express, Socket.IO, JWT Authentication
Database: MongoDB, Mongoose
File Upload: Multer (for handling file uploads)
Real-Time: WebSockets with Socket.IO
Others: bcrypt.js for password hashing, cloud storage (for file uploads)
💻 Key Features:
Real-Time Messaging: Instant message exchange between users with WebSocket-powered updates.
User Authentication: Secure login/registration with JWT token-based authentication.
Online User Indicator: Displays real-time online status of users (active/inactive).
File Uploads: Allows users to upload and share images, videos, and documents.
Chat History: Saves and displays previous messages even after a page refresh.
Auto-Scrolling: Automatically scrolls the chat window to the latest message.
Multi-User Chat Rooms: Users can join or create chat rooms for group conversations.
🛠️ Installation:
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/chat-app-mern.git
Install the backend dependencies:
bash
Copy code
cd backend
npm install
Install the frontend dependencies:
bash
Copy code
cd frontend
npm install
Set up your .env files for both frontend and backend (MongoDB URI, JWT secret, cloud storage configuration).
Start the backend server:
bash
Copy code
npm run dev
Start the frontend development server:
bash
Copy code
npm start
📄 Documentation:
This repository includes detailed documentation on project setup, features, and step-by-step instructions for building your own chat application with MERN stack.

🎯 Purpose:
This project is designed to showcase a complete full-stack application using the MERN stack. It focuses on real-time communication and modern features, providing a fun and interactive platform for learning. Perfect for developers looking to improve their skills in building real-time applications with React, Node.js, and WebSockets.

📝 License:
This project is open-source and available under the MIT License.

