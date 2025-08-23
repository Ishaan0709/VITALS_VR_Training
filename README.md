# 🩺 AIxVR TechVitals — AI Surgical Mentor

**AIxVR TechVitals** is a full-stack AI + VR platform built for medical students, especially those pursuing surgical training.  
Developed as part of the **Israel–India Hackathon (Hack4Help)**, this project combines an **AI-powered chatbot**, a **responsive surgical training web app**, and an upcoming **VR simulation module** for immersive practice.  

---

## 🌐 Live Demos
- 🌍 **Main Website:** [Vitals WebApp](https://final-med.vercel.app)  
- 🤖 **AI Chatbot:** [Medimentor Bot](https://medimentor-two.vercel.app)  
- 🕶 **VR Surgical Simulator (Planned):** [VR Prototype](https://medical-vr.vercel.app)  

---

## 📖 Description
Modern medical students face a huge challenge — **theory-heavy learning with minimal hands-on surgical exposure**.  
Cadaver training is limited, expensive, and often unavailable. Students enter hospitals **underprepared**, impacting confidence and patient safety.  

**AIxVR TechVitals** bridges this gap by offering:  
1. An **AI Surgical Mentor** for instant, specialist-informed medical knowledge.  
2. A **WebApp** for structured, interactive guidance.  
3. A **Unity-based VR simulator** (in development) for immersive surgical training.  

This ensures **safe, repeatable, and cost-effective practice opportunities** for students worldwide.  

---

## ✨ Features
- **AI-powered Chatbot** 🤖 — Get instant answers to surgical & medical queries.  
- **Personalized Guidance** 🧠 — Context-aware learning tailored to the student.  
- **Full-stack Deployment** 🚀 — Frontend on Vercel, Backend API on Render.  
- **Responsive Design** 📱💻 — Works seamlessly on mobile & desktop.  
- **VR Simulation (Planned)** 🎮 — Safe, repeatable practice for surgical procedures.  

---

## 🛠 Tech Stack

- **Frontend (Vitals_WebApp):**
  - React 18 + Vite ⚡ (ultra-fast build & dev environment)  
  - Tailwind CSS 🎨 (responsive, utility-first design)  
  - Deployed on **Vercel** (global edge network)  

- **Backend (Vitals_AI_Bot):**
  - Python (FastAPI) 🚀  
  - RESTful APIs with async support  
  - Secure environment variables + CORS enabled  
  - Deployed on **Render** (auto-scaling cloud platform)  

- **AI Model:**
  - OpenAI GPT-4 API 🤖 — Advanced reasoning & conversational intelligence  
  - Context persistence + prompt engineering for personalized responses  
  - Domain-specific tuning for **surgical & medical queries**  
  - Future-ready → **LangChain + Vector DB (RAG)** integration for specialist datasets  
  - Scalable design → plug-in for fine-tuned healthcare LLMs  

- **VR Simulation (Vitals_Unity_Simulation — Planned):**
  - Unity 3D + WebGL 🌐 for immersive simulations  
  - VR headset compatibility (Meta Quest, HTC Vive, etc.)  
  - Future haptics & device support for realistic surgical practice  

- **Other:**
  - GitHub Actions CI/CD pipelines  
  - Cloud-native deployment architecture  
  - Git for version control & team collaboration  

---

## 🚀 How to Run Locally

### 1. Clone Repository
```bash
git clone https://github.com/Ishaan0709/AIxVR_TechVitals.git
cd AIxVR_TechVitals
2. Run AI Bot (Backend)
bash
Copy
Edit
cd Vitals_AI_Bot
pip install -r requirements.txt
uvicorn main:app --reload
3. Run WebApp (Frontend)
bash
Copy
Edit
cd Vitals_WebApp
# Start dev server
npm install
npm run dev
4. (Planned) Run Unity Simulation
bash
Copy
Edit
cd Vitals_Unity_Simulation
# Open project in Unity
📦 Deployment
Frontend (Vitals_WebApp): Vercel

Backend (Vitals_AI_Bot): Render

Simulation (Future): Unity + Cloud/Standalone
