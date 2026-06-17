# 🦙 llama.cpp

![Stars](https://img.shields.io/github/stars/ggerganov/llama.cpp?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

| Field | Info |
|-------|------|
| 🏷️ **Category** | 🤖 AI & Machine Learning |
| 👤 **Made by** | Georgi Gerganov |
| ⚖️ **License** | MIT — do whatever you want!! ✅ |
| 💻 **GitHub** | [ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) |

---

## 📌 What it is

llama.cpp is the legendary project that made running LLMs on regular consumer hardware actually possible!! 🎉 Written in pure C/C++ with zero dependencies, it pioneered the GGUF model format that is now the standard for local LLM inference worldwide!!

---

## 🔍 What it does

- 🖥️ Run LLMs on CPU — no GPU required!!
- ⚡ Blazing fast inference with AVX, NEON & Metal acceleration
- 📦 Invented GGUF — the universal format for quantized models
- 🔢 Multiple quantization levels (4-bit, 5-bit, 8-bit) to fit any hardware
- 🍎 Native Apple Silicon support — screaming fast on M1/M2/M3!!
- 🛠️ Powers Ollama, LM Studio, and dozens of other tools under the hood

---

## 🚀 How to use it

```bash
# Build from source
git clone https://github.com/ggerganov/llama.cpp
cd llama.cpp
make

# Download a GGUF model and run it!!
./llama-cli -m ./models/llama-3.gguf -p "Why is open source amazing?" -n 512

# Run as an OpenAI-compatible server!!
./llama-server -m ./models/llama-3.gguf --port 8080
```

---

## 💡 Who it helps

- 💻 Developers who want zero-dependency LLM inference
- 🔬 Researchers experimenting with quantization and efficiency
- 🏢 Engineers building embedded or edge AI applications
- 🎮 Game developers adding AI NPCs with no cloud costs
- 🌍 Anyone in the world with just a CPU and no GPU

---

## ⚡ Why it's awesome

This single repo democratized AI for the ENTIRE world!! 🌍 Before llama.cpp, running an LLM required an expensive GPU and a PhD. Now a grandma with a 5-year-old laptop can run a powerful language model offline!! One developer, one repo, changed everything. One of the most impactful open source projects EVER!! 🏆🏆🏆

---

*[← Back to AI & ML index](./README.md)*

