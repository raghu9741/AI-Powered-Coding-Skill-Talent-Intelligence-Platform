# 🧬 CodeMind DNA

### AI-Powered Coding Skill & Talent Intelligence Platform

CodeMind DNA is an intelligent coding assessment and career-readiness platform designed to understand **how a developer thinks, solves problems, learns, and improves** — not just whether their code produces the correct output.

The platform combines real-time coding evaluation, behavioral analysis, AI-powered code feedback, skill intelligence, career recommendations, mentor analytics, and recruiter insights into one unified ecosystem.

---

## 🌐 Live Application

### Frontend

https://codemind-dna-frontend.onrender.com

### Backend API

https://codemind-dna-backend.onrender.com

### API Health Check

https://codemind-dna-backend.onrender.com/api/health/live

---

# 🎯 What is CodeMind DNA?

Traditional coding platforms mainly measure:

> "Did the candidate solve the problem?"

CodeMind DNA goes further.

It attempts to understand:

- How the candidate approaches a problem
- How long they take to solve it
- Which concepts they struggle with
- How often they make mistakes
- How their solutions improve
- Which skills are becoming stronger
- Where their skill gaps exist
- Which career paths match their abilities
- How prepared they are for industry roles

The result is a continuously evolving **SkillDNA profile**.

---

# ✨ Core Features

## 👨‍🎓 Student Platform

### 🧑‍💻 Live Coding Environment

CodeMind DNA provides an interactive coding environment powered by **Monaco Editor**.

Students can:

- Write code
- Solve programming problems
- Execute solutions
- Submit solutions
- Track execution results
- Review previous attempts
- Monitor coding progress

---

## 🧬 SkillDNA Profile

The platform builds a skill profile based on coding activity and performance.

The profile can represent areas such as:

```text
Problem Solving
Data Structures
Algorithms
Programming
Debugging
Consistency
Learning Progress
Coding Efficiency
```

The objective is to move beyond simple marks and create a more meaningful representation of coding ability.

---

# 🤖 AI Coding Intelligence

CodeMind DNA includes AI-powered capabilities for analyzing programming performance.

Potential AI capabilities include:

- AI code review
- Error explanation
- Skill-gap analysis
- Learning recommendations
- Career recommendations
- Personalized roadmaps
- Coding improvement suggestions

Supported AI providers include:

- Google Gemini
- OpenAI
- Groq

AI functionality can be controlled through environment configuration.

---

# 📊 Analytics

CodeMind DNA tracks coding and learning activity to provide meaningful analytics.

Examples include:

- Coding attempts
- Accepted solutions
- Failed attempts
- Problem progression
- Topic performance
- Learning progress
- Skill development
- Assessment performance

---

# 🎯 Career Intelligence

The platform connects coding performance with career development.

Students can receive guidance related to:

- Software Engineering
- Full Stack Development
- Backend Development
- Frontend Development
- Data Engineering
- AI / ML
- Cybersecurity
- Cloud Engineering
- Other technology careers

The long-term goal is to identify:

```text
Current Skills
      ↓
Skill Gaps
      ↓
Recommended Learning
      ↓
Career Readiness
      ↓
Target Career
```

---

# 👨‍🏫 Mentor Platform

Mentors can use CodeMind DNA to understand student progress.

Mentor capabilities include:

- Student monitoring
- Student assignments
- Coding analytics
- Career reviews
- Mentor sessions
- Risk alerts
- Student recommendations
- Reports
- Learning resources
- Messages

This enables mentors to focus on students who need additional support.

---

# 🧑‍💼 Recruiter Platform

CodeMind DNA is designed to provide recruiters with deeper candidate intelligence.

Recruiter capabilities include:

- Candidate matching
- Candidate analytics
- Shortlisting
- Applications
- Interview management
- Company management
- Recruiter messaging
- Candidate reports

Instead of relying only on a resume, recruiters can eventually evaluate:

```text
Resume
   +
Coding Ability
   +
Problem Solving
   +
SkillDNA
   +
Learning Behavior
   +
Career Readiness
```

---

# 🛡️ Admin Platform

The platform includes extensive administrative capabilities.

Admin modules include:

- User management
- Analytics
- AI monitoring
- Database management
- Permissions
- Reports
- System monitoring
- Settings
- Audit logs

---

# 🏗️ System Architecture

```text
                         CODEMIND DNA
                              │
              ┌───────────────┼───────────────┐
              │               │               │
              ▼               ▼               ▼
          STUDENT          MENTOR          RECRUITER
              │               │               │
              └───────────────┼───────────────┘
                              │
                              ▼
                    React Frontend
                              │
                    REST API / Axios
                              │
                              ▼
                     FastAPI Backend
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
      PostgreSQL          AI Services        Code Engine
          │                   │                   │
          │          ┌────────┼────────┐          │
          │          │        │        │          │
          │       Gemini    OpenAI    Groq         │
          │                                             │
          └───────────────────┬─────────────────────────┘
                              │
                              ▼
                       SkillDNA Engine
                              │
               ┌──────────────┼──────────────┐
               ▼              ▼              ▼
          Skill Analysis   Career AI    Recommendations
```

