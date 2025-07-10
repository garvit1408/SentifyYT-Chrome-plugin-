# 🎯 SentifyYT - Chrome Plugin for Influencer Comment Analysis
![image](https://github.com/user-attachments/assets/2ac9a396-4a79-4185-84ad-b0ae61077675)




**SentifyYT** is a powerful Chrome extension developed for influencers to **analyze YouTube comments in real time**. It performs advanced sentiment analysis, summarization, and keyword extraction to help content creators understand their audience better and optimize their content strategy.

---

## 🧩 Problem Statement

Influencers often receive **thousands of comments** on their YouTube videos, making it impractical to analyze feedback manually. This results in missed insights, poor engagement strategies, and ineffective content updates.

---

## 🚀 Our Solution

SentifyYT empowers influencers by providing **automated insights** from their comment sections:

### 🔍 Key Features

- **Real-Time Sentiment Analysis**  
  Classifies comments as Positive, Neutral, or Negative.

- **Sentiment Trend Visualization**  
  Tracks how sentiment shifts over time.

- **Comment Summarization**  
  Highlights most-discussed themes and suggestions using NLP.

- **Word Cloud**  
  Visualizes frequently used terms to identify trends and pain points.

- **Spam and Troll Detection**  
  Filters out spam, bots, and toxic comments.

- **Export Functionality**  
  Download reports as PDF or CSV for deeper analysis or collaboration.

---

## ⚙️ Tech Stack

### Backend & ML:
- Python, Flask, scikit-learn, spaCy, NLTK, Optuna
- MLflow for model tracking
- DVC for data versioning
- AWS S3 & EC2 for deployment

### Frontend:
- JavaScript, HTML, CSS
- Chrome Extension APIs
- D3.js for visualizations

### DevOps:
- GitHub Actions for CI/CD
- Docker, AWS CodeDeploy, CloudWatch

---
---

## 🧪 How to Use

1. **Clone the Repo**  
   ```bash
   git clone https://github.com/garvit1408/SentifyYT-Chrome-plugin-.git
   ```
2.	**Run Backend Server**
    ```bash
    cd api
    python app.py
    ```
3.	**Load Chrome Extension**
- Go to chrome://extensions
- Enable Developer mode
- Click Load unpacked and select the chrome_extension folder

## 🧱 Challenges We Solved
- Handling slang, emojis, sarcasm, and multi-language comments
- Dealing with class imbalance and noisy data
- Ensuring low latency for real-time analysis
- Designing a clean UX in a small browser popup

## 📌 Future Enhancements
- Multi-platform support (Instagram, TikTok)
- Language translation and multi-lingual NLP
- Deeper comment context linking to video timestamps
- Integration with Google Sheets and Notion for reporting


- **Garvit Singh** – [@garvit1408](https://github.com/garvit1408)  
  M.Tech CSE @ IIIT-Delhi | Data Science Enthusiast  
  🌐 [My Bento Profile](https://bento.me/garvit14)
