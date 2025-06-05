# Reddit NLP Analysis on Uyghur-Related Discourse

This project explores how Reddit users discuss the Uyghur crisis through NLP techniques including topic modeling (LDA/NMF) and sentiment analysis (TextBlob, DistilBERT). The dataset includes 16,900+ Reddit posts and comments from subreddits like r/China, r/Sino, r/news, and r/Uyghur.

---

## 🔍 Objectives
- Identify dominant themes and topic clusters
- Compare sentiment polarity across subreddits and time
- Visualize discourse evolution and community framing

---

## 🧠 Key Methods
- Reddit scraping with `PRAW` (Python Reddit API Wrapper)
- NLP preprocessing: lemmatization, stopword removal, tokenization
- Sentiment analysis using TextBlob and HuggingFace’s DistilBERT
- Topic modeling using LDA and NMF
- t-SNE document embedding for cluster visualization

---

## 📈 Insights
- Subreddits show polarized framing (e.g., r/Sino = positive, r/humanrights = negative)
- Core topics include genocide, international relations, meta-moderation, and religion
- Posts are mostly neutral; comments show higher emotional polarity
- Temporal patterns match major media cycles (2017–2022)

---

## 🛠 Technologies Used
- Python (Pandas, NumPy)
- NLP: NLTK, SpaCy, TextBlob, Hugging Face Transformers
- Topic Modeling: Scikit-learn (TF-IDF, LDA, NMF)
- Visualization: Matplotlib, Seaborn, WordCloud, t-SNE

---

## 📁 Files
- `notebooks/reddit_uyghur_sentiment_analysis_clean.ipynb` — full analysis notebook
- `report/reddit_uyghur__sentiment_report.pdf` — standalone research report

---

## 📜 License
MIT 
