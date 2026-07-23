# 🚀 JobMatch - AI Powered Interview Preparation Platform

JobMatch is an AI-powered interview preparation platform that helps job seekers prepare smarter by analyzing resumes, understanding job descriptions, identifying skill gaps, and generating personalized interview strategies using Generative AI.

Built with **React**, **Node.js**, **Express**, **MongoDB**, **JWT Authentication**, **Google Gemini AI**, and **Puppeteer**, JobMatch simulates a real-world SaaS application with secure authentication and AI-driven career assistance.

---

## ✨ Features

### 🔐 Secure Authentication
- User Registration & Login
- JWT-based Authentication
- Password Hashing using bcrypt
- Token Blacklisting for Secure Logout

### 🤖 AI-Powered Interview Preparation
- Upload Resume (PDF/DOCX)
- Paste Target Job Description
- AI Resume Analysis
- Skill Gap Detection
- Personalized Interview Strategy Generation
- AI-Generated Interview Questions

### 📄 Resume Processing
- Resume Parsing
- Skill Extraction
- Experience Analysis
- ATS-Friendly Resume Suggestions

### 📑 PDF Report Generation
- Dynamic Interview Report Generation
- High-quality PDF Export using Puppeteer

### 📊 Dashboard
- View Previous Interview Reports
- Match Score Visualization
- Interview History

---

# 🛠 Tech Stack

## Frontend
- React.js
- React Router
- Axios
- SCSS

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

## Authentication
- JWT (JSON Web Token)
- bcrypt
- Token Blacklisting

## AI
- Google Gemini API

## File Processing
- Multer
- Puppeteer

---

# 📂 Project Structure

```
JobMatch
│
├── Backend
│   ├── src
│   │   ├── controllers
│   │   ├── middlewares
│   │   ├── models
│   │   ├── routes
│   │   ├── services
│   │   └── config
│   │
│   ├── package.json
│   └── server.js
│
├── Frontend
│   ├── src
│   │   ├── features
│   │   ├── pages
│   │   ├── services
│   │   ├── hooks
│   │   └── components
│   │
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/JobMatch.git

cd JobMatch
```

---

## Backend Setup

```bash
cd Backend

npm install
```

Create a `.env` file inside the Backend folder.

```env
MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

GOOGLE_GENAI_API_KEY=your_gemini_api_key
```

Start Backend

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd Frontend

npm install
```

Start Frontend

```bash
npm run dev
```

---

# 🌟 Workflow

1. Register/Login
2. Upload Resume
3. Enter Job Description
4. AI analyzes your profile
5. Detects skill gaps
6. Generates personalized interview strategy
7. Creates interview questions
8. Generates ATS-optimized report

---

# 🔒 Authentication Flow

- User Login
- JWT Token Generation
- HTTP Cookie Storage
- Protected Routes
- Token Verification Middleware
- Token Blacklisting on Logout

---

# 🤖 AI Features

- Resume Parsing
- Skill Extraction
- Job Description Analysis
- Candidate Skill Matching
- Skill Gap Detection
- Personalized Interview Questions
- Interview Strategy Generation
- ATS Resume Recommendations







