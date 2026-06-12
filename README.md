# 🔥 Hotspot - Real-Time Chat Application

A modern, real-time chat application built with React and Node.js, featuring Google OAuth authentication, real-time messaging, and a beautiful glassmorphism UI design.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-ISC-green.svg)
![Node](https://img.shields.io/badge/node.js-v18+-brightgreen.svg)
![React](https://img.shields.io/badge/react-v19.0.0-blue.svg)

## ✨ Features

- 🔐 **Google OAuth Authentication** - Secure login with Google accounts
- 💬 **Real-Time Messaging** - Instant message delivery using Socket.io
- 🏠 **Room-Based Chat** - Join different chat rooms for organized conversations
- 🎨 **Modern UI/UX** - Beautiful glassmorphism design with smooth animations
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices
- ⚡ **Fast Performance** - Optimized with Vite for lightning-fast development and builds
- 🔄 **Real-Time Notifications** - Toast notifications for user actions and events

## 🛠️ Tech Stack

### Frontend
- **React 19** - Modern React with latest features
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Production-ready motion library for React
- **React Router DOM** - Client-side routing
- **Socket.io Client** - Real-time bidirectional event-based communication

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Fast, unopinionated web framework
- **Socket.io** - Real-time communication library
- **CORS** - Cross-Origin Resource Sharing middleware
- **Nodemon** - Development utility for auto-restarting server

## 📋 Prerequisites

Before running this application, make sure you have the following installed:

- **Node.js** (v18 or higher) 
- **npm** or **yarn** - Package manager
- **Git** - Version control system

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/Laxmi1214/hotspot.git
cd Hotspot
```

### 2. Backend Setup

```bash
# Navigate to backend directory
cd Backend

# Install dependencies
npm install

# Start the development server
npm run dev
# or for production
npm start
```

The backend server will start on `http://localhost:199`

### 3. Frontend Setup

```bash
# Navigate to frontend directory (in a new terminal)
cd Frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

The frontend application will start on `http://localhost:5173` (or the next available port)

### 4. Google OAuth Setup

1. Go to the [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select an existing one
3. Enable the Google+ API
4. Create OAuth 2.0 credentials
5. Add your domain to authorized origins
6. Configure your OAuth client ID in the frontend application

## 📁 Project Structure

```
Hotspot/
├── README.md
├── Backend/
│   ├── entity.js          # User management utilities
│   ├── package.json       # Backend dependencies and scripts
│   └── server.js          # Express server with Socket.io
└── Frontend/
    ├── eslint.config.js   # ESLint configuration
    ├── index.html         # HTML template
    ├── package.json       # Frontend dependencies and scripts
    ├── vite.config.js     # Vite configuration
    ├── vercel.json        # Vercel deployment config
    ├── public/            # Static assets
    └── src/
        ├── App.jsx        # Main application component
        ├── Login.jsx      # Authentication page
        ├── main.jsx       # Application entry point
        ├── index.css      # Global styles
        ├── assets/        # Images and icons
        ├── components/    # Reusable React components
        │   ├── AnimatedBackground.jsx
        │   ├── Chat.jsx
        │   ├── ChatHeader.jsx
        │   ├── ChatMessages.jsx
        │   ├── Herchat.jsx
        │   ├── Input.jsx
        │   ├── MessageInput.jsx
        │   ├── Navbar.jsx
        │   └── NicknameSetup.jsx
        └── pages/         # Page components
            ├── Aboutus.jsx
            └── Home.jsx
```

## 🎮 How to Use

1. **Access the Application**: Open your browser and navigate to `http://localhost:5173`

2. **Authentication**: 
   - Click on "Sign in with Google" to authenticate
   - Accept the terms and conditions

3. **Join a Chat Room**:
   - you will be added to a room based on your Location
   - Set your display name/nickname

4. **Start Chatting**:
   - Send messages in real-time
   - See when other users join or leave
   - Enjoy the smooth animations and responsive design

## 🔧 Configuration

### Backend Configuration

The backend server runs on port `199` by default. You can modify this in `Backend/server.js`:

```javascript
server.listen(199, () => {
    console.log("🚀 Server running at http://localhost:199");
});
```

### Frontend Configuration

Vite configuration can be found in `Frontend/vite.config.js`. The default development server runs on port `5173`.

## 📱 Responsive Design

Hotspot is designed to work seamlessly across all device sizes:

- **Desktop**: Full-featured experience with optimal layout
- **Tablet**: Adapted UI for medium screens
- **Mobile**: Touch-optimized interface for small screens

---

**Happy Chatting! 🎉**

