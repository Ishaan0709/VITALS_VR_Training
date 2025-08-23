# 🩺 Medimentor — AI Surgical Mentor

**Live Demo:** https://medimentor-two.vercel.app

Medimentor is a **full-stack AI chatbot** built for **medical students**, especially those pursuing surgical training.  
It provides instant, personalized answers to medical and surgical queries using AI trained on inputs from multiple specialists.

---

## ✨ Features
- **AI-powered Chatbot** — Get answers to surgical & medical questions instantly.
- **Personalized Guidance** — Context-aware responses for better learning.
- **Full-stack Deployment** — Frontend on Vercel, Backend API on Render.
- **Responsive Design** — Works on both mobile and desktop.

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vercel)
- **Backend:** Python (FastAPI) — Render deployment
- **AI Model:** OpenAI GPT API
- **Other:** CORS handling, secure environment variables

---

---

 How to Run Locally

### 1. Clone Repository
```bash
git clone https://github.com/Ishaan0709/Medimentor.git
cd Medimentor

- Backend Setup
cd backend
pip install -r ../requirements.txt


- Start backend:

uvicorn main:app --reload



- Frontend Setup

Open frontend/index.html directly in browser
OR if using live server in VS Code, right-click and select Open with Live Server.


- Deployment

Frontend: Deployed on Vercel

Backend: Deployed on Render
