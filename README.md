# Collaborative AI-Powered Coding Platform

A real-time collaborative coding platform with AI assistance, built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Real-time collaborative coding
- AI-powered code assistance using Google's Gemini AI
- User authentication and authorization
- Project management
- Real-time chat with AI integration
- File tree management
- Code editor with syntax highlighting

## Tech Stack

### Frontend
- React.js
- Vite
- Socket.IO Client
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Socket.IO
- JWT Authentication
- Redis
- Google Generative AI (Gemini)

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- Redis
- Google AI API Key

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd collaborative-ai-powered-coding-platform
```

2. Install dependencies:

For Backend:
```bash
cd backend
npm install
```

For Frontend:
```bash
cd frontend
npm install
```

3. Environment Setup:

Create a `.env` file in the backend directory with the following variables:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/collaborative-coding
JWT_SECRET=your-secret-key-here
GOOGLE_AI_KEY=your-google-ai-api-key-here
```

4. Start the servers:

For Backend:
```bash
cd backend
npm run dev
```

For Frontend:
```bash
cd frontend
npm run dev
```

## Getting Started

1. Register a new account or login with existing credentials
2. Create a new project
3. Invite team members to collaborate
4. Start coding with real-time collaboration
5. Use @ai in the chat to get AI assistance

## API Endpoints

### Authentication
- POST /users/register - Register a new user
- POST /users/login - Login user
- GET /users/logout - Logout user

### Projects
- POST /projects/create - Create a new project
- GET /projects/all - Get all projects
- GET /projects/get-project/:id - Get project by ID
- PUT /projects/update-file-tree - Update project file tree

### AI Integration
- WebSocket event: 'project-message' - Send message to AI
- WebSocket event: 'ai-response' - Receive AI response

## Environment Variables

### Backend (.env)
- PORT: Server port (default: 3000)
- MONGODB_URI: MongoDB connection string
- JWT_SECRET: Secret key for JWT token generation
- GOOGLE_AI_KEY: Google AI API key

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License.

## Support

For support, please open an issue in the GitHub repository. 