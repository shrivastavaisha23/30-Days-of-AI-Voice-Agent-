# 30-Days-of-AI-Voice-Agent-
A 30 Day journey of building intelligent voice AI agent using python,Flask, and Murf AI. This repository documents my daily progress in the 30 days of  voice agent challenge by Murf AI.
This project is part of the Murf AI 30 Days of AI Voice Agents Challenge.
It’s an AI-powered voice chatbot built using FastAPI, JavaScript, and AssemblyAI for Speech-to-Text (STT) and Text-to-Speech (TTS), with LLM-powered conversation capabilities.

🚀 #Features

🎤 Real-time Voice Input — Record your voice directly in the browser using MediaStream API.

📝 Speech-to-Text (STT) — Convert spoken audio into text using AssemblyAI API.

🤖 LLM Integration — Get intelligent, contextual AI responses using OpenAI API (or other LLM providers).

🔊 Text-to-Speech (TTS) — AI-generated responses are read aloud for a natural conversation flow.

💬 Chat Interface — Simple, responsive UI for seamless interaction.

#Tech Stack

Frontend

HTML, CSS, JavaScript (MediaStream API, Fetch API)

Backend

FastAPI (Python)

AssemblyAI API (Speech-to-Text)

OpenAI API (LLM) / Claude API (optional)

Other Tools

dotenv (Environment variables)

CORS Middleware (Cross-origin requests)

#Architecture
 User 🎤 → Browser (MediaStream API) → FastAPI Backend  
→ AssemblyAI STT → Text Output  
→ LLM API (OpenAI/Claude) → AI Response  
→ TTS API (AssemblyAI/Murf) → Audio Output 🔊

#Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/ai-voice-agent.git
cd ai-voice-agent
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Set up environment variables
ASSEMBLYAI_API_KEY=your_assemblyai_api_key
OPENAI_API_KEY=your_openai_api_key
Create a .env file in the root directory and add:
4️⃣ Run the backend server
 2-RUN THE APP:
python app.py
uvicorn main:app --reload
5️⃣ Open the frontend
Open index.html in your browser, or
Serve it with a simple HTTP server:
python -m http.server 8000

