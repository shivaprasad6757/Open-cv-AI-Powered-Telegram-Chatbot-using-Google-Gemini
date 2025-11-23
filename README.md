# 🤖 AI-Powered Telegram Chatbot
### Built with n8n • Google Gemini LLM • Telegram Bot API
This repository contains a fully automated AI-driven Telegram Chatbot system designed using n8n, Google Gemini LLM, and memory-enabled conversation handling. The bot supports both public and restricted modes, making it suitable for support systems, educational tools, and internal automation.

**🚀 Project Overview**
This chatbot system provides smart, real-time interactions using Google Gemini and can operate in two intelligent modes:

**🔹 1. Multi-User Mode:-**
Anyone can interact with the bot and receive AI-generated responses instantly.
**🔹 2. Authorized-User Mode:-**
- Access is restricted only to approved users, enabling secure and controlled usage.
- The entire workflow is automated in n8n — no manual monitoring required.

**💡 Key Features**
- ✔️ Real-time message handling using Telegram Trigger
- ✔️ AI-powered conversational responses via Google Gemini LLM
- ✔️ Memory-enabled chat context using Simple Memory
- ✔️ Authorization system for user-restricted access
- ✔️ Modular & scalable workflow design
- ✔️ Minimal-code AI automation using n8n
- ✔️ Works for support chatbots, student help systems, internal assistants, etc.

**🔧 Tech Stack**
- Component	Purpose
- n8n	Workflow automation platform
- Telegram Bot API	Receives and sends chat messages
- Google Gemini LLM	AI-generated intelligent responses
- AI Agent Node	Handles LLM-based conversation logic
- Simple Memory	Stores context between messages
  
**🧱 Architecture Overview**
**1)Telegram Trigger Node**
- Captures incoming messages from users.
- Authorization Logic (Optional)
- Checks if the user is allowed (in authorized mode).
- Memory + LLM Interaction.
- Simple Memory stores conversation history.
- Gemini LLM generates responses based on context.

**2)Telegram Send Node**
- Sends the AI-generated reply back to the user.
- Fully automated workflow
- No manual steps required.

**📸 Screenshot**
<img width="1611" height="478" alt="Screenshot 2025-11-13 173504" src="https://github.com/user-attachments/assets/49270849-d693-44e7-ba3c-bc7859ddbff1" />
