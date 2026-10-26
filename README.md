# Gemini AI Chatbot 🤖

A simple, interactive, command-line AI chatbot built with Python and Google's Gemini API. The chatbot accepts questions from users, generates AI-powered responses, and continues the conversation until the user types `exit`.

## ✨ Features

- 🤖 AI-powered responses using Google's Gemini API
- 💬 Interactive command-line chat interface
- 🔄 Continuous conversation loop
- ⚡ Simple and lightweight Python implementation
- 🔐 API key authentication
- 🚪 Exit the chatbot anytime by typing `exit`

## 🛠️ Technologies Used

- **Python** — Programming language
- **Google Gen AI SDK** — Connects the application to Google's generative AI models
- **Gemini API** — Generates AI responses

## 📋 Prerequisites

Before running the project, make sure you have:

- Python 3.9 or a compatible version supported by the Google Gen AI SDK
- A Google Gemini API key
- An internet connection

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd YOUR_PROJECT_FOLDER
```

Replace the repository URL and folder name with your actual GitHub repository details.

### 2. Install the required package

```bash
pip install google-genai
```

### 3. Configure your API key

Get an API key from [Google AI Studio](https://aistudio.google.com/apikey).

For better security, store your API key in an environment variable instead of writing it directly in your Python code.

**Windows PowerShell:**

```powershell
$env:GEMINI_API_KEY="your_api_key_here"
```

### 4. Run the chatbot

Save your Python script as `chatbot.py`, then execute:

```bash
python chatbot.py
```

## 💻 Example Usage

```text
You: Hello!
Gemini: Hello! How can I help you today?

You: What is Python?
Gemini: Python is a high-level, general-purpose programming language...

You: exit
```

## 📂 Project Structure

```text
Gemini-AI-Chatbot/
│
├── chatbot.py
├── README.md
└── .gitignore
```

## 🔒 Security

- Never upload your Gemini API key to GitHub.
- Use environment variables to manage sensitive credentials.
- Add `.env` and other secret files to `.gitignore` if you use them.
- If an API key has already been pushed publicly, revoke it and generate a new one.

## 🔮 Future Improvements

- Add conversation history and contextual memory.
- Build a graphical user interface using Streamlit or Tkinter.
- Add exception handling for API errors and network issues.
- Support configurable Gemini models.
- Add chat history export functionality.

## 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Python programming and loops
- User input and output handling
- API integration
- Working with Google's Gen AI SDK
- Building a basic generative AI application

## 👨‍💻 Author

**Rohan Gadade**

GitHub: [rohan2-4](https://github.com/rohan2-4)

---

⭐ If you find this project useful, consider giving the repository a star!

