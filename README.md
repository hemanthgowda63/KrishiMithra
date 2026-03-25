# 🌱 KrishiMitra

**KrishiMitra** is a full-stack agri-assistant platform built with a **FastAPI backend** and a **React (Vite) frontend**. It provides intelligent farming assistance through **multilingual chatbot support, crop disease detection, authentication workflows, and voice-enabled interactions**.

---

## 🚀 Project Overview

KrishiMitra helps farmers with:
- 🌾 Smart crop guidance
- 🦠 Crop disease detection
- 🗣️ Multilingual chatbot interaction
- 🎤 Voice-enabled communication (input + output)

---

## 📌 Key Features

### 🔐 Authentication & User Flow
- Secure login-first protected routing
- Mandatory language selection for new users
- Updated auth callback and navigation flows

### 🤖 Chatbot System
- Powered by **Groq-based LLM**
- Multilingual support
- Voice-enabled interaction
- API key rotation and fallback handling

### 🌿 Crop Disease Detection
- Vision-based pipeline integration
- Backend service enhancements
- Model fallback support

### 🎙️ Voice Features (Browser-Based)
- Microphone input using Web Speech API
- Auto-send recognized speech
- Browser text-to-speech (`speechSynthesis`)
- Voice toggle with persistent preference
- No external API required

### 🏠 Dashboard Experience
- One-time greeting using browser TTS after login
- Session-based execution

---

## 📊 A–Z Progress Snapshot

- ✅ Authentication flow hardened
- ✅ Multilingual chatbot implemented
- ✅ Groq LLM integration with key rotation
- ✅ Crop disease detection pipeline integrated
- ✅ Browser-based voice input/output enabled
- ✅ Dashboard greeting implemented
- ✅ Backend routes and services expanded
- ✅ Config and routing updates completed
- ✅ UI/UX improvements for chatbot voice controls
- ✅ Error handling fixes applied
- ✅ Feature branch (`feature1`) updated
- ⚠️ Pending: Cross-browser testing

---

## 🛠️ Recent Work

### 1️⃣ Feature Integration
**Commit:** `be91604`  
**Message:** `feat: add Groq crop vision and voice service integration`

**Files Updated:**
- Backend:
  - `config.py`
  - `routes/voice.py`
  - `services/crop_disease_service.py`
  - `services/voice_service.py`
  - Tests updated
- Frontend:
  - `AuthCallback.jsx`
  - `Chatbot.jsx`

---

### 2️⃣ Browser Voice Improvements
**Commit:** `3eda10f`  
**Message:** `fix: enable browser speech input output and home greeting`

**Enhancements:**
- 🎤 Mic button → Speech recognition
- ✉️ Auto-send recognized speech
- 🔊 Bot voice output using browser TTS
- 🏠 One-time greeting after login

---

### 3️⃣ Validation
- ✅ No frontend errors
- ✅ Vite server running successfully
- ✅ Port fallback handled (`5174`)
- ✅ Changes pushed to `feature1`

---

## 🌿 Branch History (`feature1`)


---

## ⚙️ Tech Stack

### Backend
- FastAPI
- Python
- Groq API
- Vision Model Integration

### Frontend
- React (Vite)
- Web Speech API
- Context API

---

## 💻 Local Development

### 🔧 Backend

```bash
cd backend
python -m venv .venv

# Activate (Windows PowerShell)
.\.venv\Scripts\Activate.ps1

pip install -r requirements.txt
uvicorn app.main:app --reload


🎨 Frontend
cd frontend
npm install
npm run dev
⚠️ Notes & Limitations
Voice features depend on:
Browser support (Chrome/Edge recommended)
Microphone & speaker permissions
Browser TTS works without API key
Manual testing required for cross-browser validation
✅ Verification Checklist
🔐 Login → Check one-time greeting
🎤 Chatbot → Speak → Message auto-sent
🔊 Voice ON → Bot response spoken
🔇 Voice OFF → No speech output
📁 Project Structure
krishimitra/
├── backend/
│   ├── app/
│   │   ├── config.py
│   │   ├── main.py
│   │   ├── routes/
│   │   └── services/
│   └── tests/
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   └── context/
│   └── ...
│
└── README.md
🚧 Future Improvements
🌐 Cross-browser voice testing
📱 Mobile optimization
📊 Advanced analytics dashboard
🔌 Optional external integrations
📌 Summary

KrishiMitra is a modern agri-assistant platform combining:

AI-powered chatbot 🤖
Vision-based crop analysis 🌿
Voice interaction 🎙️
Secure authentication 🔐

Designed for scalability, usability, and real-world farmer support.


---

If you want next level 🔥:
- I can add **GitHub badges (build, license, tech stack)**  
- Add **screenshots section (very important for hackathons)**  
- Or make it **top 1% professional README (like open-source projects)**