---

# 🛠️ Technology Stack

## Frontend

- React 18
- Vite
- JavaScript
- React Router
- Axios
- Monaco Editor
- Framer Motion
- Lucide React
- Tailwind CSS

## Backend

- Python 3.12
- FastAPI
- Uvicorn
- Pydantic
- SQLAlchemy
- Alembic
- JWT Authentication

## Database

- SQLite — local development
- PostgreSQL — production

## AI

- Google Gemini
- OpenAI
- Groq

## Development

- Git
- GitHub
- npm
- Python Virtual Environment
- Docker

## Deployment

- Render
- Docker
- Render Blueprint

---

# 📂 Project Structure

```text
Code-mind-dna-main/
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   │   ├── admin.py
│   │   │   ├── analytics.py
│   │   │   ├── auth.py
│   │   │   ├── dna.py
│   │   │   ├── execution.py
│   │   │   ├── goals.py
│   │   │   ├── problems.py
│   │   │   ├── recommendations.py
│   │   │   ├── recruiter.py
│   │   │   ├── student.py
│   │   │   ├── mentor_*.py
│   │   │   └── ...
│   │   │
│   │   ├── core/
│   │   │   ├── config.py
│   │   │   ├── database.py
│   │   │   ├── security.py
│   │   │   ├── middleware.py
│   │   │   └── ...
│   │   │
│   │   ├── models/
│   │   │   ├── user.py
│   │   │   ├── assessment.py
│   │   │   ├── dna_profile.py
│   │   │   ├── execution.py
│   │   │   ├── career.py
│   │   │   ├── analytics.py
│   │   │   └── ...
│   │   │
│   │   └── main.py
│   │
│   ├── alembic/
│   │   └── versions/
│   │
│   ├── requirements.txt
│   └── alembic.ini
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── vite.config.*
│   └── ...
│
├── Dockerfile
├── docker-compose.yml
├── render.yaml
├── .env.example
├── README.md
└── .github/
    └── workflows/
```

---

# 🚀 Run Locally

## Backend

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Code-mind-dna.git
cd Code-mind-dna
```

Create a virtual environment:

### Windows

```bash
cd backend
python -m venv .venv
.venv\Scripts\activate
```

### Linux / macOS

```bash
cd backend
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run FastAPI:

```bash
python -m uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

Backend:

```text
http://localhost:8000
```

API documentation:

```text
http://localhost:8000/docs
```

Health check:

```text
http://localhost:8000/api/health/live
```

---

# 💻 Frontend

Open another terminal:

```bash
cd frontend
npm ci
```

Start Vite:

```bash
npm run dev
```

Frontend:

```text
http://localhost:5173
```

---

# 🔐 Environment Variables

Create a `.env` file using `.env.example`.

Important variables include:

```env
DATABASE_URL=sqlite:///./codemind_dna.db

JWT_SECRET_KEY=your_secure_secret

JWT_ALGORITHM=HS256

ACCESS_TOKEN_EXPIRE_MINUTES=1440

CORS_ORIGINS=http://localhost:5173

AI_ENABLED=true

AI_PROVIDER=gemini

GEMINI_API_KEY=your_gemini_api_key

GEMINI_MODEL=gemini-2.5-flash
```

For production, use secure environment variables rather than committing secrets to GitHub.

---

# 🤖 AI Configuration

CodeMind DNA supports multiple AI providers.

Example:

```env
AI_ENABLED=true
AI_PROVIDER=gemini
GEMINI_API_KEY=YOUR_API_KEY
GEMINI_MODEL=gemini-2.5-flash
```

Other supported providers include:

```text
OpenAI
Groq
Gemini
```

AI features can be disabled when an external API key is not available.

---

# ☁️ Deploy to Render

The repository includes:

```text
render.yaml
```

which defines two Render services:

```text
                 Render
                   │
        ┌──────────┴──────────┐
        │                     │
        ▼                     ▼
   React Frontend        FastAPI Backend
        │                     │
        │                     │
        ▼                     ▼
codemind-dna-frontend   codemind-dna-backend
.onrender.com            .onrender.com
```

---

# 🚀 Render Deployment

## Step 1 — Push to GitHub

```bash
git add .
git commit -m "Prepare CodeMind DNA for deployment"
git push origin main
```

---

## Step 2 — Create Render Blueprint

Open Render and select:

```text
New +
   ↓
