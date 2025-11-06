# MeChat-Bot

WhatsApp multi-device bot built with [Baileys](https://github.com/WhiskeySockets/Baileys).

## ✨ Features
- Auto-reply (keyword-based)
- AI Chat (OpenRouter / ChatGPT)
- “Lugu Mode” keyword DB
- Dashboard Web (PHP Native)
- Voice transcription (Whisper API)
- Auto-post blog articles
- Dynamic engine loader from remote URL

## ⚙️ Installation
```bash
npm install
npm run start
🧩 Configuration

Edit file .env:
OPENROUTER_API_KEY=your_key
WHISPER_API_KEY=your_key

📦 Deployment

Use pm2 or systemd for auto restart on VPS.
pm2 start index.js --name mechat-bot
