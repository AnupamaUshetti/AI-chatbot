# 🧠 AI Assistant CLI with LangChain & OpenAI

This is a simple command-line AI assistant built using **LangChain**, **OpenAI**, and **LangGraph**. The assistant streams responses interactively and is structured to support additional tools for enhanced functionality.

---

## 🚀 Features

- ✅ Interactive CLI-based AI assistant  
- 🔁 Streaming responses using LangChain's ReAct agent  
- 🧠 OpenAI's Chat model integration (`ChatOpenAI`)  
- 🔧 Easily extendable with tools via LangChain  
- 🌱 Environment-based API key loading with `python-dotenv`

---

## 📦 Requirements

Install the required Python packages:

```bash
pip install

langchain
langchain-openai
langgraph
python-dotenv
```

## 🔐 Setup
Create a .env file in the project root with your OpenAI API key:


## OPENAI_API_KEY=your_openai_api_key
⚠️ Make sure your .env file is added to .gitignore to keep your API key secure.

## 🧑‍💻 How to Use
Run the main script using:

```bash
python main.py
```
You’ll see:
```bash
Welcome! I'm your AI assistant. Type 'quit' to exit.
How can I assist you today?
```
