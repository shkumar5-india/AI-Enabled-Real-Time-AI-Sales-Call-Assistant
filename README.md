
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
