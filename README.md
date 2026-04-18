# 🎥 YouTube Video Analyzer Agent

A lightweight AI agent that analyzes YouTube videos and extracts useful insights such as summaries and answers to user queries using LLMs.

---

## 🚀 Features

* Extract video transcripts
* Generate concise summaries
* Ask questions about video content
* Simple and fast analysis pipeline
* Works with any public YouTube URL

---

## 🏗️ Tech Stack

* Python 3.x
* Agno (Agent framework)
* Groq LLM (for fast inference)
* YouTube transcript extraction

---

## 📂 Project Structure

```
youtube-analyzer/
│
├── ui.py                  # User interface
├── youtube_analyzer.py    # Core agent logic
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/Subhash-Prajapati02/Youtube_Video_Analyzer_Agent.git
cd Youtube_Video_Analyzer_Agent
```

### 2. Create virtual environment

```
python -m venv myenv
```

### 3. Activate environment

**Windows**

```
myenv\Scripts\activate
```

**macOS/Linux**

```
source myenv/bin/activate
```

### 4. Install dependencies

```
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the application:

```
python ui.py
```

---

## 💡 Example Workflow

1. Enter a YouTube video URL
2. Agent extracts transcript
3. Generates summary
4. Answer questions based on the video

---

## 🧠 How It Works

* Fetch transcript from YouTube
* Pass text to Groq LLM via Agno agent
* Generate responses (summary / Q&A)

---

## 🛠️ Future Improvements

* Multi-language support
* Better UI (Streamlit/Web app)
* Video chapter detection
* Save analysis results

---
