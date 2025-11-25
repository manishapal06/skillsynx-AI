SkillSynx-AI (Next.js + Tailwind + Google Gemini API + Socket Backend)

🚀 Live App: https://skillsynx.vercel.app

📦 Frontend Repo: https://github.com/manishapal06/skillsynx-AI

📦 Backend Repo: https://github.com/manishapal06/skillsynx-AI-Socket

SkillSync-AI is an AI-powered Job Role Recommendation and Skill Analysis platform.
It analyzes a user's skillset using Google Gemini API, provides personalized insights, and shows real-time processing using Socket.IO.
The UI is built with Next.js + Tailwind CSS for a clean and responsive experience.

🧠 Core Features
🔹 AI Skill Analysis

Uses Google Gemini API

Generates:

Personalized job role suggestions

Skill strengths

Skill gaps

Improvement roadmap

Learning path

🔹 Real-Time Processing (Socket.IO)

Live AI response streaming

Progress updates in real-time

Faster user experience

Event-based communication

🔹 Modern UI (Next.js + Tailwind)

Clean and responsive design

Smooth animations

Simple user flow

Fast rendering (App Router)

🔹 Backend Services

Handles AI request pipeline

Manages user skill data

Formats AI output

Manages real-time socket events

🔧 Tech Stack
Frontend

Next.js

Tailwind CSS

Axios

Socket.io Client

React Hooks / Context

Backend

Node.js

Express

MongoDB (Mongoose)

Socket.IO

Google Gemini API

CORS

📂 Project Structure
Frontend (Next.js Repo) — skillsynx-AI
skillsynx-AI/
│
├── app/
│   ├── page.js
│   ├── components/
│   ├── styles/
│   ├── api/
│   └── utils/
├── public/
├── package.json
└── tailwind.config.js

Backend (Socket Server Repo) — skillsynx-AI-Socket
skillsynx-AI-Socket/
│
├── data/
├── helper/
├── models/
├── db.js
├── index.js
├── project.txt
├── package.json
└── .gitignore

⚙️ Frontend Setup
git clone https://github.com/manishapal06/skillsynx-AI
cd skillsynx-AI
npm install
npm run dev


Create .env.local:

NEXT_PUBLIC_SOCKET_URL=http://localhost:5000
NEXT_PUBLIC_GEMINI_KEY=your_api_key

⚙️ Backend Setup
git clone https://github.com/manishapal06/skillsynx-AI-Socket
cd skillsynx-AI-Socket
npm install
npm start


Create .env:

PORT=5000
MONGO_URL=your_mongo_url
GEMINI_API_KEY=your_api_key

🔌 Socket Events Used
Event	Purpose
connection	User connected
skill-analysis	User sends skill input
progress-update	Live updates
ai-response	Final Gemini output
disconnect	User left
🤖 AI Processing Flow

User enters skillset

Data sent to backend through Socket

Backend sends prompt → Gemini API

AI generates structured response

Live streaming updates shown in UI

Final job role + improvement plan displayed

📈 Future Enhancements

User login & saved reports

Downloadable PDF career report

More job role categories

Role-based dashboards

Admin analytics

Roadmap generator

👩‍💻 Developer

Manisha Pal , Akhil, Sagar, Manoj
Full Stack Developer
Creator of SkillSynx-AI
