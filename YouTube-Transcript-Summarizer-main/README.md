# YouTube Transcript Summarizer

**YouTube Transcript Summarizer** is a Chrome Extension that allows users to generate a **concise summary of YouTube video transcripts** with a **single click**.  
The project leverages **Natural Language Processing (NLP)** techniques such as **Latent Semantic Analysis (LSA)** and **state-of-the-art Hugging Face Transformer models** to produce meaningful summaries.

A **Flask-based REST API backend** is used to handle transcript processing and summarization, enabling seamless communication between the Chrome extension and the server.

---

## 📌 Project Workflow
![Project Stages](/extention/images/stages.png?raw=true)

---

## 🚀 Features

- Automatically summarizes YouTube video transcripts using advanced NLP techniques.
- Uses **Latent Semantic Analysis (LSA)** for extractive summarization of very long transcripts.
- Leverages **Transformer-based models** for abstractive summarization of shorter transcripts.
- Allows users to control the **maximum length** of the summary through dynamic truncation.
- Supports **multiple languages** depending on the availability of subtitles.
- Implements **asynchronous XMLHttpRequest (AJAX)** to ensure non-blocking communication with the Flask backend.
- Clean and minimal Chrome Extension UI for ease of use.

---

## 📸 Output Preview
![Output Screenshot](/extension/images/output.png?raw=true)

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/YouTube-Transcript-Summarizer.git
cd YouTube-Transcript-Summarizer
pip install -r Requirements.txt
python TranscriptApp.py
http://127.0.0.1:5000/

