# 🚀 CodCollab - Real-Time Collaborative Editor

CodCollab is a powerful, real-time collaborative platform that combines a feature-rich code editor with an interactive drawing board. Built with React, Node.js, and WebSockets, it allows teams to code, design, and communicate seamlessly in a shared virtual workspace.

**[Live Demo](https://cod-collab-git-main-siddharth4572s-projects.vercel.app/)**

## ✨ Features

*   **Real-time Collaboration:** Multiple users can code, draw, and chat in the same room simultaneously.
*   **Integrated Code Editor:** Powered by **CodeMirror**, with syntax highlighting for numerous languages.
*   **Interactive Drawing Board:** A shared canvas for brainstorming and diagrams using **tldraw**.
*   **Virtual File System:** Create, rename, delete, and organize files and folders just like in a local IDE.
*   **Project Sync:**
    *   **Upload:** Start a session by uploading your local project folder.
    *   **Download:** Download the entire file structure as a `.zip` file at any time.
*   **User Presence:** See who's online, their cursor position, and their currently active file.
*   **Room-based Sessions:** Join unique rooms using a Room ID and a username for private collaboration.
*   **Built-in Chat:** Communicate with other users in the room without leaving the application.

## 📸 Screenshot

*(Add a screenshot of your application here)*



## 🛠️ Tech Stack

### Frontend

*   **Framework:** React
*   **Language:** TypeScript
*   **Build Tool:** Vite
*   **Styling:** Tailwind CSS
*   **Real-time Communication:** Socket.IO Client
*   **Code Editor:** CodeMirror
*   **Drawing Board:** tldraw
*   **State Management:** React Context API

### Backend

*   **Framework:** Express.js
*   **Language:** TypeScript
*   **Real-time Communication:** Socket.IO
*   **Runtime:** Node.js

### Deployment

*   **Frontend:** Vercel
*   **Backend:** Render

---

## ⚙️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Node.js (v18 or later recommended)
*   npm or yarn

### 1. Clone the Repository

```bash
git clone https://github.com/siddharth4572/CodCollab.git
cd CodCollab
```

### 2. Setup the Backend

```bash
# Navigate to the server directory
cd server

# Install dependencies
npm install

# Create a .env file and add your frontend URL
# (For local development, this will be http://localhost:5173)
echo "FRONTEND_URL=http://localhost:5173" > .env

# Start the development server
npm run dev
```

The backend server will be running on `http://localhost:3000`.

### 3. Setup the Frontend

```bash
# Navigate to the client directory from the root
cd client

# Install dependencies
npm install

# Create a .env file and add your backend URL
echo "VITE_BACKEND_URL=http://localhost:3000" > .env

# Start the development server
npm run dev
```

The frontend application will be available at `http://localhost:5173`.

## 🌐 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` files:

## 📜 License

This project is licensed under the ISC License.