# IMDB Movie Reviews Sentiment Analysis

## Project Overview

This project focuses on sentiment analysis of movie reviews from the **IMDB 50K Dataset**, a balanced collection of positive and negative reviews. The goal is to classify user reviews as **positive** or **negative** using natural language processing (NLP) and deep learning techniques. The model is trained on preprocessed and cleaned text data using a Bidirectional GRU neural network.

---

## Technical Highlights

* **Dataset**:

  * 50,000 labeled reviews from IMDB
  * Balanced distribution: 25,000 positive and 25,000 negative

* **Exploratory Data Analysis (EDA)**:

  * Review length distribution and text length histograms
  * Sentiment-wise visualizations including word clouds and pie charts
  * Duplicate handling and basic statistics

* **Text Preprocessing & Cleaning**:

  * Removal of HTML tags, URLs, emojis, hashtags, mentions, special characters
  * Lowercasing, punctuation and stopword removal
  * Chat word normalization and contraction expansion
  * Tokenization and lemmatization

* **Model Architecture**:

  * **Tokenizer** and **padding** for sequence preparation
  * **Bidirectional GRU** layers with dropout and batch normalization
  * **Binary classification** using sigmoid activation
  * **Regularization** via `L2` and **early stopping** for generalization

* **Performance**:

  * Achieved \~91% training accuracy
  * Achieved \~80% validation accuracy
  * Visualizations of training and validation metrics included

---

## Purpose and Applications

* **Customer feedback analysis** in review platforms
* **Sentiment monitoring** for marketing and brand analysis
* **Movie recommendation engines** based on sentiment trends
* Educational tool for learning **NLP pipelines** and **deep learning** model deployment

---

## Installation

**Clone the repository**:

   ```bash
   git clone https://github.com/BhaveshBhakta/IMDB-Movie-Reviews-Sentiment-Analysis-Using-GRU.git
   cd IMDB-Movie-Reviews-Sentiment-Analysis-Using-GRU
   ```

---

## Collaboration

Contributions are welcome! You can:

* Extend the model using **LSTM**, **Transformers**, or **pretrained BERT**
* Add **streamlit/flask** web apps for live predictions
* Improve preprocessing using **custom NLP pipelines**

