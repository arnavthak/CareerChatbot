# CareerChatbot

This is a lightweight Gradio-based chatbot project that allows you to interact with an AI agent acting on behalf of **Arnav Thakrar**. The agent answers questions about Arnav’s career, background, and skills using context pulled from his LinkedIn PDF and a personal summary. It also logs user interest and unknown questions via Pushover notifications.

> ⚠️ **If you are not Arnav Thakrar and want to repurpose this project, please modify the `me/` folder contents and change the `name` variable accordingly.**

---

## 🚀 Features

- **Conversational Web Interface:** Built with [Gradio](https://www.gradio.app/).
- **Contextual AI Agent:** AI uses a summary and PDF resume to respond accurately.
- **Pushover Integration:** Logs email leads and unknown questions to your device.
- **OpenAI Tool Calls:** Uses OpenAI's function calling to dynamically respond or log metadata.

---

## 🔐 .env Configuration

Before running, create a `.env` file with the following:

```env
OPENAI_API_KEY=your_openai_key_here
PUSHOVER_USER=your_pushover_user_key
PUSHOVER_TOKEN=your_pushover_app_token