# Smart Feedback Analyzer

A cloud-native app that analyzes sentiment of user feedback using GCP services.

## 🔧 Tech Stack
- Flask (API hosted on Cloud Run)
- Pub/Sub
- Cloud Functions
- Natural Language API
- BigQuery or Firestore

## 📌 How it works
1. User submits feedback
2. Flask API publishes it to Pub/Sub
3. Cloud Function processes it and calls Natural Language API
4. Sentiment is stored in DB

## ▶️ Run Locally

```bash
pip install -r requirements.txt
python api/main.py
