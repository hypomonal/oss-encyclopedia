# 🦙 Ollama

![Stars](https://img.shields.io/github/stars/ollama/ollama?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

| Field | Info |
|-------|------|
| 🏷️ **Category** | 🤖 AI & Machine Learning |
| 👤 **Made by** | Ollama Team |
| ⚖️ **License** | MIT — use it however you want!! ✅ |
| 🌐 **Website** | [ollama.com](https://ollama.com) |
| 💻 **GitHub** | [ollama/ollama](https://github.com/ollama/ollama) |

---

## 📌 What it is

Ollama lets you run powerful large language models **completely locally** on your own machine — no internet, no API keys, no subscription, no data sent anywhere!! 🔒 One command and you're chatting with Llama, Mistral, Gemma, and dozens more!!

---

## 🔍 What it does

- 🚀 Download & run LLMs with a single command
- 🔒 Fully offline — your data NEVER leaves your machine
- 🤖 Supports 50+ models: Llama 3, Mistral, Gemma, Phi, Qwen & more
- 🌐 Built-in REST API so you can build apps on top of it
- 💬 Chat interface out of the box
- ⚡ GPU-accelerated on NVIDIA, AMD & Apple Silicon

---

## 🚀 How to use it

```bash
# Install (macOS/Linux)
curl -fsSL https://ollama.com/install.sh | sh

# Pull and run a model instantly!!
ollama run llama3

# Run Mistral
ollama run mistral

# Use the REST API
curl http://localhost:11434/api/generate -d '{
  "model": "llama3",
  "prompt": "Why is open source so awesome?",
  "stream": false
}'
```

---

## 💡 Who it helps

- 🧑‍💻 Developers building AI-powered apps without cloud costs
- 🔐 Privacy-focused users who don't want data leaving their machine
- 🧪 Researchers testing and comparing different LLMs
- 🏢 Companies needing on-premise AI with no vendor lock-in
- 🎓 Students learning how LLMs work

---

## ⚡ Why it's awesome

Before Ollama, running a local LLM was a painful 20-step process involving CUDA drivers, model conversion scripts, and prayer 🙏. Ollama made it ONE command. The democratization of local AI in a single tool!! It's the Docker of AI models — pull, run, done!! 🐳

---

*[← Back to AI & ML index](./README.md)*

