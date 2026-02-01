# 🤖 AI Resume Checker – Telegram Bot

An AI-powered resume evaluation system built using **Make.com** that allows users to submit resumes via **Telegram** and receive structured feedback via **email**.

---

## 📌 Problem Statement
Manually reviewing resumes is time-consuming and inconsistent. This project automates resume evaluation using AI, making the process faster and more accessible through a chat-based interface.

---

## ⚙️ How It Works
1. User interacts with a Telegram bot
2. Bot requests a Google Docs resume link
3. Resume content is extracted automatically
4. An AI agent evaluates the resume
5. Feedback is sent to the user via email

---

## 📂 Workflows

### 1. Telegram Watch Updates
- Listens for incoming Telegram messages
- Triggers the resume evaluation flow

### 2. Get Resume Content
- Extracts resume text from Google Docs
- Uses regex to parse document ID

### 3. AI Resume Evaluation
- AI agent analyzes resume structure, clarity, and content
- Generates actionable feedback

### 4. Send Resume Report (Gmail)
- Emails the resume evaluation to the user

---

## 🛠 Tech Stack
- Make.com (Integromat)
- AI Agents
- Telegram Bot API
- Google Docs API
- Gmail API

---

## 🔐 Security
All credentials, tokens, and connection IDs have been removed.  
Users must configure their own connections after importing the workflows.

---

## 🚀 Setup Instructions
1. Import the `.make.json` files into Make.com
2. Configure Telegram, Gmail, and Google Docs connections
3. Activate the scenario

---

## 📈 Future Enhancements
- ATS score calculation
- Job description matching
- PDF resume support
- Resume improvement suggestions
