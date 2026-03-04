# Google Gemini Chatbot

## Overview
A simple interactive chatbot using **Google Gemini** in a Jupyter Notebook. It remembers conversation history and gives context-aware responses.

## Features
- Chat interactively in a notebook
- Contextual replies
- Exit anytime with `exit` or `quit`

## Installation & Setup

Follow these steps:

**Clone the repository, create virtual environment, install dependencies, and add your API key**
# 1. Clone the repo
```bash
git clone https://github.com/yourusername/google-gemini-chatbot.git
```
# 2. Go into the project folder
```bash
cd google-gemini-chatbot
```
# 3. Create a virtual environment
```bash
python -m venv venv
```
# 4. Activate the virtual environment
```bash
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
```
# 5. Install dependencies
```bash
pip install -r requirements.txt
```
# 6. Add your Google Gemini API key
```bash
echo "GEMINI_API_KEY=your_google_gemini_api_key" > .env
```
# 7. Launch Jupyter Notebook
```bash
jupyter notebook
```
