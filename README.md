# TweetShield 🛡️  
**Proactive Offensive Content Filter for Twitter**

TweetShield is a real-time tweet moderation tool that detects hate speech and offensive language **before** a tweet is posted. Unlike traditional moderation systems that act *after* user reports, TweetShield takes a **proactive approach** to prevent harmful content from being published in the first place.

---

## 🚀 Features
- ⚠️ **Real-time Tweet Scanning**
- 🧠 **Deep Learning-Based Classification** (Keras LSTM model)
- ✅ **Severity-Based Action**
  - **Block** for extreme cases
  - **Flag** for medium-level violations
- 🐦 Integrated with **Twitter API**
- 🔒 Designed to promote safer online spaces

---

## 🛠️ Tech Stack
- **Python**
- **Keras / TensorFlow**
- **Twitter API (Tweepy)**
- **NLP Toolkit** – Tokenization, stopword removal, TF-IDF

---



## 🧪 How It Works

1. User attempts to post a tweet.
2. The tweet text is passed to the trained model.
3. Based on confidence score:
   - If **toxic**, the tweet is **blocked**.
   - If **potentially harmful**, the tweet is **flagged**.
   - Else, it's **allowed** to post.

---

## 📂 Project Structure

