# Bag of Words and TF-IDF in NLP

This is a brief overview of two foundational techniques in Natural Language Processing (NLP): Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF). These methods are used for text representation and feature extraction.

## 1. Bag of Words (BoW)

The Bag of Words model is a simple and effective way to represent text data. It converts text into a fixed-length vector of features based on the frequency of words in the document, disregarding grammar and word order.

### Steps:
- **Tokenization:** Split the text into words (tokens).
- **Vocabulary Creation:** Build a vocabulary of unique words from the dataset.
- **Vectorization:** Represent each document as a vector where each element corresponds to a word in the vocabulary, filled with the count of that word in the document.

---

## 2. Term Frequency-Inverse Document Frequency (TF-IDF)

TF-IDF is an advanced method that improves upon BoW by considering the importance of a word in a document relative to its frequency in the entire corpus. It helps in reducing the weight of common words and highlights more significant words.

### Components:
- **Term Frequency (TF):** Measures how frequently a term occurs in a document.
- **Inverse Document Frequency (IDF):** Measures how important a term is across all documents.

### TF-IDF Calculation:
TF-IDF(t, d) = TF(t, d) * IDF(t)
- TF (Term Frequency): Frequency of term t in document d.
- IDF (Inverse Document Frequency): Measures how common or rare a term is across all documents.

---
- **Bag of Words (BoW)** transforms text into a count-based vector representation, capturing word frequencies without considering context.
- **TF-IDF** enhances this representation by evaluating the significance of words in relation to their occurrence across multiple documents, emphasizing important terms.

These techniques serve as the foundation for many NLP applications, including text classification, sentiment analysis, and information retrieval.

--- 
