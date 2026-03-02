
# 🤖 Clone Myself – Personal AI Assistant

This project builds a **personal AI assistant** that answers questions as if it were you, using your LinkedIn profile and a short personal summary.

## 🚀 What It Does

* Reads your `linkedin.pdf`
* Loads additional context from `summary.txt`
* Creates a personalized system prompt
* Uses OpenAI to generate responses in your voice
* Launches a simple web UI using **Gradio**

The assistant can answer questions about:

* Career & experience
* Skills & projects
* Background & achievements
* Professional interests

## 📂 Project Structure

```
linkedin.pdf      # Your LinkedIn export (replace with yours)
summary.txt       # Short personal summary
clone-myself.ipynb
```

## 🛠 Tech Stack

* OpenAI API
* PyPDF (PDF parsing)
* Gradio (UI)
* Python
* dotenv (API key management)

## ⚙️ Setup

1. Add your OpenAI API key to `.env`
2. Replace `linkedin.pdf` with your own
3. Update `summary.txt`
4. Run the notebook
5. Launch the Gradio interface

## 🎯 Goal

Create a lightweight **AI-powered personal website assistant** that represents you professionally and consistently.


