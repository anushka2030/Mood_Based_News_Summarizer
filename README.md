# 📰 Mood-Based News Summarizer  
### *AI-Generated News Summaries Based on Your Mood*

This project uses NLP + Machine Learning to summarize BBC news articles based on the **user’s mood**.  
It classifies articles by **emotion**, maps them to **sentiment**, and generates human-like summaries using a Transformer model, displayed through a beautiful **Gradio UI**.

---

## 🚀 Features

- 🧹 **Dataset Cleaning** — Deep cleaning for analysis & light cleaning for summarization  
- 🤖 **Emotion Classification** using `j-hartmann/emotion-english-distilroberta-base`  
- 😊 **Sentiment Mapping** (Positive / Negative / Neutral)  
- ✂️ **Abstractive Summarization** using `facebook/bart-large-cnn`  
- 🎨 **Interactive Gradio Interface** to browse news based on mood  
- 📊 **Automatic CSV Generation** (cleaned, emotion-labeled, sentiment-ready)

---
## Dataset Link
https://www.kaggle.com/datasets/pariza/bbc-news-summary


## 🧠 Workflow
BBC News Dataset → Cleaning → Emotion Detection → Sentiment Mapping → Summarization → Gradio UI



---

## 🔧 Technologies Used

- Python, Pandas, NumPy  
- HuggingFace Transformers  
- Datasets Library  
- Gradio  
- Matplotlib, Seaborn  

**Models Used**  
- Emotion: `j-hartmann/emotion-english-distilroberta-base`  
- Summarizer: `facebook/bart-large-cnn`

---

## ▶️ Running the App

1. Open the notebook in Google Colab  
2. Run preprocessing cell to generate `news_with_sentiments.csv`  
3. Run the Gradio app cell  
4. Click your public Gradio link  
5. Choose a **category** and **mood** → get top 10 AI-generated summaries

---

## 🌟 Example Output (UI)

- Select: **Technology + Positive**
- App returns top 10 tech articles with **positive sentiment**
- Each summary is highlighted with category & mood tag
- Human summary + AI summary shown together

---

## 📜 License
This project is open-source and free to use for learning and research.

---

## 💡 Author
**Anushka Chakravarti**

---


