# 💄 L'Oréal Beauty Assistant Chatbot

An AI-powered beauty consultant chatbot themed around L'Oréal Paris. Ask it about skincare routines, makeup recommendations, hair care, and L'Oréal product guidance, all through a sleek, branded chat interface.

**[▶ Launch the App](https://k-evr.github.io/LOreal-Chatbot/)**

---

> ⚠️ **Disclaimer:** The OpenAI API key bundled with this project is no longer active. The chatbot will not return AI responses in its current deployed state. To run it with full functionality, you will need to supply your own OpenAI API key (see [Running Locally](#-running-locally) below).

---

## ✨ Features

- **AI Beauty Consultant** — Conversational assistant that answers questions about skincare routines, makeup, hair color, and L'Oréal products
- **Popular Topic Shortcuts** — One-click prompts for common queries: Dry Skin Routine, Foundation Match, Anti-Aging, Hair Color, and Glow Serums
- **Branded UI** — L'Oréal Paris styling with the iconic "Because You're Worth It" tagline
- **Chat Interface** — Clean, responsive message thread with user and assistant bubbles
- **Powered by OpenAI** — Uses the OpenAI Chat Completions API with an L'Oréal-focused system prompt

---

## 💬 Example Questions

- *"What's the best routine for dry skin?"*
- *"Can you recommend a foundation for medium skin tone?"*
- *"What L'Oréal serums help with anti-aging?"*
- *"How do I maintain color-treated hair?"*
- *"What's a good glow serum for beginners?"*

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — no frameworks or build tools
- **OpenAI Chat Completions API** (`gpt-3.5-turbo` or similar)
- **GitHub Pages** — static hosting

---

## 💻 Running Locally

```bash
git clone https://github.com/k-evr/LOreal-Chatbot.git
cd LOreal-Chatbot
```

Then open `index.html` in your browser.

To restore AI functionality, add your own OpenAI API key:

1. Get a key at [platform.openai.com](https://platform.openai.com/api-keys)
2. Open `index.html` (or the relevant JS file) and locate the API key variable
3. Replace the placeholder value with your own key

> **Security note:** Never commit a real API key to a public repository. For a production deployment, proxy API calls through a backend server so the key is never exposed in client-side code.

---

## 📄 License

This project is a fan-made demo and is not affiliated with, endorsed by, or associated with L'Oréal Paris or its parent company. L'Oréal and "Because You're Worth It" are trademarks of L'Oréal S.A.
