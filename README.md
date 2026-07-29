# 📈 Financial News Sentiment Analyzer

An end-to-end Python data pipeline that fetches live financial news headlines via Google News RSS and predicts market sentiment using a fine-tuned Hugging Face RoBERTa Transformer model.

## 🚀 Features
* **Live Scraping:** Automatically fetches real-time market headlines for any search topic or stock ticker.
* **Transformer Sentiment Analysis:** Uses `distil roberta-finetuned-financial-news-sentiment-analysis` to classify text into Positive, Neutral, or Negative with confidence scores.
* **Interactive Visualizations:** Renders Plotly donut charts to break down overall market sentiment.
* **Catalyst Extraction:** Automatically filters and highlights the top high-confidence positive and negative market news.
* **Data Export:** Saves analyzed results into a clean CSV spreadsheet.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **AI / NLP:** Hugging Face `transformers`, PyTorch
* **Data & Visualization:** `pandas`, `plotly`

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/nibodh-p/financial-sentiment-analysis.git](https://github.com/nibodh-p/financial-sentiment-analysis.git)
   cd financial-sentiment-analysis

