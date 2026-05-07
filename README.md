# 🌌 DeltaAI - Into the Unknown

DeltaAI is a modern conversational AI platform built for fast, smooth, and intelligent interactions. Developed using the MERN stack and integrated with Google Gemini AI, the platform delivers real-time AI conversations with a clean dark-themed interface, secure authentication, and smart code-rendering capabilities.

---

# ✨ Features

- **AI-Powered Conversations**  
  Integrated with the Gemini AI model to generate fast, contextual, and accurate responses.

- **Modern Dark UI**  
  Minimal and premium dark-mode interface designed for a smooth user experience.

- **Smart Code Blocks**  
  Supports Markdown rendering, syntax highlighting, and one-click code copy functionality.

- **Chat History Storage**  
  Conversations are securely stored in MongoDB and synced automatically after login.

- **Secure Authentication**  
  User authentication and session management handled using Clerk.

- **Responsive Design**  
  Optimized for desktop, tablet, and mobile devices.

---

# 🛠️ Tech Stack

## Frontend
- React.js (Vite)
- TypeScript
- Material UI (MUI)
- Clerk Authentication
- React Markdown
- React Syntax Highlighter

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Google Generative AI SDK
- TypeScript

---

# 🚀 Getting Started

Follow these steps to run DeltaAI locally.

## Prerequisites
- Node.js installed
- MongoDB database setup
- Clerk account
- Google AI Studio API Key

---

# 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/DeltaAI.git

cd DeltaAI
2️⃣ Backend Setup
cd backend
npm install

Create a .env file inside the backend folder:

PORT=5000
MONGODB_URL=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
CLERK_SECRET_KEY=your_clerk_secret_key

Start backend server:

npm run dev
3️⃣ Frontend Setup
cd frontend
npm install

Create a .env file inside the frontend folder:

VITE_API_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

Run frontend:

npm run dev
🧠 Usage
Open http://localhost:5173
Create an account or login
Start chatting with DeltaAI
Generate code snippets, explanations, and AI responses instantly
👨‍💻 Developer

Sumit Bera
Full Stack & MERN Developer

GitHub: @sumit-bera-0805
