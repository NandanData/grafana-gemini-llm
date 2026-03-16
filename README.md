# Grafana Gemini LLM Stack

![Status](https://img.shields.io/badge/Status-Active-success)
![Version](https://img.shields.io/badge/Grafana-v12.4-orange)

This project integrates **Google Gemini LLM** with **Grafana V12.4** using **LiteLLM Proxy** on Ubuntu.

---

## 🛠️ Stack Components

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Observability** | Grafana V12.4 | Visualization & AI Plugin Host |
| **AI Gateway** | LiteLLM Proxy | OpenAI-compatible API bridge |
| **LLM** | Google Gemini | Core Language Model |
| **Runtime** | Docker Compose | Container orchestration |

---

## 🚀 Quick Start

1. **Clone the Repo**
2. **Configure Environment:** Create a `.env` file with your `GEMINI_API_KEY`.
3. **Deploy:** ```bash
   docker-compose up -d
