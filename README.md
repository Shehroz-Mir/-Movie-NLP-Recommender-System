# 🎬 Movie NLP Recommender System

This project performs Natural Language Processing (NLP) on a movie dataset (Rotten Tomatoes) to build a **content-based movie recommender system**. It combines classical NLP techniques (TF-IDF, n-grams, Word2Vec) to explore, visualize, and recommend similar movies based on user queries.

---

## 📌 Features

- Text preprocessing (cleaning, tokenization, lemmatization)
- Exploratory analysis using:
  - Word frequencies
  - Bigrams & trigrams
  - Word clouds
- Two recommendation systems:
  - **TF-IDF + Cosine Similarity**
  - **Word2Vec Embeddings (CBOW & Skip-gram)**

---

## 🧠 Techniques Used

- **Libraries**: `nltk`, `pandas`, `sklearn`, `seaborn`, `matplotlib`, `gensim`
- **NLP Concepts**:
  - Stopword removal, lemmatization
  - TF-IDF vectorization
  - Word2Vec (CBOW & Skip-gram models)
- **Similarity Measures**:
  - Cosine similarity on TF-IDF & Word2Vec vectors
- **Visualization**:
  - Word frequency bar charts
  - Word clouds

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/movie-nlp-recommender.git
   cd movie-nlp-recommender
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset `rotten_tomatoes_movies.csv` and place it in the project folder.

4. Run the notebook:
   ```bash
   jupyter notebook movie_recommender.ipynb
   ```

---

## 🔍 Example Recommendations

```text
Query: "A thrilling action-packed adventure with a heroic protagonist"

CBOW Recommendations:
- The Monster Squad
- The Boy And The Beast (Bakemono No Ko)
- Wallace & Gromit: The Curse of the Were-Rabbit

TF-IDF Recommendations:
- Escape Plan: The Extractors
- The Legion
- American Flyers
```

---

## 📁 Project Structure

```
movie-nlp-recommender/
│
├── movie_recommender.ipynb       # Jupyter notebook with full pipeline
├── rotten_tomatoes_movies.csv    # Dataset (not uploaded to GitHub)
├── README.md                     # Project overview
└── requirements.txt              # Python libraries used
```

---

## 🤝 Acknowledgements

- Dataset: Rotten Tomatoes
- Libraries: NLTK, Gensim, scikit-learn, seaborn

---

## 📬 Contact

Shehroz Mir — [LinkedIn](https://www.linkedin.com/in/shehrozmir/) | [GitHub](https://github.com/Shehroz-Mir)

---

⭐ If you like this project, feel free to star it and share!
