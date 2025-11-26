<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI-Enabled Real-Time AI Sales Call Assistant</title>
<style>
  body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; background: #f8f9fa; color: #333; }
  h1, h2, h3 { color: #2c3e50; }
  pre { background: #ecf0f1; padding: 10px; border-radius: 5px; overflow-x: auto; }
  code { background: #ecf0f1; padding: 2px 4px; border-radius: 4px; }
  ul { margin-bottom: 15px; }
  .section { margin-bottom: 30px; }
  a { color: #2980b9; text-decoration: none; }
  a:hover { text-decoration: underline; }
</style>
</head>
<body>

<h1>📞 AI-Enabled Real-Time AI Sales Call Assistant</h1>

<div class="section">
<h2>🚀 Overview</h2>
<p>An intelligent, real-time AI-powered sales assistant that listens to calls, transcribes conversations, performs sentiment and recommendation analysis, and provides instant AI-guided suggestions to help sales teams close deals efficiently.</p>
</div>

<div class="section">
<h2>🌟 Key Features</h2>
<ul>
  <li>Real-Time Speech-to-Text (STT) using <strong>Deepgram API</strong></li>
  <li>Text-to-Speech (TTS) for AI responses using Deepgram</li>
  <li>AI Agent Suggestions powered by <strong>Google Gemini LLM</strong></li>
  <li>Real-time sentiment & recommendation analysis</li>
  <li>Secure User Authentication using SHA-256 hashes stored in MongoDB Atlas</li>
  <li>Call transcript storage in MongoDB for historical analysis</li>
  <li>Real-time agent dashboard via LiveKit</li>
</ul>
</div>

<div class="section">
<h2>🏗️ Project Structure</h2>
<pre>
AI-Enabled-Real-Time-AI-Sales-Call-Assistant/
│── backend_mongo/        # Node.js backend + MongoDB Atlas
│── frontend/             # Next.js + React + LiveKit client
│── Agent/                # AI agent logic & LLM prompts
│── .claude/              # Optional AI model configs
│── README.md
</pre>
</div>

<div class="section">
<h2>🔧 Technologies Used</h2>
<h3>Frontend</h3>
<ul>
  <li>React.js / Next.js</li>
  <li>TypeScript</li>
  <li>Tailwind CSS</li>
  <li>LiveKit Client for real-time audio/video</li>
  <li>Deepgram STT/TTS</li>
</ul>

<h3>Backend</h3>
<ul>
  <li>Node.js / Express.js</li>
  <li>MongoDB Atlas</li>
  <li>SHA-256 for password hashing</li>
  <li>LiveKit Server integration</li>
  <li>WebSockets for real-time communication</li>
</ul>

<h3>AI / ML / LLM</h3>
<ul>
  <li>Google Gemini API for AI suggestions</li>
  <li>Real-time sentiment analysis</li>
  <li>Recommendation analysis</li>
  <li>Call summarization</li>
</ul>
</div>

<div class="section">
<h2>🧩 How It Works</h2>
<ol>
  <li><strong>User Authentication:</strong> Users register/login with SHA-256 hashed passwords stored in MongoDB Atlas.</li>
  <li><strong>Real-Time Call Processing:</strong> Audio → LiveKit → Backend → Deepgram STT → Text → Google Gemini LLM → AI recommendations.</li>
  <li><strong>Sentiment & Recommendation Analysis:</strong> Calculates sentiment and provides live suggestions.</li>
  <li><strong>AI Response via TTS:</strong> Deepgram converts AI text to speech in real-time.</li>
  <li><strong>Transcript & Analytics:</strong> All transcripts stored in MongoDB for historical analysis and improving AI recommendations.</li>
</ol>
</div>

<div class="section">
<h2>🏁 Getting Started</h2>
<h3>Prerequisites</h3>
<ul>
  <li>Node.js v18+</li>
  <li>pnpm or npm</li>
  <li>MongoDB Atlas cluster</li>
  <li>LiveKit server</li>
  <li>Deepgram API key</li>
  <li>Google Gemini API key</li>
</ul>

<h3>Clone the Repository</h3>
<pre>git clone https://github.com/&lt;your-username&gt;/AI-Enabled-Real-Time-AI-Sales-Call-Assistant.git
cd AI-Enabled-Real-Time-AI-Sales-Call-Assistant</pre>

<h3>Install Frontend Dependencies</h3>
<pre>cd frontend
pnpm install  # or npm install</pre>

<h3>Install Backend Dependencies</h3>
<pre>cd backend_mongo
npm install</pre>

<h3>Setup Environment Variables</h3>
<p><strong>Backend .env:</strong></p>
<pre>
MONGO_URI=<your_mongodb_atlas_uri>
LIVEKIT_API_KEY=<your_livekit_key>
LIVEKIT_SECRET=<your_livekit_secret>
DEEPGRAM_API_KEY=<your_deepgram_key>
GOOGLE_GEMINI_API_KEY=<your_google_gemini_key>
PORT=5000
</pre>

<p><strong>Frontend .env.local:</strong></p>
<pre>
NEXT_PUBLIC_LIVEKIT_URL=<your_livekit_url>
NEXT_PUBLIC_BACKEND_URL=<your_backend_url>
</pre>

<h3>Start Servers</h3>
<p>Frontend:</p>
<pre>cd frontend
pnpm dev</pre>
<p>Backend:</p>
<pre>cd backend_mongo
npm start</pre>
</div>

<div class="section">
<h2>🛠️ Roadmap</h2>
<ul>
  <li>Multi-language support</li>
  <li>Advanced AI recommendation engine</li>
  <li>Supervisor monitoring dashboard</li>
  <li>CRM integration</li>
  <li>Export call analytics & summaries</li>
</ul>
</div>

<div class="section">
<h2>🤝 Contributing</h2>
<p>Fork the repo → Create a branch → Submit a pull request. All contributions are welcome!</p>
</div>

<div class="section">
<h2>📄 License</h2>
<p>MIT License</p>
</div>

<div class="section">
<h2>💬 Contact</h2>
<p>Email: <em>your email here</em></p>
<p>GitHub: <a href="https://github.com/your-username">your-username</a></p>
</div>

</body>
</html>
