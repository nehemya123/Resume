# Local AI Chatbot

A private AI chatbot built with Python, Gradio, and Ollama.

This project runs a local large language model (LLM) directly on your computer without using external APIs. The chatbot supports real-time conversations, adjustable tone settings, and local processing for better privacy.

---

# 🚀 Features

* Local/offline AI chatbot
* Real-time chat interface
* Adjustable tone settings
* Conversation memory
* Runs with Ollama models
* No cloud API required
* Simple Gradio web interface

---

# 🛠️ Technologies Used

* Python
* Gradio
* Ollama
* Requests Library
* Local LLMs (Llama 3 / Phi3)

---

# 📁 Project Structure

```bash
AI-chatbot/
│── app.py
│── chatbot.py
│── config.py
│── requirements.txt
│── README.md
```

---

# ⚙️ Installation

## 1. Clone the repository

```bash
git clone <your-repo-link>
cd AI-chatbot
```

---

## 2. Install Python dependencies

```bash
pip3 install gradio requests
```

---

## 3. Install Ollama

Download Ollama from:

[https://ollama.com](https://ollama.com)

---

## 4. Download a model

Example:

```bash
ollama run phi3
```

You can also use:

```bash
ollama run llama3
```

---

# ▶️ Running the Project

## Start Ollama

Open a terminal:

```bash
ollama run phi3
```

---

## Run the chatbot app

Open another terminal:

```bash
python3 app.py
```

Then open:

```bash
http://127.0.0.1:7860
```

in your browser.

---

# 🧠 How It Works

1. User sends a message through the Gradio interface.
2. The message is stored in conversation history.
3. Python sends the request to Ollama.
4. Ollama processes the message using a local AI model.
5. The chatbot response is displayed in the UI.

---

# 🔥 Future Improvements

* Voice input/output
* Save chat history
* Dark mode UI
* Multiple model support
* Docker deployment
* User authentication
* Better memory system

---

# 📌 Resume Description

### Local AI Chatbot

Built a private AI chatbot using Python, Gradio, and locally hosted large language models through Ollama. Implemented conversation memory, configurable chatbot behavior, and a real-time web interface while focusing on privacy through local processing.

---

# 📷 Demo

Example prompts:

* "Tell me a joke"
* "Explain Python"
* "Write a short story"
* "Help me study for algorithms"

---

# 👨‍💻 Author

Nehemya Assefa
Computer Science Student at the University of Minneso
