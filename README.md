# 🎙️ Lecture Note Summarizer – Whisper + LLM 📚

An open-source Flask application that transcribes lecture audio into text using OpenAI's Whisper, and generates detailed lecture notes and summaries using an LLM via OpenRouter API.

---

## 🚀 Features

- 🎧 **Audio Upload**: Upload `.mp3`, `.wav`, or `.m4a` files
- 🔊 **Speech-to-Text**: Transcribes audio using Whisper
- 🧠 **Smart Note Generation**: Generates detailed notes using OpenRouter LLM
- 📋 **Summary**: Extracts concise summaries of the lectures
- 💡 Ideal for students, teachers, and researchers

---

## 🛠️ Tech Stack

| Layer      | Tool/Library              |
|------------|---------------------------|
| Transcription | `whisper` (OpenAI ASR)       |
| Summarization | `OpenRouter API` + LLM         |
| Backend    | `Flask`                   |
| Frontend   | `React` (optional for chatbot UI) |
| File Handling | `Werkzeug`, `pydub`          |

---

## 📁 Folder Structure
whisper/
├── app.py # Main Flask app to run the server and routes
├── whisper_utils.py # Handles audio transcription using Whisper
├── summarizer.py # Uses OpenRouter API to generate summaries
├── notes_generator.py # Converts transcription to full lecture notes
├── qa.py # (Optional) Generates Q&A from transcript
├── test_notes.py # Testing logic for note generation
├── README.md # Project documentation
├── static/ # Static files like CSS or JS (if needed)
├── templates/ # HTML templates (e.g., index.html)
└── uploads/ # Directory where uploaded audio files are saved



