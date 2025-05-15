# 🧠 Mental Health Support: Grief Analysis via Reddit Discussions

A research-oriented project that explores the mental health consequences of losing a family member through Reddit-based content analysis. This project automates the process of keyword extraction, Reddit scraping, subtopic discovery, and sentiment analysis to derive structured insights from public discourse.

---

## 📌 Overview

Social media platforms like Reddit offer users an outlet to anonymously share their grief and seek support. Our project aims to:

- Identify relevant keywords related to grief and loss
- Scrape posts from Reddit using these keywords
- Analyze sentiments and uncover subtopics in the discussions
- Visualize trends and draw meaningful conclusions from user-generated content

---

## 👥 Team

- Khushi Sachan — `2021-IMT-052`
- Shubham Kumar — `2021-IMT-095`
- Nihit Moolaney — `2021-IMT-069`  
- Abhijeet Singh — `2021-IMT-002`  
 


---

## 🧩 Project Pipeline

### 1. Keyword Search
- Extracted from trusted domain sources (e.g., Wikipedia, mental health articles)
- Cleaned and tokenized using NLP techniques
- Selected through frequency analysis and named entity recognition

### 2. Keyword Similarity Scoring
- Applied embedding-based similarity using Word2Vec, GloVe, or spaCy
- Computed cosine similarity against predefined target terms
- Filtered out irrelevant or low-context terms

### 3. Web Scraping (Reddit API)
- Utilized the `praw` library for Reddit API integration
- Queried specific subreddits for relevant discussions
- Collected metadata such as title, body, timestamp, score, and subreddit name
- Stored in CSV/JSON formats

### 4. Subtopic Extraction
- Used co-occurrence matrices and TF-IDF for keyword grouping
- Performed topic modeling using Latent Dirichlet Allocation (LDA)
- Identified subtopics:
  - Emotional coping mechanisms  
  - Community support and advice  
  - Shared personal experiences  

### 5. Analysis
- **Keyword Frequency Analysis** via word clouds and bar plots
- **Sentiment Analysis** using TextBlob/VADER
  - Classified posts as positive, negative, or neutral
  - Revealed sentiment trends and concerns over time

---

## 📈 Sample Insights

- Temporal patterns in grief-related conversations
- Emotional tone and engagement across subreddits
- Identification of high-impact support themes

---

## 🛠️ Technologies Used

- Python (NLP, data processing)
- `praw` (Reddit API wrapper)
- Gensim (LDA topic modeling)
- spaCy / GloVe / Word2Vec (embeddings)
- TextBlob / VADER (sentiment analysis)
- Matplotlib / WordCloud (visualizations)

## 📚 References
- Reddit API Documentation

- Wikipedia & mental health knowledge bases

- Research papers on grief and NLP techniques