Blueprint
```

Connect your GitHub repository.

Render will detect:

```text
render.yaml
```

---

## Step 3 — Backend

The backend uses:

```yaml
rootDir: backend
```

Build:

```bash
pip install -r requirements.txt
```

Start:

```bash
uvicorn app.main:app --host 0.0.0.0 --port $PORT
```

Health check:

```text
/api/health/live
```

---

# 🌐 Backend Environment Variables

Configure:

```text
JWT_SECRET_KEY
CORS_ORIGINS
ADMIN_PHONE_NUMBERS
DATABASE_URL
```

If using Gemini:

```text
AI_ENABLED=true
AI_PROVIDER=gemini
GEMINI_API_KEY=your_api_key
GEMINI_MODEL=gemini-2.5-flash
```

Never commit API keys to GitHub.

---

# 🎨 Frontend Deployment

Render builds the React application using:

```bash
npm ci && npm run build
```

The production files are generated in:

```text
frontend/dist
```

Render serves:

```text
frontend/dist
```

The frontend API URL is:

```text
https://codemind-dna-backend.onrender.com/api
```

configured through:

```env
VITE_API_URL
```

---

# 🔄 Client-Side Routing

Because CodeMind DNA uses React Router, Render is configured to redirect unknown frontend routes to:

```text
/index.html
```

This allows routes such as:

```text
/dashboard
/student
/mentor
/recruiter
/admin
```

to work correctly after refreshing the browser.

---

# 🏥 Health Check

Backend health endpoint:

```text
https://codemind-dna-backend.onrender.com/api/health/live
```

A successful response indicates that the FastAPI backend is running.

---

# 🔑 Authentication

CodeMind DNA uses JWT-based authentication.

Authentication flow:

```text
User
 │
 ▼
Login
 │
 ▼
FastAPI
 │
 ▼
Validate Credentials
 │
 ▼
Generate JWT
 │
 ▼
Frontend
 │
 ▼
Authenticated API Requests
```

---

# 👥 User Roles

The platform is designed around multiple user types:

```text
Student
Mentor
Recruiter
Admin
```

Each role has different capabilities and dashboards.

---

# 🧑‍💻 Coding Evaluation

The coding workflow is designed around:

```text
Problem
   ↓
Coding
   ↓
Execution
   ↓
Submission
   ↓
Result
   ↓
Analytics
   ↓
SkillDNA
   ↓
Recommendations
```

This creates a continuous feedback loop between coding activity and career development.

---

# 🧬 SkillDNA Intelligence

The central concept of CodeMind DNA is the **SkillDNA Profile**.

Instead of evaluating candidates using only:

```text
Marks
Resume
Certificates
```

the platform aims to combine:

```text
Coding Performance
       +
Problem Solving
       +
Learning Progress
       +
Assessment Results
       +
Behavior
       +
Skill Development
```

into a continuously evolving developer profile.

---

# 📊 Future Enhancements

Planned improvements include:

- Advanced AI coding analysis
- More programming languages
- Secure cloud code execution
- Advanced anti-cheating mechanisms
- AI mock interviews
- Resume intelligence
- GitHub intelligence
- Job-market intelligence
- Recruiter candidate scoring
- Advanced SkillDNA prediction
- Personalized learning paths
- Industry readiness scoring
- Real-time mentor alerts
- Advanced analytics
- Mobile application

---

# 🔒 Security

The project includes security mechanisms such as:

- JWT authentication
- Password hashing
- Authentication rate limiting
- Request size limits
- CORS configuration
- Audit logging
- Permission management
- Environment-based secrets
- API validation

For production, additionally consider:

- HTTPS-only secure cookies where applicable
- Strong secret rotation
- PostgreSQL instead of SQLite
- Secure code execution isolation
- Container sandboxing
- Rate limiting at the infrastructure level
- Security headers
- Monitoring and alerting

---

# 🧪 Testing

Backend tests can be run using:

```bash
pytest
```

Frontend tests:

```bash
npm run test
```

Frontend production build:

```bash
npm run build
```

---

# 🐳 Docker

Build the backend image:

```bash
docker build -t codemind-dna .
```

Run:

```bash
docker run -p 8000:8000 codemind-dna
```

Open:

```text
http://localhost:8000
```

---

# 📌 Project Vision

CodeMind DNA aims to evolve from a coding assessment platform into an **AI-powered Student and Talent Intelligence Platform**.

The long-term vision is:

```text
                    CodeMind DNA
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
     Student           Mentor          Recruiter
        │                │                │
        └────────────────┼────────────────┘
                         │
                         ▼
                  Skill Intelligence
                         │
                         ▼
                    SkillDNA
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
          Learning     Career       Jobs
          Guidance   Readiness    Matching
```

---

# 👨‍💻 Author

**Raghu**

Information Science & Engineering

CodeMind DNA is developed as an academic, portfolio, and product-development project focused on AI, software engineering, coding intelligence, and career technology.

---

# ⭐ Support

If you find CodeMind DNA interesting, consider giving the repository a ⭐ Star.

---

## 🌐 Live Demo

**CodeMind DNA**

https://codemind-dna-frontend.onrender.com

### Backend API

https://codemind-dna-backend.onrender.com

### API Documentation

https://codemind-dna-backend.onrender.com/docs

---

## 📜 License

This project is currently intended for educational, portfolio, and research purposes.
