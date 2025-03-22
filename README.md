#  Resume Text Similarity & Job Matching with NLP + Web Scraping

This project combines **Natural Language Processing (NLP)** with **web scraping** to analyze and compare resume content against real-time job postings. It demonstrates how to build a smart pipeline that preprocesses text, generates embeddings, and finds the best matching roles using similarity scores.

---

## Overview

- Scrapes job descriptions from the **CareerJet API**
- Cleans and preprocesses resume text
- Trains **Word2Vec** models on resume content
- Computes **TF-IDF** and **cosine similarity** scores
- Visualizes similarities and keyword frequencies

---

##  Features

###  Web Scraping
- Fetches job descriptions using keyword search
- Parses job listings from the [CareerJet public API](http://public.api.careerjet.net/search)
- Enables real-time job-to-resume matching

### NLP Pipeline
- Custom tokenizer and stopword removal
- Text vectorization using:
  - `CountVectorizer`
  - `TF-IDF Vectorizer`
- Word embeddings using `Word2Vec` from `gensim`

### Similarity Analysis
- Calculates **cosine similarity** between resumes and job descriptions
- Compares traditional vectorization with Word2Vec embeddings

### Visualizations
- Heatmaps for similarity scores
- Bar plots for term frequency insights

---

##  Tech Stack

- **Python**
- `requests` for web scraping
- `pandas`, `numpy` for data wrangling
- `scikit-learn` for vectorization and similarity
- `gensim` for Word2Vec modeling
- `matplotlib`, `seaborn` for visualizations

---



