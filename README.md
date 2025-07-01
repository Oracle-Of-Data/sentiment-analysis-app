# 💬 Sentiment Analysis on Customer Feedback

An interactive web application built using **Streamlit**, performing real-time sentiment analysis on customer reviews using **TextBlob** and **VADER**. The app also supports real-time input, text cleaning, and graphical sentiment distribution.

## 🧠 Features

- Sentiment classification using VADER and TextBlob
- Text subjectivity and polarity scoring
- Clean user-entered text with `clean-text`
- Visual sentiment distribution histogram
- DataFrame output with analysis results
- Notebook version for step-by-step analysis (Colab)

## 🛠 Tech Stack

- **Streamlit** – Web UI  
- **TextBlob** & **VADER** – NLP sentiment engines  
- **pandas** – Data handling  
- **matplotlib** – Visualizations  
- **clean-text** – Text preprocessing  
- **Google Colab / Jupyter Notebook** – Notebook implementation

## 📊 Dataset

- File: `Reviews.csv`
- Fields used:
  - `Text`: Customer review content
  - `Score`: Original numerical rating

## 🔖 Topics

`sentiment-analysis` • `nlp` • `streamlit` • `textblob` • `vader` • `data-visualization` • `customer-feedback` • `rule-based-nlp` • `python`


## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Oracle-Of-Data/sentiment-analysis-app.git
cd sentiment-analysis-app
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
streamlit run SentAn_Streamlit.py
```

## 📄 Licensed under the [MIT License](./LICENSE).
