# 🎙️ Voice Chat with Your PDFs (Yes, Really!)

Welcome to the **Voice Chat with PDFs** project! Imagine talking to your PDFs and getting answers like a real conversation, powered by the magical combo of [LlamaIndex](https://www.llamaindex.ai/) and [Next.js](https://nextjs.org/). It's like turning your PDFs into your personal assistants!

## What’s Going On Here?

This project takes inspiration from the super cool [openai-realtime-console](https://github.com/openai/openai-realtime-console), but we’ve spiced it up by adding a simple RAG system (fancy talk for making your chats smarter) using [LlamaIndexTS](https://ts.llamaindex.ai/).

## Prerequisites

- **An OpenAI API Key** – This is the magic wand that powers the whole thing. You can get one (user key or project key) and pop it into the `.env` file or set it as an environment variable (`OPENAI_API_KEY`). Trust me, it won’t work without it!

## Getting Started

### Step 1: Install the Stuff
Run this magical line to get all the things you need:
```bash
npm install
npm run generate
npm run dev
```

### Launching the App

Open [http://localhost:3000](http://localhost:3000) in your browser and watch the magic happen! ✨

### Using the Voice Console

When you first start the app, it might ask you for the API key again (yeah, it’s a little annoying, we know…).
Connect to start chatting, and don’t forget to give the app microphone access (so it can hear you!).
Choose between Push-to-talk (manual mode) or VAD (Voice Activity Detection) mode, where it listens when you start talking. You can switch anytime!
Interrupt the AI? Sure! You’re in charge.

### Learning More

If you’re curious about LlamaIndex and want to level up your skills, check out these awesome resources:

* [LlamaIndex Documentation (Python)](https://www.llamaindex.ai/docs/python)
* [LlamaIndexTS Documentation (Typescript)](https://ts.llamaindex.ai/docs)

