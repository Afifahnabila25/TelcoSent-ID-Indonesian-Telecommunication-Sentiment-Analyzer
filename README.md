# TelcoSent-ID-Indonesian-Telecommunication-Sentiment-Analyzer

An interactive Natural Language Processing (NLP) mini-project designed to run on Google Colab. This application performs sentiment analysis on Indonesian text, specifically trained to classify user reviews and tweets regarding cellular service providers in Indonesia into positive or negative sentiments.

## 🚀 Features
* **Text Preprocessing:** Utilizes `Sastrawi` for Indonesian stemming and stopword removal, alongside regex for noise reduction (removing URLs, mentions, and hashtags).
* **N-Gram Feature Extraction:** Implements `TfidfVectorizer` with Bigrams (1, 2) to capture deeper contextual meaning in phrases rather than isolated words.
* **Machine Learning Model:** Powered by the `MultinomialNB` (Naive Bayes) algorithm, achieving reliable accuracy for text classification.
* **Interactive Interface:** A clean, infinite-loop input prompt directly within the notebook cell for real-time text analysis.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Libraries:** `pandas`, `scikit-learn` (Machine Learning), `Sastrawi` (Indonesian NLP), `re` (Regular Expressions)

## 📊 Dataset
The model is trained on a public dataset containing tweets about Indonesian cellular service providers.
* **Source:** [Dataset-Sentimen-Analisis-Bahasa-Indonesia](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia)
* **Labels:** `POSITIVE` / `NEGATIVE`

---
## 👨‍💻 Author
**Afifah Nabila Devi**
