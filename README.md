# Zeolite_Small_Language_Model

This project explores unsupervised learning and representation modeling on abstracts from research papers related to **zeolites**. It includes text extraction, dimensionality reduction, similarity analysis, clustering, and small language model fine-tuning.

---

## 📌 Project Overview

1. **Data Collection**  
   Downloaded ten peer-reviewed research papers on zeolites and extracted their abstracts.

2. **Preprocessing & Storage**  
   - Tokenized abstracts into individual sentences.
   - Saved the aggregated text in a plain text file (`abstract.txt`).

3. **Text Analysis**  
   Applied a range of NLP and unsupervised learning techniques:
   - TF-IDF vectorization
   - **PCA** (Principal Component Analysis)
   - **KMeans** for clustering algorithm
   - **Cosine similarity** for sentence relationship mapping
   - **Hierarchical clustering with dendrograms**

4. **Language Model Training**  
   Trained a lightweight language model on the dataset to explore domain-specific language representation.

---

## 🧪 Tech Stack

- Python 3.12+
- `scikit-learn`
- `matplotlib`
- `nltk`
- `numpy`
- `gensim` or `transformers` (for language modeling)
- Optional: `seaborn`, `scipy` for dendrograms

---


