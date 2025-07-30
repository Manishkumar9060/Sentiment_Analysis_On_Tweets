# Sentiment_Analysis_On_Tweets
# 🐦 Tweet Sentiment Analysis Web App

This project is a **Sentiment Analysis On Tweets** built using **Flask** and **Hugging Face Transformers**. It analyzes the **sentiment of tweets** (or any short text) and returns whether the sentiment is **Positive**, **Negative**, or **Neutral**.

## 🔧 Tech Stack
- 🐍 Python (Flask Framework)
- 🤗 Transformers by Hugging Face
- 🌐 HTML/CSS + JavaScript (Frontend)
- 🔁 Flask-CORS for cross-origin requests

## 🚀 Features
- Analyze real-time tweets or user-input sentences
- Shows sentiment with confidence score
- Lightweight and responsive web UI
- Easy to deploy locally or on cloud (e.g., Heroku)

## 💡 How It Works
1. User inputs a tweet or sentence
2. Backend uses Hugging Face `pipeline("sentiment-analysis")` to analyze it
3. Response is sent back and displayed with sentiment and confidence

## 🧪 Sample Output
> Input: _"I love You!"_  
> Output: `Positive (1)`
> <img width="1858" height="956" alt="image" src="https://github.com/user-attachments/assets/9bc3a5ef-9154-4637-9531-9b98dddf40bd" />


## 📁 Folder Structure

## ⚙️ Installation
```bash
git clone https://github.com/your-username/tweet-sentiment-analysis.git
cd tweet-sentiment-analysis
pip install -r requirements.txt
python app.py

