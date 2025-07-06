# Jarvis - Python Voice Assistant 🧠🎤

Jarvis is a Python-based voice assistant inspired by Iron Man's AI. It listens for a wake word ("Jarvis") and performs a variety of tasks like opening websites, playing music, reading news headlines, and answering general queries using OpenAI's GPT API.

---

## 🔧 Features

- 🔊 **Wake Word Detection**: Activate by saying **"Jarvis"**
- 🌐 **Open Websites**: Google, YouTube, Facebook, LinkedIn
- 🎵 **Play Songs**: Uses links from a custom music library
- 🗞️ **News Headlines**: Reads top news from NewsAPI
- 🤖 **AI Responses**: Uses OpenAI's GPT model to answer any question
- 🗣️ **Text-to-Speech**: Converts responses to speech using `gTTS` and plays via `pygame`

---

## 🚀 Installation

1. **Install Required Packages**

```bash
pip install speechrecognition pyttsx3 pygame gTTS requests openai

