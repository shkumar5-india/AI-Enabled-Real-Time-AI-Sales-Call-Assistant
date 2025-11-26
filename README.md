# AI-Enabled Real-Time AI Sales Call Assistant

An intelligent, real-time AI-powered sales assistant that listens to calls, transcribes conversations, performs sentiment and recommendation analysis, and provides instant AI-guided suggestions to help sales teams close deals efficiently.

---

## Overview

The AI-Enabled Real-Time Sales Call Assistant enhances sales team performance using AI and real-time analytics. It provides real-time transcription, AI-guided recommendations, call sentiment tracking, and automated summarization.

---

## Key Features

- **Real-Time Speech-to-Text (STT)** using Deepgram API  
- **Text-to-Speech (TTS)** for AI responses using Deepgram  
- **AI Agent Suggestions** powered by Google Gemini LLM  
- **Real-time Sentiment & Recommendation Analysis**  
- **Secure User Authentication** using SHA-256 hashes stored in MongoDB Atlas  
- **Call Transcript Storage** in MongoDB for historical analysis  
- **Real-Time Agent Dashboard** via LiveKit  

---

## Technologies Used

### Frontend
- React.js / Next.js  
- TypeScript  
- Tailwind CSS  
- LiveKit Client for real-time audio/video  
- Deepgram STT/TTS  

### Backend
- Node.js / Express.js
- Python FastAPI
- MongoDB Atlas  
- SHA-256 for password hashing  
- LiveKit Server integration  
- WebSockets for real-time communication  

### LLM ,STT & TTS ,Integration
- Google Gemini API for AI suggestions  
- Real-time sentiment analysis  
- Recommendation analysis  

---

## How It Works

1. **User Authentication**  
   Users register/login with SHA-256 hashed passwords stored in MongoDB Atlas.  

2. **Real-Time Call Processing**  
   User audio streams via LiveKit → Backend → Deepgram STT → Text → Google Gemini LLM → AI recommendations.  

3. **Sentiment & Recommendation Analysis**  
   Real-time sentiment scoring and AI guidance is calculated and displayed live.  

4. **AI Response via TTS**  
   Deepgram converts AI text responses to speech and streams back to the user in real-time.  

5. **Transcript & Analytics**  
   All transcripts stored in MongoDB for historical analysis, training, and improving AI recommendations.  

---

## 🏁 Getting Started

### Prerequisites
- Node.js v18+  
- pnpm or npm  
- MongoDB Atlas cluster  
- LiveKit server  
- Deepgram API key  
- Google Gemini API key  


## 📄 License

MIT License
