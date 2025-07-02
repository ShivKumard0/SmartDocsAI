# 🦜 SmartDocsAI — Your AI Assistant for Documents

[![OpenAI Powered](https://img.shields.io/badge/OpenAI-Powered-blueviolet?logo=openai)](https://platform.openai.com)
[![Dockerized](https://img.shields.io/badge/Dockerized-Yes-blue?logo=docker)](https://www.docker.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Built by Shiv Kumar](https://img.shields.io/badge/Built%20by-ShivKumar-blue)](https://github.com/ShivKumard0)

SmartDocsAI is an intelligent document chatbot that allows you to **converse with your documents** in plain English. Whether it's a research paper, invoice, policy, or product manual, SmartDocsAI can help you **summarize**, **search**, and **extract** information with ease.

Built for developers, researchers, and enterprise teams, SmartDocsAI runs privately on your system and supports both **OpenAI** and **local LLMs**. It offers full-stack control — from ingesting diverse file types to integrating actions via APIs.

> 🚀 Created, developed, and maintained by [Shiv Kumar](https://github.com/ShivKumard0)

---

## 🌟 Key Features

🗂️ **Multi-Format Support**  
Read and process documents in PDF, DOCX, CSV, XLSX, EPUB, Markdown (MD, MDX), HTML, reStructuredText (RST), JSON, PPTX — even image-based formats.

🌐 **Smart Data Ingestion**  
Ingest content from URLs, sitemaps, Reddit threads, GitHub repositories, and even through custom web crawlers.

✅ **Trustworthy & Cited Responses**  
Get accurate, context-aware answers — with inline source citations and clean, user-friendly traceability.

🔑 **Integrated API Key Management**  
Generate and manage API keys directly in-app. Tie them to your documents, models, and chatbots — making integration seamless and secure.

🔗 **LLM Action Toolkit**  
Connect SmartDocsAI to APIs, external services, or your own internal tools — and empower LLMs to take action, not just answer.

🧩 **Built-In Integrations**  
Use ready-to-go components: React/HTML chat widgets, intelligent search, Telegram/Discord bots, and much more.

🔌 **Flexible Model Support**  
Works with leading cloud LLMs (OpenAI, Claude, Gemini) as well as local engines like Ollama, llama.cpp, and gguf-compatible models.

🏢 **Secure & Scalable Architecture**  
Run it on your own machine, on-prem, or scale it with Kubernetes in production. Designed for reliability and enterprise use.

---

## 🛠 Tech Stack

| Layer       | Technology                        |
|-------------|------------------------------------|
| UI          | React, TypeScript, Tailwind CSS    |
| Backend     | FastAPI, LangChain                 |
| LLM Support | OpenAI / Local (HuggingFace, gguf) |
| Infra       | Docker, Docker Compose, K8s ready  |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ShivKumard0/SmartDocsAI.git
cd SmartDocsAI
```

### 2. Add API Key (optional if using local model)

In the `.env` file inside `backend/` or `frontend/`, add:

```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

### 3. Launch the App

```bash
cd deployment
docker compose -f docker-compose.yaml up --build
```

Then open:
```
http://localhost:5173
```

### 4. Use It!
Upload documents and ask questions like:
- “Summarize this”
- “What are the key decisions?”
- “Extract bullet points”

---

## 🧪 Use Cases

- 📚 **Students & Academics**
- 💼 **Legal & Business**
- 🧠 **LLM Builders**
- 🏢 **Enterprises**

---

## 📂 Project Structure

```
SmartDocsAI/
├── backend/         # API and LLM logic
├── frontend/        # React + Vite UI
├── deployment/      # Docker setup and configurations
├── extensions/      # Plugin integrations and tooling
└── README.md
```

---

## 🌐 Connect with Me

- 💻 GitHub: [ShivKumard0](https://github.com/ShivKumard0)
- 🐦 X (Twitter): [@shivkumard](https://x.com/shivkumard?t=R7fkI_N_ouuezXU6d972BQ&s=09)
- 💬 Discord: [768303590237274112](https://discord.com/users/768303590237274112)

---

## 📄 License

MIT License © 2025 [Shiv Kumar](https://github.com/ShivKumard0)

---

## 🚧 Roadmap

- [ ] Add multi-user authentication
- [ ] Document auto-tagging
- [ ] Whisper integration for audio
- [ ] Deploy to Netlify/Vercel
- [ ] Plugin marketplace

---

## ⭐️ Final Thought

> “Documents don’t need to be static. SmartDocsAI turns them into dynamic, intelligent, and interactive assistants.”

Give it a ⭐️ if you like the project — and feel free to fork, remix, and improve it!