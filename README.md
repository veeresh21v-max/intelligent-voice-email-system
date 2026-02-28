# 🎙️ Intelligent Voice Email System

An AI-powered voice assistant that composes and sends emails using your voice — no typing needed!

## 🚀 Demo
> Record your voice → NLP analyzes it → Email sent automatically!

## ✨ Features
- 🎤 Voice to text email composition using Google Speech API
- 🧠 Sentiment analysis using TextBlob NLP
- 📌 Auto subject line generation using noun phrase extraction
- 🔑 Keyword extraction using NLTK
- 🗄️ Email history logged in SQLite database
- 📊 Analytics dashboard with Matplotlib charts

## 🛠️ Tech Stack
| Technology | Purpose |
|---|---|
| Python | Core language |
| SpeechRecognition | Voice to text |
| TextBlob + NLTK | NLP & Sentiment Analysis |
| SQLite | Email history database |
| Matplotlib + Pandas | Analytics & visualization |
| yagmail | Gmail SMTP email sending |
| Google Colab | Cloud execution environment |

## ⚙️ How to Run
1. Open notebook in **Google Colab**
2. Run **Cell 1** to install all dependencies
3. Run cells top to bottom
4. Allow **microphone access** when browser prompts
5. Use **Gmail App Password** when sending emails

## 📊 What the Analytics Dashboard Shows
- Sentiment distribution of all emails sent
- Email status breakdown (sent/cancelled/failed)
- Word count distribution per email

## 👨‍💻 Author
**Veeresh** | [GitHub](https://github.com/veeresh21v-max)
