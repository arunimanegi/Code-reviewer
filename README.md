# Code Review Assistant

A modern web application that helps developers get AI-powered code reviews for their code snippets. The application uses Google's Generative AI to provide intelligent code reviews and suggestions.

## Features

- Real-time code editing with syntax highlighting
- AI-powered code review generation
- Markdown rendering of code reviews
- Modern and responsive UI
- Support for JavaScript code review

## Tech Stack

### Frontend
- React 19
- Vite
- React Simple Code Editor
- Prism.js for syntax highlighting
- React Markdown for rendering reviews
- Axios for API calls

### Backend
- Node.js
- Express.js
- Google Generative AI
- CORS support
- Environment variable configuration

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Google AI API key

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd code-review-main
```

2. Install dependencies for both frontend and backend:
```bash
# Install root dependencies
npm install

# Install frontend dependencies
cd Frontend
npm install

# Install backend dependencies
cd ../BackEnd
npm install
```

3. Create a `.env` file in the BackEnd directory with your Google AI API key:
```
GOOGLE_AI_API_KEY=your_api_key_here
```

## Running the Application

1. Start the backend server:
```bash
cd BackEnd
npm start
```

2. In a new terminal, start the frontend development server:
```bash
cd Frontend
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

## Usage

1. Write or paste your code in the editor on the left side
2. Click the "Review" button
3. View the AI-generated code review on the right side

## Development

- Frontend runs on port 5173 (Vite default)
- Backend runs on port 3000
- The application uses environment variables for configuration
- Code reviews are generated using Google's Generative AI

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Acknowledgments

- Google Generative AI for providing the AI capabilities
- React community for the amazing tools and libraries
- All contributors who have helped shape this project 