# 🤖 AI Interview Bot

An intelligent, interactive web-based system for conducting mock interviews using the **Gemini API**, **speech recognition**, **text-to-speech**, and **real-time body language monitoring**.

## 🚀 Features

- ✅ Generate domain-specific interview questions (Technical / HR)
- 🧠 Answer evaluation with feedback and scoring using Gemini AI
- 🎙️ Voice input with speech-to-text transcription
- 🔊 Text-to-speech to read questions aloud
- 📷 Real-time webcam-based body language analysis using MediaPipe
- 📊 Final score report at the end of the interview

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **AI**: Google Gemini API (`gemini-2.0-flash`)
- **Voice & Vision**: Whisper/Vosk (ASR), MediaPipe (pose & face detection)

## 📦 Setup Instructions

### 1. Clone the repository


git clone https://github.com/NiranjanKJ304/AI-InterviewBot.git
cd AI-interview BOT

cd backend
pip install -r requirements.txt

create your own API KEY
 Set up your .env
Create a .env file in the backend folder:
GEMINI_API_KEY=your_gemini_api_key

RUNNING: 

for backend:
- cd backend
- python app.py

for frontend:
- cd frontend
- python -m http.server 8000

