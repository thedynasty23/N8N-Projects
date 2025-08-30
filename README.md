# ⚡ N8N Projects – AI Powered Workflows  

![n8n](https://img.shields.io/badge/Workflow-n8n-orange?logo=n8n)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-red?logo=google)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--powered-black?logo=openai)
![Gmail](https://img.shields.io/badge/Integration-Gmail-blue?logo=gmail)
![Weather](https://img.shields.io/badge/Integration-OpenWeatherMap-lightblue?logo=openweathermap)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

This repository contains **automation workflows** built with **[n8n](https://n8n.io/)** 🤖.  
It demonstrates how AI models like **Google Gemini** and **OpenAI** can be integrated with real-world tools such as **Gmail** and **OpenWeatherMap** 🌍.  

---

## 📸 Demo  
Screenshots of the workflows are available in the [`Images/`](./Images) folder:  
- Gmail Assistant (Gemini Workflow) ✉️  
- Weather Assistant (Vapi Workflow) ⛅  

---

## ✨ Workflows  

### 1️⃣ Gemini Workflow – Gmail Assistant ✉️  
**Use Case**: An AI-powered Gmail assistant that can **send and fetch emails**.  

**Components**:  
- 📩 **Trigger** → Chat message received  
- 🤖 **AI Agent** → Handles instructions  
- 🔮 **Google Gemini Chat Model** → Powers natural language understanding  
- 🧠 **Simple Memory** → Maintains context  
- 📤 **Gmail - Send Mails** → Send new emails  
- 📥 **Gmail - Get Mails** → Fetch recent emails  

---

### 2️⃣ Vapi Workflow – Weather Assistant ⛅  
**Use Case**: An AI assistant that can **fetch real-time weather info** and respond via webhook.  

**Components**:  
- 🌐 **Webhook** → Entry point for API requests  
- 🤖 **AI Agent** → Parses user queries  
- 🧠 **OpenAI Chat Model** → Language model for reasoning  
- 🌦 **OpenWeatherMap** → Fetches live weather data  
- 📡 **Respond to Webhook** → Sends weather results back as JSON  

---

## 🚀 Getting Started  

### 1️⃣ Requirements  
- [n8n](https://n8n.io/) installed (self-hosted or cloud)  
- API Keys:  
  - Google Gemini API 🔑  
  - Gmail OAuth2 credentials  
  - OpenAI API Key  
  - OpenWeatherMap API Key  

### 2️⃣ Import Workflow  
1. Open n8n  
2. Import either `Gemini_Workflow.json` or `Vapi_Workflow.json`  
3. Configure credentials for Gmail, OpenAI, Gemini, and OpenWeatherMap  

### 3️⃣ Run the Workflow  
- **Gemini Workflow** → Start a chat and manage Gmail messages ✉️  
- **Vapi Workflow** → Trigger via webhook to fetch weather ⛅  

---

## 📂 Repository Structure  

```
.
├── Images/                         # Workflow screenshots 📸
│   ├── gmail usage workflow using gemini.jpg
│   └── weatherapp workflow using vapi.jpg
├── Gemini_Workflow.json            # Gmail assistant workflow ✉️
├── Vapi_Workflow.json              # Weather assistant workflow ⛅
└── README.md                       # Project documentation 📘
```

---

## 🧩 Future Enhancements  
- 🔊 Voice-enabled assistants  
- 📊 Analytics for mail usage & weather queries  
- 🌐 Multi-tool orchestration (combine email + weather + calendar)  

---

## 🤝 Contributing  
Contributions are welcome! Fork the repo and suggest new workflows 💡  

---

## 📜 License  
This project is licensed under the MIT License.  

---

🚀 Built with ❤️ using **n8n, Google Gemini, OpenAI, Gmail, and OpenWeatherMap**
