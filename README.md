<<<<<<< HEAD
# Ai-ChatBot
=======
# ⚡ Apex Chatbot

**Apex** is a next-generation AI assistant designed for speed, intelligence, and seamless interaction. It combines the power of large language models with real-time internet search and advanced voice capabilities to deliver a premium user experience.

![Apex Banner](https://via.placeholder.com/1200x400?text=Apex+Chatbot+Project) _<!-- Replace with actual project screenshot if available -->_

## 🚀 Features

- **🗣️ Advanced Voice Mode**: Real-time, low-latency voice interaction with emotion detection and bilingual support (English/Hindi), inspired by GPT-4o.
- **🌐 Live Internet Access**: Fetches the latest information using **SerpAPI** (Google) and **DuckDuckGo** to provide up-to-date answers.
- **📚 Smart Knowledge Retrieval**: Integrates **Wikipedia** for accurate factual summaries.
- **⚡ Ultra-Fast AI**: Powered by **Groq** (Llama 3 / Mixtral) for instant text and voice responses.
- **🎨 Modern UI/UX**: Built with **Next.js 14**, featuring a sleek dark mode, glassmorphism effects, and fluid animations using **Framer Motion**.
- **🔐 Secure Authentication**: User sign-in and session management.
- **💬 Persistent Chat History**: Saves your conversations for future reference.

## 🛠️ Tech Stack

### Frontend

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS, CSS Modules
- **Animations**: Framer Motion
- **Icons**: Lucide React

### Backend

- **Framework**: FastAPI (Python)
- **Server**: Uvicorn
- **Real-Time**: WebSockets (for Voice Mode)
- **Search Engines**: SerpAPI, DuckDuckGo
- **Audio Processing**: Deepgram / ElevenLabs (TTS), Groq Whisper (STT)

## 📦 Installation & Setup

Follow these steps to set up the project locally.

### Prerequisites

- **Node.js** (v18+)
- **Python** (v3.10+)
- **Git**

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/apex-chatbot.git
cd apex-chatbot
```

### 2. Backend Setup

Navigate to the backend folder and set up the Python environment.

```bash
cd backend
# Create virtual environment (optional but recommended)
python -m venv venv
# Activate:
# Windows: .\venv\Scripts\activate
# Mac/Linux: source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

**Configuration (.env)**  
Create a `.env` file in the `backend/` directory and add your API keys:

```env
GROQ_API_KEY=your_groq_api_key
SERPAPI_API_KEY=your_serpapi_key  # Optional, for Google Search
DEEPGRAM_API_KEY=your_deepgram_key # For Voice Mode
ELEVENLABS_API_KEY=your_elevenlabs_key # Optional alternative for TTS
```

**Run the Backend Server**

```bash
python -m uvicorn main:app --reload
```

_Server running at: `http://localhost:8000`_

### 3. Frontend Setup

Open a new terminal and navigate to the frontend folder.

```bash
cd frontend
# Install dependencies
npm install

# Run the development server
npm run dev
```

_App running at: `http://localhost:3000`_

## 🎯 Usage

1.  **Text Chat**: Open the app and start typing. Ask about current events (e.g., "Latest news on AI") to trigger the search engine.
2.  **Voice Mode**: Click the **"Voice Mode (Beta)"** button in the sidebar. Grant microphone permissions to talk to Apex in real-time.
3.  **Bilingual Chat**: Try speaking in Hindi or Hinglish; Apex understands and responds accordingly.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## 📄 License

This project is licensed under the MIT License.

---

_Built with ❤️ by [Dibendu Mondal]_
>>>>>>>  
