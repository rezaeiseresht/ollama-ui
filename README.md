# 🧠 Ollama UI – Simple Local Chat Interface

A lightweight, local-first web UI to interact with Large Language Models using [Ollama](https://ollama.com).  
Perfect for testing LLMs like `llama3`, `mistral`, or `gemma` on your own machine — no cloud, no API cost.


[logo](assets/logo.png) 

## 🚀 Features

- Minimal web UI (HTML + JavaScript)
- Sends prompts to local Ollama API (`localhost:11434`)
- Displays responses in a chat-like interface
- Easily extendable (history, themes, model selection, etc.)

---

## 📸 Preview

![screenshot](assets/screenshot.png) <!-- Add later if you want -->

---

## 🔧 Requirements

- [Ollama](https://ollama.com/download) installed and running locally
- A supported model (e.g., `llama3`) already pulled via:

```bash
ollama run llama3
