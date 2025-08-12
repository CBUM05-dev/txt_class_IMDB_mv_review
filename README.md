# txt_class_IMDB_mv_review
#  IMDB Movie Reviews Sentiment Analysis

##  Overview
This project is a sentiment analysis model that classifies IMDB movie reviews as **positive** or **negative** using **TensorFlow** and **Keras**.  
We use an embedding layer to learn word representations, then a fully connected neural network to make predictions.

---

##  Dataset
We use the **IMDB dataset** provided by Keras:
- **50,000** movie reviews (25,000 for training, 25,000 for testing).
- Reviews are pre-tokenized into integers where each integer represents a specific word.
- We keep only the top **88,000** most frequent words to reduce noise.

---

