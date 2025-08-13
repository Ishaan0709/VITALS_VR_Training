# Medimentor — AI Mentor for Medical Students (Full-stack)

Live app: https://medimentor-two.vercel.app

Medimentor is a full-stack AI chatbot that helps medical students (esp. surgery) with quick, personalized answers.  
Frontend is a static web app; backend is a Python API that calls LLMs and (optionally) retrieval sources.

---

## Features
- Q&A for surgical/clinical topics with concise, safe answers
- Context memory per session
- Ready for RAG: plug PDFs/notes to ground answers (optional)
- Production deploy: Frontend (Vercel) + Backend API (Render/any VM)

---

## Architecture (high level)
