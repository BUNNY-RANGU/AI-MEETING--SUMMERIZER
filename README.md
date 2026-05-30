<div align="center">

# AI Meeting Summarizer

Meeting intelligence platform for transcription, summaries, sentiment heatmaps, action items, and empathetic follow-ups.

[![Next.js](https://img.shields.io/badge/Next.js-frontend-black)](https://nextjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-backend-green)](https://fastapi.tiangolo.com)
[![Groq](https://img.shields.io/badge/Groq-Whisper%20transcription-orange)](#ai-architecture)
[![Gemini](https://img.shields.io/badge/Gemini-analysis-blue)](#ai-architecture)

</div>

## Overview

AI Meeting Summarizer turns meeting recordings into structured business intelligence. It is built to go beyond a normal transcript by extracting summaries, action items, emotional flow, and follow-up drafts.

## Core Capabilities

| Capability | Description |
|---|---|
| Transcription | Converts meeting audio into text |
| Multilingual Summaries | Produces summaries across language preferences |
| Sentiment Heatmap | Visualizes emotional flow across the meeting |
| Action Items | Extracts owners, decisions, and next steps |
| Smart Outreach | Drafts follow-up emails or Slack-style messages |
| Session History | Keeps local meeting intelligence for review |

## AI Architecture

```text
Audio Upload
  -> Groq Whisper transcription
  -> Gemini analysis
  -> Summary, sentiment, action items
  -> Follow-up draft
```

## Tech Stack

- Next.js and React
- Tailwind CSS
- Framer Motion
- FastAPI
- Groq Whisper
- Google Gemini

## Run Locally

Backend:

```bash
cd ai-meeting-summarizer/backend
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

Frontend:

```bash
cd ai-meeting-summarizer
npm install
npm run dev
```

## Environment

Create a backend `.env` file:

```env
GROQ_API_KEY=
GEMINI_API_KEY=
```

## Use Cases

- Team meeting summaries
- Founder and startup call notes
- Class or workshop summaries
- Cross-language meeting review
- Follow-up automation drafts

## Author

Built by [Rangu Suchandra](https://github.com/BUNNY-RANGU).
