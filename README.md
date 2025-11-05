
🧠 CodeReviewer.AI

> "AI-Powered Code Review Assistant for Developers"






---

⚙️ Tech Stack

Frontend: React.js, Prism.js, react-markdown, Axios
Backend: Node.js, Express.js, dotenv, CORS
AI Service: Google Gemini / Jamna 2.0 Flash API
Tools: Postman, VS Code, Git, npm


---

🌟 About the Project

CodeReviewer.AI is an open-source full-stack application that uses Google’s AI models to analyze and review code snippets in real time.
It’s built for developers, students, and teams who want instant, intelligent feedback on their code.
This project demonstrates how to integrate AI APIs with a modular Node.js + React.js architecture, while keeping performance, security, and usability in mind.


---

✨ Key Features

🤖 AI-Powered Code Reviews: Get instant feedback on syntax errors, optimizations, and best practices.

💬 Smart Suggestions: AI provides clean, structured responses with explanations and improvement ideas.

💻 Interactive Frontend: React-based editor with syntax highlighting (Prism.js) and markdown-rendered AI responses.

🔄 Real-Time API Integration: Backend connects directly with Google’s AI for processing user code.

🧩 Clean Modular Design: Routes, controllers, and services neatly separated for scalability.



---

🧠 System Architecture / Project Overview

Frontend (React) <--> Backend (Express API) <--> Google AI (Gemini Model)
        ↑                                                   ↓
    Code Input                                    AI-generated Review

Flow:

1. User enters code in React editor.


2. Axios sends the code to Express backend.


3. Backend calls Google’s AI model using API key.


4. AI analyzes and sends review → frontend displays it beautifully.




---

📂 Folder Structure

CodeReviewer.AI/
├── backend/
│   ├── server.js
│   ├── .env
│   └── src/
│       ├── app.js
│       ├── routes/
│       ├── controllers/
│       └── services/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│   ├── package.json
│
└── README.md


---

⚡ Installation / Setup Instructions

Setup Backend

cd backend
npm install
npm start

Create a .env file:

G_API_KEY=your_google_ai_key_here
PORT=3000

Setup Frontend

cd frontend
npm install
npm run dev


---

🔑 Environment Variables

Variable	Description

G_API_KEY	Google AI API key
PORT	Port for backend server (default: 3000)



---

💡 What I Learned / Challenges Faced

How to design a modular Express.js architecture with controllers and services.

Managing CORS and asynchronous API calls between frontend and backend.

Structuring AI prompts and system instructions for better review accuracy.

Handling real-world issues like error boundaries, rate limiting, and environment security.



---

🧩 Future Enhancements

🧠 Multi-language support (Python, Java, C++).

🔐 User authentication (JWT + Role-based access).

📊 Code quality scoring metrics.

☁️ Cloud deployment (Render / Vercel + MongoDB Atlas).

💬 AI chat interface for interactive code mentoring.



