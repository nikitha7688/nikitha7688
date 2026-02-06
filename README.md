# NexaChat — AI Chat by Nikitha

[![Repo languages](https://img.shields.io/github/languages/top/nikitha7688/NexaChat?style=for-the-badge)](https://github.com/nikitha7688/NexaChat)
[![GitHub stars](https://img.shields.io/github/stars/nikitha7688/NexaChat?style=for-the-badge)](https://github.com/nikitha7688/NexaChat/stargazers)
[![License](https://img.shields.io/github/license/nikitha7688/NexaChat?style=for-the-badge)](https://github.com/nikitha7688/NexaChat/blob/main/LICENSE)

NexaChat is an AI-powered chat application built by Nikitha. It provides an intuitive chat interface with real-time-like messaging, AI responses, and an easy-to-run developer setup so others can run or deploy the app locally or on a cloud host.

Live demo: (add demo URL here if available)

---

## Features
- Conversational AI chat UI
- Support for pluggable AI providers (OpenAI / Hugging Face / others) via environment variables
- Clean, responsive frontend UI (React)
- Simple backend API for proxying requests to an AI provider
- Example deployment instructions included

---

## Tech stack
- JavaScript (~97.9%), HTML, CSS
- Frontend: React
- Backend: Node.js / Express (if included)
- Optional: WebSockets or SSE for streaming responses

---

## Quickstart (local)

1. Clone the repo
   git clone https://github.com/nikitha7688/NexaChat.git
   cd NexaChat

2. Install dependencies
   npm install

3. Create a .env file with required variables:
   - Example for OpenAI:
     OPENAI_API_KEY=your_openai_api_key
     AI_PROVIDER=openai
     AI_MODEL=gpt-4o-mini
   - Example for HuggingFace:
     HF_API_KEY=your_hf_key
     AI_PROVIDER=huggingface
     AI_MODEL=your-hf-model

4. Start dev server
   npm run dev

5. Open http://localhost:3000 (or the port shown) and chat!

---

## Environment configuration
- .env example:
  AI_PROVIDER=openai
  OPENAI_API_KEY=sk-...
  AI_MODEL=gpt-4o-mini
  PORT=3000

---

## API example
- POST /api/chat { "message": "Hello" } returns { "reply": "..." }

(If using streaming add instructions for SSE or WebSocket connection.)

---

## Deployment
- Frontend: Vercel / Netlify / GitHub Pages
- Backend: Railway / Render / Heroku / Vercel Serverless
- Set API keys as platform secrets.

---

## Screenshots / Demo
Add screenshot / gif to ./assets/ and reference it here:
![NexaChat screenshot](./assets/nexachat-demo.gif)

---

## Contributing
Contributions welcome — fork, branch, PR. Please include steps to reproduce and environment info.

---

## License
MIT © Nikitha

---

## Contact
Nikitha — nikithadharani23@gmail.com  
Portfolio: https://nikitha7688.github.io/Nikki-Portfolio/  
GitHub: https://github.com/nikitha7688
