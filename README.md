# 🎙️ VoxAI — AI Voice Chatbot

**VoxAI** is a Python-based AI voice chatbot that enables users to have natural voice conversations with an AI assistant through a web-based interface.

The application combines **OpenAI GPT-5 nano** for intelligent response generation with **IBM Watson Speech-to-Text (STT)** and **IBM Watson Text-to-Speech (TTS)** to create a complete speech-to-speech conversational pipeline.

## ✨ Features

* 🎤 **Speech-to-Text** — IBM Watson STT converts the user's voice into text.
* 🤖 **AI Conversation** — OpenAI GPT-5 nano processes the user's query and generates a response.
* 🔊 **Text-to-Speech** — IBM Watson TTS converts the AI response into spoken audio.
* 💬 **Interactive Web Interface** — Chat with VoxAI through a browser-based interface.
* ⚡ **Voice-Based Interaction** — Designed for conversational interaction using voice instead of traditional text-only input.
* 🐍 **Python Backend** — Handles the application's core processing and service integrations.
* 🌐 **Web Application** — Provides an accessible interface for interacting with the voice assistant.

## 🧠 How VoxAI Works

VoxAI follows a simple speech-to-speech AI pipeline:

```text
                 🎤 User Voice
                      │
                      ▼
             IBM Watson STT
                      │
                      ▼
                📝 Text Query
                      │
                      ▼
              OpenAI GPT-5 nano
                      │
                      ▼
              🤖 AI Response
                      │
                      ▼
             IBM Watson TTS
                      │
                      ▼
                 🔊 Audio
                      │
                      ▼
                 👤 User
```

## 🛠️ Tech Stack

| Technology                    | Purpose                           |
| ----------------------------- | --------------------------------- |
| **Python**                    | Backend application logic         |
| **Flask**                     | Web application/backend framework |
| **OpenAI GPT-5 nano**         | AI response generation            |
| **IBM Watson Speech-to-Text** | Converts speech into text         |
| **IBM Watson Text-to-Speech** | Converts text into speech         |
| **HTML**                      | Web interface                     |
| **CSS**                       | User interface styling            |
| **JavaScript**                | Frontend interaction              |

## 🏗️ Project Structure

```text
VoxAI/
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── server.py
├── worker.py
├── .gitignore
└── README.md
```

Sensitive credentials and certificate files are intentionally excluded from the repository.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MuhammadHamzaAlam/VoxAI.git
cd VoxAI
```

### 2. Create a virtual environment

#### Windows

```powershell
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Credentials

VoxAI requires credentials for the external AI and speech services.

Configure the required:

* OpenAI API credentials
* IBM Watson Speech-to-Text credentials
* IBM Watson Text-to-Speech credentials

**Never commit API keys, passwords, private certificates, or other sensitive credentials to GitHub.**

### 5. Run the application

```bash
python server.py
```

Open the local URL displayed by the Flask server in your browser.

## 🔐 Security

Sensitive files are excluded from version control using `.gitignore`.

For example:

```text
certs/
.env
venv/
__pycache__/
*.pyc
```

This prevents private certificates, environment files, virtual environments, and Python cache files from being uploaded to the repository.

> **Important:** `.gitignore` prevents files from being tracked in future commits. If a secret was already committed to Git history, simply adding it to `.gitignore` is not sufficient; the secret should be revoked/rotated and the Git history cleaned if necessary.

## 🎯 What This Project Demonstrates

VoxAI brings together multiple components required to build a voice-enabled AI application:

* **Generative AI integration**
* **Speech recognition**
* **Text-to-speech synthesis**
* **Backend API integration**
* **Web application development**
* **Frontend/backend communication**
* **Python application architecture**
* **Asynchronous/background processing**
* **Git and GitHub version control**

## 🔮 Future Improvements

Potential improvements include:

* 🎙️ Real-time streaming speech
* 🧠 Conversation memory
* ⚡ Lower-latency voice responses
* 🌍 Multi-language voice support
* 🎚️ Voice activity detection
* 👤 User authentication
* ☁️ Cloud deployment
* 🐳 Docker containerization
* 📊 Conversation analytics

## 👨‍💻 Author

**Muhammad Hamza Alam**

Computer Science Student | AI/ML & Software Engineering

GitHub: [MuhammadHamzaAlam](https://github.com/MuhammadHamzaAlam)

---

⭐ **VoxAI** — Turning voice into intelligent AI conversations.
