# Zephyr Chatbot (Streaming LLM UI)

This is a lightweight chatbot interface built with **Gradio** that connects to the **Zephyr 7B Beta** model via Hugging Face's inference API. It supports real-time token streaming and customizable generation settings.

## 🚀 Features

- Live token streaming for smooth, responsive conversations
- Adjustable model behavior with:
  - System prompts
  - Temperature
  - Top-p (nucleus sampling)
  - Max token limit
- Clean chat UI using `gr.ChatInterface`

## 🛠️ Tech Stack
- Python
- [Gradio](https://www.gradio.app/)
- Hugging Face Inference API (`HuggingFaceH4/zephyr-7b-beta`)
- dotenv for secure token loading

## 📦 Setup

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/zephyr-chatbot.git
   cd zephyr-chatbot
