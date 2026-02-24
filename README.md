# 🎙️ Global Agent Intelligence: AI Meeting Summarizer

An innovative, state-of-the-art AI platform that transforms meeting recordings into deep, actionable intelligence. Featuring a **Global Agent Suite**, this application goes beyond simple transcription to provide emotional insights and cross-lingual analysis.

![MeetingPulse Heatmap Interface](public/dashboard-preview.png) *(Note: Add your own screenshot here)*

## 🌟 Key Innovations

### 🌍 Universal Language Bridge
- **Multilingual Support**: Upload meetings in any language and receive summaries in your target language (English, Hindi, Spanish, French, etc.).
- **Automatic Translation**: Seamlessly bridges communication gaps in global teams.

### 📊 Emotional Sentiment Heatmap
- **MeetingPulse Engine**: Visualizes the "heartbeat" of your meeting with a dynamic SVG sentiment graph.
- **Momentum Tracking**: Track the emotional flow—from tense debates to productive alignment—across the duration of the meeting.

### 💖 Empathy-Aware Smart Outreach
- **Contextual Drafting**: Automatically generates follow-up emails or Slack messages that match the *emotional tone* of the meeting.
- **Agent Intelligence**: The agent detects excitement or concern and adjusts its language to ensure professional, empathetic follow-ups.

## 🚀 Tech Stack

- **Frontend**: Next.js 14, React, Tailwind CSS, Framer Motion (for premium animations).
- **Backend**: FastAPI (Python), Uvicorn.
- **AI Intelligence**: 
  - **Transcription**: Groq (Whisper-large-v3) for near-instant precision.
  - **Analysis**: Google Gemini 2.5 Flash for deep reasoning and multilingual support.
- **State Management**: LocalStorage for session-based meeting persistence.

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/BUNNY-RANGU/AI-MEETING--SUMMERIZER.git
cd AI-MEETING--SUMMERIZER
```

### 2. Backend Setup
```bash
cd ai-meeting-summarizer/backend
# Create a virtual environment
python -m venv .venv
source .venv/bin/activate # On Windows use: .venv\Scripts\activate
# Install dependencies
pip install -r requirements.txt
# Set up .env
# Create a .env file with:
# OPENAI_API_KEY=your_groq_key
# GEMINI_API_KEY=your_gemini_key
python main.py
```

### 3. Frontend Setup
```bash
cd ai-meeting-summarizer
npm install
npm run dev
```

## 📐 Architecture
The system uses a **Dual-Agent Architecture**:
1. **The Scribe**: Handled by Groq/Whisper, focusing on high-fidelity audio-to-text conversion.
2. **The Analyst**: Handled by Gemini, performing multi-step reasoning: Sentiment Extraction -> Summary Synthesis -> Action Item Mapping -> Outreach Drafting.

## 📄 License
MIT License - Created with passion for innovative AI communication.
