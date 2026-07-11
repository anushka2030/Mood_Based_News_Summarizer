# 📰 Mood-Based News Summarizer
### *AI-Generated News Summaries Based on Your Mood*

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Gradio](https://img.shields.io/badge/Gradio-Interface-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered NLP application that delivers **personalized news summaries based on the user's mood**. The system classifies emotions from user input, retrieves relevant BBC news articles, and generates concise summaries using state-of-the-art Transformer models through an interactive **Gradio interface**.

---

## 🚀 Features

- 🧹 **Dataset Cleaning** – Performs deep text cleaning for analysis and light preprocessing for summarization.
- 🎭 **Emotion Classification** – Predicts emotions using `j-hartmann/emotion-english-distilroberta-base`.
- 😊 **Sentiment Mapping** – Maps detected emotions into Positive, Negative, and Neutral sentiments.
- ✂️ **Abstractive Summarization** – Generates concise summaries using `facebook/bart-large-cnn`.
- 🎨 **Interactive Gradio Interface** – Browse AI-generated summaries based on mood and category.
- 📊 **Automated Dataset Generation** – Creates cleaned, emotion-labeled, and sentiment-ready CSV files.
- ⚡ **End-to-End NLP Pipeline** – From preprocessing to deployment-ready inference.

---

## 📂 Dataset

**BBC News Summary Dataset**

🔗 https://www.kaggle.com/datasets/pariza/bbc-news-summary

The dataset consists of BBC news articles spanning multiple categories. During preprocessing, articles are cleaned, assigned emotion labels using a Transformer-based classifier, mapped to sentiment classes, and stored in a structured CSV for efficient retrieval and summarization.

---

## 🧠 Workflow

```text
BBC News Dataset
        │
        ▼
Text Cleaning & Preprocessing
        │
        ▼
Emotion Classification
        │
        ▼
Sentiment Mapping
        │
        ▼
Article Filtering
        │
        ▼
BART Abstractive Summarization
        │
        ▼
Interactive Gradio Interface
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Hugging Face Transformers
- PyTorch
- Gradio
- Matplotlib
- Seaborn
- Google Colab

### 🤖 Models Used

| Task | Model |
|------|-------|
| Emotion Classification | `j-hartmann/emotion-english-distilroberta-base` |
| News Summarization | `facebook/bart-large-cnn` |

---

## ▶️ Running the Project

1. Clone the repository

```bash
git clone https://github.com/anushka2030/Mood_Based_News_Summarizer.git
cd Mood_Based_News_Summarizer
```

2. Install the required dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook in **Google Colab**.

4. Run the preprocessing cells to generate:

```
news_with_sentiments.csv
```

5. Run the Gradio application cell.

6. Open the generated Gradio link.

7. Select a **News Category** and **Mood** to receive AI-generated summaries.

---

## 🌟 Example Usage

**Input**

- Category: **Technology**
- Mood: **Positive**

**Output**

- Top matching technology articles
- Emotion & sentiment labels
- Human-written summary
- AI-generated abstractive summary

---

## 📸 Demo

> *(Add screenshots or GIFs of your Gradio interface here.)*

Example:

```
assets/home.png
assets/demo.gif
```

---

## 📈 Future Improvements

- 🌐 Deploy on Hugging Face Spaces
- 📰 Integrate live news APIs
- 🌍 Multilingual news summarization
- ⚡ Optimize inference speed
- 👤 Personalized recommendations based on user history

---

## 👩‍💻 Author

**Anushka Chakravarti**

- GitHub: https://github.com/anushka2030
- LinkedIn: https://www.linkedin.com/in/anushka-chakravarti-0a9b80292/

---

