# 🦜 LangChain

![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

| Field | Info |
|-------|------|
| 🏷️ **Category** | 🤖 AI & Machine Learning |
| 👤 **Made by** | LangChain AI |
| ⚖️ **License** | MIT — totally free!! ✅ |
| 🌐 **Website** | [langchain.com](https://langchain.com) |
| 💻 **GitHub** | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) |

---

## 📌 What it is

LangChain is THE standard framework for building applications powered by large language models 🧠. Think of it as the glue that connects LLMs to your data, tools, APIs, and memory — turning a raw AI model into a smart, useful application!!

---

## 🔍 What it does

- 🔗 Chain together LLM calls, tools, and data sources
- 🗂️ Connect LLMs to your own documents (PDFs, databases, websites)
- 🧠 Add memory so your AI actually remembers the conversation
- 🛠️ Build AI agents that can use tools like search, calculators, APIs
- 🌐 Works with OpenAI, Anthropic, Ollama, Hugging Face & more
- 📦 Hundreds of integrations out of the box

---

## 🚀 How to use it

```bash
pip install langchain langchain-openai
```
```python
from langchain_openai import ChatOpenAI
from langchain_core.messages import HumanMessage

# Create a model
model = ChatOpenAI(model="gpt-4o")

# Chat with it!
response = model.invoke([HumanMessage(content="What is open source?")])
print(response.content)

# Build a RAG pipeline — chat with YOUR documents!!
from langchain_community.document_loaders import PyPDFLoader
from langchain_openai import OpenAIEmbeddings

loader = PyPDFLoader("my_document.pdf")
docs = loader.load()
```

---

## 💡 Who it helps

- 🧑‍💻 Developers building chatbots, assistants, or AI-powered features
- 📚 Anyone who wants to chat with their own documents
- 🏢 Enterprises building internal AI tools
- 🤖 Builders creating autonomous AI agents
- 🔬 Researchers experimenting with LLM applications

---

## ⚡ Why it's awesome

LangChain turned "I have an LLM" into "I have an entire AI application" 🎉. The ecosystem is MASSIVE — hundreds of integrations, a huge community, and it works with literally any LLM provider. It's the Rails of AI development — opinionated, powerful, and incredibly productive!! 🚂

---

*[← Back to AI & ML index](./README.md)*

