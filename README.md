# Socket-Talk - Real-Time Chat Application

A full-stack real-time chat application built with React, Node.js, Socket.IO, and MongoDB.

## Features

- 🔐 User authentication (signup/login)
- 👤 User profiles with customizable avatars and bio
- 💬 Real-time messaging
- 🖼️ Image sharing support
- 🔵 Online/offline user status
- 👀 Message read status
- 🔍 User search functionality
- 📱 Responsive design

## Tech Stack

### Frontend
- React
- TailwindCSS
- Socket.IO Client
- React Router DOM
- React Hot Toast
- Axios
- Vite

### Backend
- Node.js
- Express
- Socket.IO
- MongoDB & Mongoose
- JWT Authentication
- Cloudinary (image storage)
- bcryptjs (password hashing)

## Project Structure

```
chat-app/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── assets/        # Images and static assets
│   │   ├── components/    # React components
│   │   ├── pages/        # Page components
│   │   ├── lib/          # Utility functions
│   │   └── context/      # React context providers
│   └── ...
└── server/                # Backend Node.js application
    ├── controllers/       # Route controllers
    ├── models/           # MongoDB models
    ├── routes/           # API routes
    ├── middleware/       # Express middleware
    ├── lib/             # Utility functions
    └── server.js        # Main server file
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- MongoDB database
- Cloudinary account

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd chat-app
```

2. Install backend dependencies
```bash
cd server
npm install
```

3. Install frontend dependencies
```bash
cd ../client
npm install
```

### Running the Application

1. Start the backend server
```bash
cd server
npm run server
```

2. Start the frontend development server
```bash
cd client
npm run dev
```

## Features in Detail

### Authentication
- Secure signup and login with JWT
- Protected routes
- Persistent sessions

### Messaging
- Real-time message delivery
- Image sharing support
- Message read status
- Unread message counter
- Chat history persistence

### User Features
- Profile customization
- Online/offline status
- User search
- User bio

### UI/UX
- Responsive design for mobile and desktop
- Clean and modern interface
- Real-time status updates
- Loading states and error handling
- Toast notifications

## Deployment

The application is configured for deployment on Vercel:
- Frontend: Static site hosting
- Backend: Serverless functions

# Socket-Talk - Real-Time Chat Application

A full-stack real-time chat application built with React, Node.js, Socket.IO, and MongoDB.

## Live Demo
🔗 [Try the live demo](https://chat-app-eight-coral-70.vercel.app/login)

> **Note:** Since the application is deployed on Vercel it may not work exactly in Real Time

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
